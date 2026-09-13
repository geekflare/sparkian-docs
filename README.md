<br/>
<div align="center">
  <img alt="Sparkian" src="fern/docs/assets/logo-dark.svg#gh-dark-mode-only" height="40">
  <img alt="Sparkian" src="fern/docs/assets/logo-light.svg#gh-light-mode-only" height="40">

  <h1>Sparkian Docs</h1>

  <p>
    Source for <a href="https://docs.sparkian.com">docs.sparkian.com</a> — the documentation site for
    <a href="https://sparkian.com">Sparkian</a>, the AI workspace to chat, generate images, and more.
  </p>
</div>

<br/>

## About

This repo holds the content and configuration for Sparkian's docs site, built with [Fern](https://buildwithfern.com). Pages are written in MDX under `fern/docs/pages`, and the site's navigation, theme, and metadata are configured in [`fern/docs.yml`](fern/docs.yml).

## Working locally

Install the Fern CLI, then preview the site:

```bash
npm install -g fern-api
fern docs dev
```

Validate the docs configuration before opening a pull request:

```bash
fern check
```

## Contributing

- Add or edit pages under `fern/docs/pages/`, then register them in [`fern/docs.yml`](fern/docs.yml).
- Open a pull request against `main`. A preview link is posted automatically once checks pass.
- Merges to `main` publish straight to [docs.sparkian.com](https://docs.sparkian.com).

## License

Content in this repository is © Geekflare. See [sparkian.com](https://sparkian.com) for product details.
