# kq-website

Static landing site for KQ with pages for KS1, KS2, KS3, GCSE, and entrance exams.

## Preview locally

You can view the site by serving the static files from the repository root:

1. Open a terminal in the project directory.
2. Start a simple local server (choose one of the options below):
   - Python 3: `python3 -m http.server 8000`
   - Node.js (serve): `npx serve .`
3. Open http://localhost:8000 in your browser (or the port shown by `serve`).

Alternatively, you can double-click `index.html` to open it directly in your browser, but some browsers block local asset loading; using a local server is recommended.

## Deployment

The site is a set of static HTML and CSS files and can be deployed on any static host (e.g., Netlify). Point your host to the repository root as the publish directory.
