<p align="center">
  <a href="https://docsify.js.org">
    <img alt="docsify" src="./docs/_media/icon.svg">
  </a>
</p>

<p align="center">
  A magical documentation site generator.
</p>


Web made with [Docsify documentation](https://docsify.js.org)


# Docsify documentation
## [Quick start](https://docsify.js.org/#/quickstart)
It is recommended to install docsify-cli globally, which helps initializing and previewing the website locally.
```sh
npm i docsify-cli -g
```

## Initialize
If you want to write the documentation in the ./docs subdirectory, you can use the init command.
```sh
docsify init ./docs
```

## Writing content

After the init is complete, you can see the file list in the ./docs subdirectory.

```sh
index.html as the entry file
README.md as the home page
.nojekyll prevents GitHub Pages from ignoring files that begin with an underscore
```

You can easily update the documentation in ./docs/README.md, of course you can add more pages.

## Preview your site
Run the local server with docsify serve. You can preview your site in your browser on http://localhost:3000.
```
docsify serve docs
```

> For more use cases of docsify-cli, head over to the docsify-cli documentation.


# Features
- No statically built html files
- Simple and lightweight
- Smart full-text search plugin
- Multiple themes
- Useful plugin API
- Compatible with IE11
- Experimental SSR support ([example](https://github.com/docsifyjs/docsify-ssr-demo))
- Support embedded files


# Links
- [`develop` branch preview](https://docsify-preview.vercel.app/)
- [Documentation](https://docsify.js.org)
- [CLI](https://github.com/docsifyjs/docsify-cli)
- CDN: [UNPKG](https://unpkg.com/docsify/) | [jsDelivr](https://cdn.jsdelivr.net/npm/docsify/) | [cdnjs](https://cdnjs.com/libraries/docsify)
- [Awesome docsify](https://github.com/docsifyjs/awesome-docsify)
- [Community chat](https://discord.gg/3NwKFyR)