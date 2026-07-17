# Conference presentation videos

The presentations page reads its content from:

- `config.json` for English
- `config-de.json` for German

Each presentation has a `video` object.

## Recommended: YouTube embed

Upload the recording to YouTube as **Unlisted** and copy the video ID from the URL.

Example URL:

```text
https://www.youtube.com/watch?v=ABC123xyz
```

Use only `ABC123xyz` in both configuration files:

```json
"video": {
  "type": "youtube",
  "youtubeId": "ABC123xyz",
  "message": "Watch the presentation"
}
```

The website uses YouTube's privacy-enhanced embed domain automatically.

## Local MP4

A locally hosted video uses this format:

```json
"video": {
  "type": "local",
  "url": "./videos/example-presentation.mp4",
  "poster": "./videos/example-presentation-poster.jpg",
  "message": "Watch the presentation"
}
```

Use MP4 with H.264 video and AAC audio for broad browser support.

## Placeholder

Until a recording is ready:

```json
"video": {
  "type": "placeholder",
  "message": "Presentation video coming soon"
}
```

Make the corresponding change in both `config.json` and `config-de.json`. The video itself remains English; only the surrounding interface text is translated.
