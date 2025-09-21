# How to Add to Your GitHub Profile

After the GitHub Action runs and creates the `github-breakout` branch with the SVG files, add this to your profile README.md:

```markdown
## GitHub Contributions Breakout Game

<picture>
  <source
    media="(prefers-color-scheme: dark)"
    srcset="https://raw.githubusercontent.com/Sheriffelrefaey/Sheriffelrefaey/github-breakout/images/breakout-dark.svg"
  />
  <source
    media="(prefers-color-scheme: light)"
    srcset="https://raw.githubusercontent.com/Sheriffelrefaey/Sheriffelrefaey/github-breakout/images/breakout-light.svg"
  />
  <img alt="GitHub Breakout Game" src="https://raw.githubusercontent.com/Sheriffelrefaey/Sheriffelrefaey/github-breakout/images/breakout-light.svg" />
</picture>
```

## Setup Steps:

1. **Copy the workflow file** (`.github/workflows/generate-breakout.yml`) to your profile repository (the one named after your username)

2. **Run the workflow** manually first time:
   - Go to Actions tab in your profile repository
   - Select "Generate Breakout SVG" workflow
   - Click "Run workflow"

3. **Wait for completion** - the workflow will create a `github-breakout` branch with the SVG files

4. **Add the HTML snippet** above to your profile README.md

5. **Commit and push** your README changes

The SVGs will automatically update daily based on your contribution activity!