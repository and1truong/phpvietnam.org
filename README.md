# PHP Vietnam landing page

Temporary, buildless landing page for `phpvietnam.org`. The site uses plain HTML and CSS so GitHub Pages can publish directly from the repository root.

## Preview

```sh
python3 -m http.server 8000
```

Open <http://localhost:8000>.

## Deployment

Publish the repository's `master` branch from `/` with GitHub Pages. The `CNAME` file declares `phpvietnam.org`; configure the apex and `www` records in Cloudflare according to [GitHub Pages custom domain guidance](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site).
