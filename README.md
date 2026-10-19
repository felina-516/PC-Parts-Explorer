# PC Parts Explorer

A beginner-friendly static guide to seven computer parts. The site uses plain HTML and CSS with local SVG artwork; it has no build step or dependencies. Replace `[Your Name]` in each footer with your name before publishing.

## Deploy to GitHub Pages

1. Create a GitHub repository and upload the project files, keeping `index.html` at the repository root.
2. In the repository, open **Settings → Pages**.
3. Choose **Deploy from a branch**, select your main branch and the root (`/`) folder, then save. GitHub Pages will publish the site at the address it provides.

## Deploy to Vercel

1. Import the GitHub repository into Vercel (or upload this project folder).
2. Choose **Other** as the framework preset and leave the build command empty. Set the output directory to `.` (the project root).
3. Deploy. Vercel serves `index.html` directly; `404.html` is the custom not-found page.

## Replacing the illustrations

The SVG illustrations can optionally be replaced by real photos. Save each `.webp` or `.jpg` file inside `images/`, then edit that image's `src` in the HTML files to use its relative path (for example, `images/cpu.webp`). Add photo credits in the page or README and follow the image's license terms.
