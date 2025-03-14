# Jekyll Page Template

This template provides an easy way to set up a Jekyll-powered website using GitHub Pages or any other hosting platform. It's designed to streamline the development process and offer a solid foundation for your web projects.

## Features

- **Docker-based Local Development**: Eliminates the need for installing dependencies directly on your machine. Just have Docker installed, and you're ready to go.
- **GitHub Actions Workflow**: Automates the publishing process to GitHub Pages, making deployment effortless.
- **Minimal Mistakes Theme**: Incorporates a clean, responsive, and feature-rich Jekyll theme that's perfect for various types of websites.

## Quick Start

1. Clone this repository
2. Run `docker compose up` to start the local development server
3. Check `docker logs jekyll_dev -f` until it says **Server running...**
4. Open [http://localhost:4000](http://localhost:4000) in your browser to view your site
5. Edit files in the `_posts` directory to create new content

## Customization

- Modify `_config.yml` to personalize your site settings
- Add new pages in the `_pages` directory
- Customize the theme by overriding Minimal Mistakes config file `_config.yml` in your project

## Deployment

To deploy your site to GitHub Pages, follow these steps:

1. **Update GitHub Pages URL**: Modify the `repository` value in `_config.yml` to match your GitHub Pages URL (e.g., `https://username.github.io/your-repo-name`).
2. **Push Changes**: Commit and push your changes to your GitHub repository.
3. **Automatic Deployment**: The GitHub Actions workflow will automatically build and deploy your site to GitHub Pages for changes in the `main` branch.

Make sure your repository settings on GitHub are configured to use GitHub Pages.