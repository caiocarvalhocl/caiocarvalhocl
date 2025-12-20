# 🚀 GitHub Profile Setup Guide

## Step 1: Create the Repository

1. Go to [github.com/new](https://github.com/new)
2. Repository name: `caiocarvalhocl` (must match your username exactly!)
3. Make it **Public**
4. Check **Add a README file**
5. Click **Create repository**

## Step 2: Add the README

1. Replace the content of `README.md` with the content from this folder
2. Commit the changes

## Step 3: Enable Snake Animation

1. Go to your new repo's **Settings** → **Actions** → **General**
2. Under "Workflow permissions", select **Read and write permissions**
3. Save changes
4. Go to **Actions** tab
5. Click on **Generate Snake Animation** workflow
6. Click **Run workflow** → **Run workflow**
7. Wait for it to complete (creates the `output` branch with snake SVGs)

## Step 4: Customize

### Featured Projects
Edit the README to add your actual repositories:

```markdown
[![Repo Card](https://github-readme-stats.vercel.app/api/pin/?username=caiocarvalhocl&repo=YOUR-REPO-NAME&theme=dark&hide_border=true&bg_color=0d1117&title_color=22C55E&icon_color=22C55E)](https://github.com/caiocarvalhocl/YOUR-REPO-NAME)
```

### If Stats Don't Load
The GitHub Stats cards use [github-readme-stats](https://github.com/anuraghazra/github-readme-stats). If they show errors, you can deploy your own instance for free on Vercel.

## File Structure

```
caiocarvalhocl/
├── README.md                    # Your profile README
└── .github/
    └── workflows/
        └── snake.yml            # Snake animation workflow
```

## Troubleshooting

### Snake animation not showing?
- Make sure the workflow ran successfully
- Check that the `output` branch was created
- The snake images are at:
  - `https://raw.githubusercontent.com/caiocarvalhocl/caiocarvalhocl/output/github-snake.svg`
  - `https://raw.githubusercontent.com/caiocarvalhocl/caiocarvalhocl/output/github-snake-dark.svg`

### Stats showing "Error fetching data"?
- Your repositories might be set to private
- GitHub's API might be rate-limited (wait a few minutes)

---

Enjoy your new profile! 🎉
