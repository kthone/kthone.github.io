# Taehoon Kim — academic homepage

A responsive, dependency-free website for https://kthone.github.io/.

## Edit

- `index.html`: biography, publications, education, links.
- `style.css`: layout, typography, responsive breakpoints.
- `assets/`: portrait and publication images from the previous personal homepage.

## Preview

```sh
python3 -m http.server 8765 --bind 127.0.0.1
```

## Deploy

GitHub Pages: deploy from the `main` branch, `/` (root). `.nojekyll` bypasses Jekyll. Pushing changes to `main` updates the site.

## Content sources

- https://sites.google.com/view/taehoonkim0723 (biography, publications, images, education, service, social links)
- Linked arXiv records (paper titles)

Layout inspiration: https://junoh-kang.github.io/ and https://mjmjeong.github.io/. Implementation is original; no template or code copied. No private research results are included. Contact uses the address in the original site's Contact section. No CV link is shown because no verified CV was supplied.
