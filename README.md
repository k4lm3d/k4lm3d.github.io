# Site details.

  > General information about the site

## Site information

  - Site name:  `profile-site`
  - Owner:  `k4lm3d`
  - Description: `profile`
  - Theme: [Blowfish](https://github.com/nunocoracao/blowfish/) by [Nuno Coracao](https://n9o.xyz) [![GitHub release (latest by date)](https://img.shields.io/github/v/release/nunocoracao/blowfish?style=flat-square)](https://github.com/nunocoracao/blowfish/releases)

[![Minimum Hugo Version](https://img.shields.io/static/v1?label=min-HUGO-version&message=0.87.0&color=blue&logo=hugo)](https://github.com/gohugoio/hugo/releases/tag/v0.87.0)
[![GitHub](https://img.shields.io/github/license/nunocoracao/blowfish)](https://github.com/nunocoracao/blowfish/blob/main/LICENSE)
[![Blowfish](https://img.shields.io/badge/Hugo--Themes-@Blowfish-blue)](https://themes.gohugo.io/themes/blowfish/)
![code-size](https://img.shields.io/github/languages/code-size/nunocoracao/blowfish)

## Build & deploy

  > Settings for Continuous Deployment from a Git repository

### Repository

  - Current repository: [github.com/k4lm3d/](https://github.com/k4lm3d/)

### Build settings

  - Base directory: `/`
  - Build command: `hugo`
  [![Hugo](https://img.shields.io/badge/Hugo-%5E0.101.0-ff4088?style=flat-square&logo=hugo)](https://gohugo.io/)
  - Publish directory: `public`
  - Builds: `Active`

## Domains

  > Use your own domain for your site

### Custom domains

  - Default subdomain: [k4lm3d.github.io](https://k4lm3d.github.io)
  - Primary domain: [kalmed.localplayer.dev](https://kalmed.localplayer.dev)
  - Redirects automatically to primary domain: 
  - Domain alias: https://kalmed.onrender.com 

## Website launching offline

  > Go to http://localhost:1313

  > Launch by using the following command:

  - `hugo server`
    + When you run `hugo server`, when the contents of the files change, the page automatically refreshes with the changes.
  - `hugo server -D` or `hugo server --buildDrafts`
    + By default all posts and pages are created as a draft. If you want to render these pages, remove the property `draft: true` from the metadata, set the property `draft: false` or add `-D`/`--buildDrafts` parameter to `hugo` command.
  - `hugo serve --disableFastRender`
    + Since the theme use ***`.Scratch`*** in Hugo to implement some features, it is highly recommended that you add `--disableFastRender` parameter to hugo server command for the live preview of the page you are editing.
  - `hugo server -e production`
    + Default environments are `development` with `hugo serve` and production with hugo.
    + Due to limitations in the local `development` environment, the **comment system**, **CDN** and **fingerprint** will not be enabled in the `development` environment.
    + You could enable these features with `hugo server -e production`.
  - `hugo server --cleanDestinationDir`
    + This command is used to remove files from destination not found in static directori.

## Build the website

  - When your site is ready to deploy, run the `hugo` command.
  - A *`public`* folder will be generated, containing all static content and assets for your website. It can now be deployed on any web server.

***

### Resources

  - [Theme Website of Blowfish](https://blowfish.page/)
  - [Hugo Documentation](https://gohugo.io/documentation/)
  - [Host on GitHub Pages | Hugo Docs](https://gohugo.io/host-and-deploy/host-on-github-pages/)

### Keyboard Shortcuts

  - Visual Studio Code's [Keyboard Shortcuts Reference](https://code.visualstudio.com/shortcuts/keyboard-shortcuts-windows.pdf)
  - *Open/New Terminal* -> `Ctrl` + `Shift` + <code>`</code>
  - *Markdown Preview* -> `Ctrl` + `Shift` + `V`
  - *Markdown Preview to the left* -> `Ctrl` + `K` + `V`

<!-- TODO: Tasks after building the website -->
  > Legend:

  - [ ] To do task
  - [x] Done task
  - Posponed task
  - ~~Cancelled task~~ 

### Tasks

  - [x] Learn about *Hugo* & how to work with it
  - [x] Download & install things
  - [x] Choose a *Hugo* theme & clone it
  - [x] Build the website locally
  - [x] Create a new *GitHub* repository
  - [x] Upload files online thru *Git*
  - [x] Host the website on *Netlify*
  - [x] Read & learn the theme's documentation
  - [x] Deploy updated changes & configurations
  - [x] Publish new blog/s
  - [x] Publish an About page
<!-- TODO: End of to do list -->

***
