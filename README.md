# eunos-1128.github.io

[![Deploy](https://img.shields.io/badge/deployed-GitHub%20Pages-blue?logo=github)](https://eunos-1128.github.io/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](./LICENSE.txt)

Personal homepage of **UENO, M.** — a research engineer studying bioinformatics and cheminformatics.

Live site: <https://eunos-1128.github.io/>

## About

A single-page portfolio site introducing my expertise, skills, and featured projects.
It is built with [Jekyll](https://jekyllrb.com) and based on the
[Particle](https://github.com/nrandecker/particle) theme, with the following stack:

- Jekyll (static site generation)
- SASS (styles)
- gulp (asset build)
- particles.js (animated background)
- Sweet Scroll (smooth scrolling)
- Font Awesome & Devicon (icons, loaded via CDN)

## Local Development

Compile the assets and run Jekyll locally:

- Install [Node.js](https://nodejs.org/)
- Install [Jekyll](https://jekyllrb.com): `gem install bundler jekyll`
- Install [Yarn](https://yarnpkg.com/): `npm install -g yarn`
- Install dependencies: `yarn`
- Build assets: `gulp`
- Serve the site: `jekyll serve`

## Configuration

Site and user information is defined in `_config.yml` (title, description, username,
user description, social usernames, etc.). Page content lives in `_includes/`
(`about.html`, `projects.html`, `header.html`, ...).

## Credits

Based on the [Particle](https://github.com/nrandecker/particle) Jekyll theme by
Nathan Randecker, which in turn drew inspiration from:

- [Willian Justen](https://github.com/willianjusten/will-jekyll-template)
- [Vincent Garreau](https://github.com/VincentGarreau/particles.js/)

## License

This project is distributed under the [MIT License](./LICENSE.txt).
