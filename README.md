# Awesome Decap [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of resources for [Decap CMS](https://decapcms.org) (formerly Netlify CMS), the open source, Git-based CMS for static site generators.

Many projects still carry the old `netlify-cms` name. They are listed when they work with Decap or are useful as a reference.

## Contents

- [Official](#official)
- [Documentation](#documentation)
- [Authentication](#authentication)
- [Framework Integrations](#framework-integrations)
- [Starters and Templates](#starters-and-templates)
- [Widgets](#widgets)
- [Tooling](#tooling)
- [Related Lists](#related-lists)

## Official

- [Decap CMS](https://github.com/decaporg/decap-cms) - The core repository.
- [decapcms.org](https://decapcms.org) - Website, docs and blog.
- [decap-website](https://github.com/decaporg/decap-website) - Source of the website and docs.
- [Community chat](https://decapcms.org/chat) - Discord server for questions and discussion.
- [decap-server](https://www.npmjs.com/package/decap-server) - Proxy server for editing a local Git repository during development.

## Documentation

- [Basic steps](https://decapcms.org/docs/basic-steps/) - Add Decap to an existing site.
- [Start with a template](https://decapcms.org/docs/start-with-a-template/) - Official one-click starters.
- [Configuration options](https://decapcms.org/docs/configuration-options/) - Full `config.yml` reference.
- [Widgets](https://decapcms.org/docs/widgets/) - Built-in field widgets.
- [Backends overview](https://decapcms.org/docs/backends-overview/) - GitHub, GitLab, Bitbucket, Azure, Gitea, Git Gateway and more.
- [Editorial workflows](https://decapcms.org/docs/editorial-workflows/) - Draft, review and publish via pull requests.
- [Open authoring](https://decapcms.org/docs/open-authoring/) - Let contributors without write access propose changes from forks.
- [i18n support](https://decapcms.org/docs/i18n/) - Multilingual content structures.
- [Creating custom widgets](https://decapcms.org/docs/custom-widgets/) - Register your own field controls and previews.
- [Creating custom previews](https://decapcms.org/docs/customization/) - Preview templates and styles.
- [Work with a local repository](https://decapcms.org/docs/decap-proxy/) - Edit content locally without a remote backend.
- [External OAuth clients](https://decapcms.org/docs/external-oauth-clients/) - Community-maintained OAuth providers for hosting outside Netlify.
- [Examples](https://decapcms.org/docs/examples/) - Sites and projects built with Decap.

## Authentication

OAuth providers for running Decap with the GitHub (or other) backend outside Netlify Identity.

- [decap-proxy](https://github.com/sterlingwes/decap-proxy) - GitHub OAuth proxy as a Cloudflare Worker.
- [netlify-cms-cloudflare-pages](https://github.com/i40west/netlify-cms-cloudflare-pages) - OAuth API on Cloudflare Pages Functions.
- [sveltia-cms-auth](https://github.com/sveltia/sveltia-cms-auth) - Cloudflare Workers GitHub/GitLab authenticator, compatible with Decap.
- [netlify-cms-github-oauth-provider](https://github.com/vencax/netlify-cms-github-oauth-provider) - Node.js/Express GitHub OAuth client.
- [netlify-cms-oauth-provider-node](https://github.com/bericp1/netlify-cms-oauth-provider-node) - Stateless provider with built-in Vercel serverless support.
- [netlify-cms-oauth-provider-go](https://github.com/igk1972/netlify-cms-oauth-provider-go) - Go implementation.
- [netlify-cms-oauth-provider-python](https://github.com/davidejones/netlify-cms-oauth-provider-python) - Python implementation.
- [decap-cms-github-backend](https://github.com/njfamirm/decap-cms-github-backend) - GitHub OAuth backend.
- [decap-cms-oauth-provider](https://github.com/openaq/decap-cms-oauth-provider) - GitHub OAuth provider for AWS Lambda.
- [decap-cms-google-apps-script](https://github.com/nuzulul/decap-cms-google-apps-script) - GitHub OAuth client in Google Apps Script.

## Framework Integrations

### Astro

- [astro-decap-cms-oauth](https://github.com/dorukgezici/astro-decap-cms-oauth) - Adds the admin dashboard and GitHub OAuth routes to an Astro project.
- [astro-netlify-cms](https://github.com/delucis/astro-netlify-cms) - Integration that adds the admin dashboard to any Astro project.
- [astro-decap-cms](https://github.com/miseya/astro-decap-cms) - Admin dashboard integration loading Decap from a CDN for faster builds.

### Gatsby

- [gatsby-plugin-decap-cms](https://github.com/decaporg/gatsby-plugin-decap-cms) - Official plugin that generates the Decap single page app.

### Hugo

- [hugomods/decap-cms](https://github.com/hugomods/decap-cms) - Hugo module for Decap CMS. (experimental)
- [headless-cms](https://github.com/privatemaker/headless-cms) - Hugo module for Decap and Sveltia CMS.
- [hbstack/decap-cms](https://github.com/hbstack/decap-cms) - Decap module for the HB Framework.

### Nuxt

- [nuxt-decap-cms](https://github.com/eddie-vallier/nuxt-decap-cms) - Nuxt module with Nuxt Content compatibility and live preview. (archived)

### Vite

- [vite-plugin-decap-cms](https://github.com/ghostrider-05/vite-plugin-decap-cms) - Configure Decap from a Vite project.

## Starters and Templates

### Astro

- [Intermediate-Astro-Decap-CMS](https://github.com/CodeStitchOfficial/Intermediate-Astro-Decap-CMS) - Astro kit with a Decap-powered blog on Content Collections.
- [astro-decap-cloudflare-starter](https://github.com/jshuntley/astro-decap-cloudflare-starter) - Astro and Decap on Cloudflare Pages, with a setup guide.
- [casper](https://github.com/AntonyLeons/casper) - Casper theme for Astro with Algolia search and Decap.

### Eleventy

- [eleventy-netlify-boilerplate](https://github.com/danurbanowicz/eleventy-netlify-boilerplate) - Blog template for Eleventy and Decap.
- [Intermediate-Website-Kit-SASS](https://github.com/CodeStitchOfficial/Intermediate-Website-Kit-SASS) - Eleventy, Decap and Sass kit.

### Gatsby

- [gatsby-starter-decap-cms](https://github.com/decaporg/gatsby-starter-decap-cms) - Official Gatsby example project.
- [gatsby-starter-henlo](https://github.com/clean-commit/gatsby-starter-henlo) - Block-based Gatsby starter styled with Tailwind CSS.

### Hexo

- [hexo-cms-example](https://github.com/decaporg/hexo-cms-example) - Official Hexo example.

### Hugo

- [one-click-hugo-cms](https://github.com/decaporg/one-click-hugo-cms) - Official Hugo template.
- [hugolify-template](https://github.com/Hugolify/hugolify-template) - Hugo and Bootstrap framework with Decap and other Git-based CMSs.

### Jekyll

- [jekyll-decap-cms](https://github.com/decaporg/jekyll-decap-cms) - Official Jekyll starter.

### Next.js

- [nextjs-netlify-blog-template](https://github.com/wutali/nextjs-netlify-blog-template) - Next.js blogging template.
- [nextjs-blog-tailwind-starter](https://github.com/ositaka/nextjs-blog-tailwind-starter) - Next.js blog with Tailwind CSS and Contentlayer.

## Widgets

Legacy `netlify-cms-widget-*` packages may need small changes to register with Decap 3.

- [decap-cms-widget-starter](https://github.com/iamspark1e/decap-cms-widget-starter) - Vite starter for custom widget development.
- [decap-cms-widget-id](https://github.com/clean-commit/decap-cms-widget-id) - Generate unique IDs for content.
- [decap-cms-widget-permalink](https://github.com/clean-commit/decap-cms-widget-permalink) - Permalink field.
- [netlify-cms-widget-nested-select](https://github.com/kbravh/netlify-cms-widget-nested-select) - Conditional second select, for example subcategories.
- [netlify-cms-widget-async-select](https://github.com/chrisboustead/netlify-cms-widget-async-select) - Select populated from a remote endpoint.
- [netlify-cms-widget-colorpicker](https://github.com/felixboet/netlify-cms-widget-colorpicker) - Color picker supporting HEX, RGBA and named colors.
- [netlify-cms-widgets](https://github.com/d4rekanguok/netlify-cms-widgets) - Collection of custom widgets. (archived)
- [netlify-cms-widget-starter](https://github.com/netlify/netlify-cms-widget-starter) - Original widget boilerplate. (archived)

## Tooling

- [decap-extras](https://github.com/allejo/decap-extras) - TypeScript utilities for working with Decap in a type-safe way.
- [netlify-ts](https://github.com/jsaari97/netlify-ts) - Generate TypeScript types from collection config.
- [docker-decap-cms-standalone](https://github.com/itsmejoeeey/docker-decap-cms-standalone) - Docker image to self-host Decap.
- [responsive-decap](https://github.com/hithismani/responsive-decap) - Mobile-responsive CSS for the admin UI.

## Related Lists

- [awesome-decap-cms](https://github.com/nuzulul/awesome-decap-cms) - Another collection of Decap resources.

## Contributing

Contributions welcome. Read the [contribution guidelines](contributing.md) first.
