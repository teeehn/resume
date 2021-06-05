# Resume

This is Tom Nicolosi's Web Developer resume.

## Installation, Build, and Development

To install run:
```
npm install
```

To build for production run:
```
npm run build
```

This places production assets in the /dist/ folder and is configured
assuming that the file will be served from the /resume/ folder.

For development run:
```
npm run serve
```

This will open a browser window at https://localhost:9000.

## Technology Highlights

*   This page is statically rendered using [webpack version 5](https://webpack.js.org/).
*   Content is managed using:

    *  [markdown](https://daringfireball.net/projects/markdown/)
  
    *  The [Remark loader for Webpack](https://github.com/webpack-contrib/remark-loader)

*   Templating is accomplished using:
  
    *   An HTML template bundled with the [HTML Webpack Plugin](https://webpack.js.org/plugins/html-webpack-plugin/)

    *   [EJS](https://ejs.co/) templating.
  


