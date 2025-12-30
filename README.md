# RogueWordsInfo

Privacy and other info about the RogueWords game

## GitHub Pages Site

This repository hosts a GitHub Pages site with:
- **Privacy Policy**: Available at `/privacy-policy.html`
- **Home Page**: Landing page with links to documentation

## Accessing the Site

This repository uses GitHub Actions to automatically deploy to GitHub Pages. 

### Setup Instructions

1. Go to repository **Settings > Pages**
2. Under "Build and deployment":
   - Set **Source** to "GitHub Actions"
3. The workflow will automatically deploy when you push to the main/master branch

The site will be available at: `https://dreamti-me.github.io/RogueWordsInfo/`

Direct privacy policy URL: `https://dreamti-me.github.io/RogueWordsInfo/privacy-policy.html`

### Automatic Deployment

The `.github/workflows/pages.yml` workflow automatically:
- Builds the site with Jekyll when you push to main/master
- Deploys to GitHub Pages
- Can be manually triggered from the Actions tab

## Files

- `index.html` - Main landing page
- `privacy-policy.html` - Privacy policy page (HTML)
- `PRIVACY-POLICY.md` - Privacy policy (Markdown source)
- `_config.yml` - Jekyll configuration for GitHub Pages

## Local Development

To test locally with Jekyll:
```bash
# Install Jekyll (if not already installed)
gem install bundler jekyll

# Serve the site locally
jekyll serve

# Visit http://localhost:4000
```

## Updating the Privacy Policy

1. Edit `PRIVACY-POLICY.md` for the markdown version
2. Update `privacy-policy.html` to match
3. Commit and push changes
4. GitHub Pages will automatically rebuild the site
