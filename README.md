# Personal Blog

Personal technical blog powered by [Hexo](https://hexo.io/).

## Development

```bash
npm install
npm run server
```

The local site runs at `http://localhost:4000/personal-blog/`.

## Write

```bash
npm run new -- "my-new-post"
```

Posts live in `source/_posts`.

## Build

```bash
npm run deploy
```

The generated site is written to `public`.

## Deployment

Pushing to `main` triggers `.github/workflows/pages.yml`, builds the Hexo site, and deploys it to GitHub Pages.

Default Pages URL:

```text
https://liguochuan00.github.io/personal-blog/
```
