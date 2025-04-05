
# Sumeet Singh Mankoo - Personal Website

This project hosts a simple personal website for Sumeet Singh Mankoo, featuring links to his blog and LinkedIn profile. 
The website is deployed on GitHub Pages.

## Project Structure

```
.github/
├── workflows/
│   └── static.yml      # Deploy to GitHub Pages
index.html               # Main HTML file for the personal website
```

### index.html

This file contains the simple static page displaying Sumeet's name and links to his blog and LinkedIn profile. 
It follows a modern and minimalistic design.

## Deployment

The project uses GitHub Actions to automate deployment to GitHub Pages.

### Deploy to GitHub Pages

The `static.yml` workflow triggers on pushes to the `main` branch. 
It deploys the static content to GitHub Pages using the `actions/deploy-pages@v4` action.

## How to Use

1. Fork and clone the repository.
2. Push changes to the `main` branch to trigger the deployment workflows.
3. Access the website on:
   - GitHub Pages URL: `https://<username>.github.io/<repository-name>/`

## Author

Sumeet Singh Mankoo
