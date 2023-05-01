# Docsify documentation

## What it is
Docsify generates your documentation website on the fly. Unlike GitBook, it does not generate static html files. Instead, it smartly loads and parses your Markdown files and displays them as a website. To start using it, all you need to do is create an `index.html` and [deploy it on GitHub Pages](deploy.md).

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

Add markdown of docs to *_sidebar* 


## Preview your site
Run the local server with docsify serve. You can preview your site in your browser on http://localhost:3000.
```
docsify serve docs
```
> For more use cases of docsify-cli, head over to the docsify-cli documentation.

# Features
- No statically built html files
- Smart full-text search plugin
- Multiple themes
- Useful plugin API
- Support server-side rendering ([example](https://github.com/docsifyjs/docsify-ssr-demo))

## Examples
Check out the [Showcase](https://github.com/docsifyjs/awesome-docsify#showcase) to see docsify in use.
