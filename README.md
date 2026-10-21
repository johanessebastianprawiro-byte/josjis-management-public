# Josjis Management — Public Website

This folder is a standalone, public-facing version of the Josjis Management website for sharing from an agency bio. It keeps the service prices visible while excluding SPH names, client links, reports, screenshots, and campaign figures.

## Preview

Open `index.html` in a browser. No build step or package installation is required.

## Publish as a separate website

To keep the one-to-one website separate:

1. Create a new repository in the same GitHub account.
2. Add only the contents of this `josjis-public` folder to that repository. Do not upload the parent folder or the original website files.
3. In Netlify, create a new site by importing that new repository. Use the repository root as the publish directory; no build command is needed.
4. Netlify will assign the new site a separate URL. Set a custom domain or site name there if desired.

Review public contact details and obtain permission before adding identifiable client names, logos, work samples, testimonials, screenshots, or performance figures. The listed service prices and package details are taken from the current website and should be reviewed before publication if they have changed.

## Assets and security

The hero uses the locally included video and poster. The approach section uses a stock video by cottonbro studio from Pexels, with its Pexels poster image; these Pexels origins are allowed by the Content Security Policy in `netlify.toml`. Pexels videos are free to use under the [Pexels License](https://www.pexels.com/license/).
