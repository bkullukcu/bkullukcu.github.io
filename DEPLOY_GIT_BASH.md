# Deploy with Git Bash

1. Extract the website ZIP.
2. Open Git Bash and enter your local repository:

```bash
cd ~/Documents/bkullukcu.github.io
```

3. Create a safety branch:

```bash
git branch backup-before-industry-redesign
```

4. Remove the old website files but keep `.git`:

```bash
find . -mindepth 1 -maxdepth 1 ! -name '.git' -exec rm -rf {} +
```

5. Copy all files from the extracted website folder into the repository root. Example:

```bash
cp -r ~/Downloads/Berkay_Kullukcu_Industry_Portfolio/. .
```

6. Validate and push:

```bash
python -m json.tool data/en.json > /dev/null
python -m json.tool data/de.json > /dev/null
git add -A
git commit -m "Redesign portfolio for industry applications"
git push origin master
```

Use `main` instead of `master` if that is your active branch.
