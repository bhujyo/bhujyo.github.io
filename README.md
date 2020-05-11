# Dr. B's Portfolio and Physics Learning Resources

## Demo URL

[https://bbsite.netlify.app/](https://bbsite.netlify.app/)

## Features

- Clean and minimal design
- [Tailwind CSS v1](https://tailwindcss.com) (with PurgeCSS). Using [this gridsome plugin](https://gridsome.org/plugins/gridsome-plugin-tailwindcss) as it combines Tailwind and PurgeCSS.
- Scroll to sections using [vue-scrollto](https://github.com/rigor789/vue-scrollto)
- Blog with markdown content for posts
- Documentation type that shows how to use Vue components in Markdown (click Docs)
- Theme Switcher with Dark Mode
- Search posts with [Fuse.js](https://fusejs.io) and [vue-fuse](https://github.com/shayneo/vue-fuse)
- Tags for posts
- Basic pagination
- Syntax highlighting with [Shiki](https://shiki.matsu.io) (using [this gridsome plugin](https://gridsome.org/plugins/gridsome-plugin-remark-shiki))
- 404 Page
- RSS Feed
- Sitemap in XML

## Installation

1. Install Gridsome CLI tool if you don't have it: `npm install --global @gridsome/cli`
1. Clone the repo
1. `cd bbsite`
1. `yarn`
1. `gridsome develop` to start a local dev server at `http://localhost:8080`

## Notes

- Forked from the [personal portfolio website](https://andremadarang.com) of Andre Madarang.
- Illustrations from [unDraw](https://undraw.co)
- Search is based on [Fuse.js](https://fusejs.io) and [vue-fuse](https://github.com/shayneo/vue-fuse). It only searches the title and summary of posts for now. Some tweaking may be necessary to get it to search to your liking. Check out the fuse documentation for search settings. A `search.json` index file is generated at build time. This happens in `gridsome.server.js`.
- Check out these other Gridsome Starters where I got some ideas from:
  - [Gridsome Starter Blog](https://github.com/gridsome/gridsome-starter-blog)
  - [Gridsome Starter Bleda](https://github.com/cossssmin/gridsome-starter-bleda)
  - [Jigsaw Starter Blog](https://jigsaw.tighten.co/docs/starter-templates/) - I got a lot of design inspiration from this starter theme.
