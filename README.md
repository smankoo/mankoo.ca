
# Sumeet Singh Mankoo - Personal Website

This project hosts a simple personal website for Sumeet Singh Mankoo, featuring links to his blog and LinkedIn profile. The website is deployed on both AWS S3 and GitHub Pages.

## Project Structure

```
.github/
├── workflows/
│   ├── deploy.yml      # Deploy to AWS S3
│   └── static.yml      # Deploy to GitHub Pages
index.html               # Main HTML file for the personal website
```

### index.html

This file contains the simple static page displaying Sumeet's name and links to his blog and LinkedIn profile. It follows a modern and minimalistic design.

## Deployment

The project uses GitHub Actions to automate deployment to both AWS S3 and GitHub Pages.

### Deploy to S3

The `deploy.yml` workflow triggers on pushes to the `main` branch and deploys the website to an S3 bucket. Ensure that the following secrets are configured in your GitHub repository:

- `AWS_ACCESS_KEY_ID`
- `AWS_SECRET_ACCESS_KEY`
- `AWS_REGION`
- `S3_BUCKET_NAME`

### Deploy to GitHub Pages

The `static.yml` workflow also triggers on pushes to the `main` branch. It deploys the static content to GitHub Pages using the `actions/deploy-pages@v4` action.

## How to Use

1. Fork and clone the repository.
2. Set up the required GitHub Secrets for AWS deployment.
3. Push changes to the `main` branch to trigger the deployment workflows.
4. Access the website on:
   - S3 Bucket URL: `http://<bucket-name>.s3-website.<region>.amazonaws.com/`
   - GitHub Pages URL: `https://<username>.github.io/<repository-name>/`

## Author

Sumeet Singh Mankoo
