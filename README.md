# Wordpress Core Styles

This repo will be used to import the core styles for wordpress wysiwyg content.

## Installation

Run `npm install 1minus1limited/wordpress-core.git --save`

-or-

Add to the dependencies in your `package.json`
```
"dependencies": {
  "wordpress-core": "github:1minus1limited/wordpress-core",
  ...
},
```

The run `npm install`


## Using it in projects

If using in a brunch project, you need to have `postcss` installed as well as
the `postcss-import`, as this will search for the file in the `node_modules`
directory.

Then you can use it in projects by importing the CSS
```
@import 'wordpress-core/wordpress-core.css';
```

Otherwise use whichever method is suggested by your task runner/builder to
handle the use of npm module files
