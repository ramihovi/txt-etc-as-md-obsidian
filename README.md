# txt etc as md Obsidian plugin

Forked and modified for personal use from
[https://github.com/deathau/txt-as-md-obsidian/](https://github.com/deathau/txt-as-md-obsidian/).

A plugin for [Obsidian](https://obsidian.md) which allows editing and indexing
of text (.txt), VimOutliner (.otl) and R Markdown (.Rmd) files as if they were
markdown, and also includes alternative markdown suffix .markdown.

### Compatibility

The required APIs were only added in Obsidian **0.10.12**, and as such, that is the minimum version of Obsidian required to use this plugin. 

## Security

> Third-party plugins can access files on your computer, connect to the internet, and even install additional programs.

The source code of this plugin is available on GitHub for you to audit yourself, but installing plugins into Obsidian is currently a matter of trust.

I can assure you here that I do nothing to collect your data, send information to the internet or otherwise do anything nefarious with your system. However, be aware that I *could*, and you only have my word that I don't.

## Installation and development

This project uses Typescript to provide type checking and documentation.  
The repo depends on the latest [plugin API](https://github.com/obsidianmd/obsidian-api) in Typescript Definition format, which contains TSDoc comments describing what it does.

**Note:** The Obsidian API is still in early alpha and is subject to change at any time!

If you want to contribute to development and/or just customize it with your own
tweaks, you can do the following:

- Clone this repo.
- `npm i` or `yarn` to install dependencies.
- `npm run build` to compile.
- Copy `manifest.json`, `main.js` and `styles.css` to a subfolder of your plugins
folder (e.g, `<vault>/.obsidian/plugins/<plugin-name>/`)
- Reload Obsidian.
- Go to the community plugins window and activate the newly installed plugin.

Alternately, you can clone the repo directly into your plugins folder and once
dependencies are installed use `npm run dev` to start compilation in watch mode.  
You may have to reload obsidian (`ctrl+R`) to see changes.

