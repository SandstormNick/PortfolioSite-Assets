# PortfolioSite-Assets

This repository is used for hosting static assets, primarily images, via GitHub Pages. These assets can be referenced and used by other websites, making it easy to share and manage resources for portfolio or other web projects.

## Usage

All assets in this repository are publicly available and can be accessed directly through GitHub Pages URLs. Simply copy the URL of the desired image or asset to use it in your website or project.

## How it Works

- Assets (such as images) are stored in the repository.
- GitHub Pages is enabled for this repository to serve the assets.
- Other websites can link to or embed these assets using the direct URLs provided by GitHub Pages.

## GitHub Actions Workflow

This repository uses a GitHub Actions workflow to automate image optimization and publishing:

- When an image file of type `.jpg`, `.jpeg`, or `.png` is committed to the repository, the workflow is triggered.
- The workflow uses tools to convert these images into modern web image formats: `.webp` and `.avif`.
- A GitHub bot then commits the newly generated `.webp` and `.avif` images back to the repository, making them available via GitHub Pages.

This ensures that your assets are optimized for web use and accessible in the latest formats.

## Example

An image in this repo can be used by copying its GitHub Pages URL (e.g., `https://sandstormnick.github.io/PortfolioSite-Assets/path/to/image.png`) and referencing it in the HTML or CSS.
