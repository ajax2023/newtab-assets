# Newtab Assets

This repository contains the static assets (images, icons, etc.) used in the Newtab DND application.

## Directory Structure

- `/new-button-images/` - Contains all button icons and images used in the application
- `/webp_images/` - Contains all button icons and images in WebP format for optimal performance

## Usage

These assets are automatically deployed to Cloudflare Pages and can be accessed via:
`https://newtab-assets.pages.dev/webp_images/[filename]`

Example:
`https://newtab-assets.pages.dev/webp_images/google.webp`

## Adding New Images

### Adding Non-WebP Images

1. Add new images to the appropriate directory
2. Commit and push your changes
3. Cloudflare Pages will automatically deploy the updates

### Adding WebP Images

1. Convert your images to WebP format for best performance
2. Add new images to the `webp_images` directory
3. Commit and push your changes
4. Cloudflare Pages will automatically deploy the updates
