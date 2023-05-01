# How to create webs

This is a simple documentation page that shows you the basics of how webs work.

*Made with [docsify.js](https://github.com/docsifyjs/docsify) a magical documentation site generator.*

## Use of docsify

- With docsify package
```sh
# install docsify with npm (node package manager)
npm i docsify-cli -g

# initialize with docsify
docsify init ./docs

# serve with docsify by default in port 3000
docsify serve ./docs
```

- Manually
```sh
# create html
cat > index.html << EOF
<!DOCTYPE html>
<html>
  <head>
    <meta http-equiv="X-UA-Compatible" content="IE=edge,chrome=1" />
    <meta name="viewport" content="width=device-width,initial-scale=1" />
    <meta charset="UTF-8" />
    <link
      rel="stylesheet"
      href="//cdn.jsdelivr.net/npm/docsify@4/themes/vue.css"
    />
  </head>
  <body>
    <div id="app"></div>
    <script>
      window.$docsify = {
        //...
      };
    </script>
    <script src="//cdn.jsdelivr.net/npm/docsify@4"></script>
  </body>
</html>
EOF

# serve with python in port 3000
cd ./docs && python -m http.server 3000
```