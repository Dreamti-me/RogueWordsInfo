# RogueWordsInfo

Privacy and other info about the RogueWords game

## GitHub Pages Site

This repository hosts a GitHub Pages site with:
- **Privacy Policy**: Available at `/privacy-policy.html`
- **Home Page**: Landing page with links to documentation

## Accessing the Site

Once GitHub Pages is enabled for this repository:
1. Go to repository Settings > Pages
2. Set Source to "Deploy from a branch"
3. Select branch: `main` (or `master`) and folder: `/ (root)`
4. Save the settings

The site will be available at: `https://dreamti-me.github.io/RogueWordsInfo/`

Direct privacy policy URL: `https://dreamti-me.github.io/RogueWordsInfo/privacy-policy.html`

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
