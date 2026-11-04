# seabrick.ca -> seabrick.com

A one-page GitHub Pages site whose only job is to send every request for seabrick.ca (and www.seabrick.ca) to the
same path on https://seabrick.com. GitHub Pages allows one custom domain per site, so the second domain needs
its own repository.

`dist/index.html` and `dist/404.html` are the same file: a JavaScript redirect that keeps the path, with a
meta refresh fallback. `dist/CNAME` holds the custom domain.
