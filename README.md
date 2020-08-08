![sheetloaf: Fresh-made stylesheets for the whole family.](https://i.imgur.com/BHHYDm9.png)

# Benefits

* No additional dependencies except for those required by sass and postcss
* More to come...

WARNING: This project is still early on and does not do much of anything. Check back later. 

## FAQ

> Can I use this with regular CSS files?

Yes, but you should use PostCSS-CLI in that case. This project is intended to simplify the two-step process of rendering Sass files and then transforming the output with PostCSS.

Likewise, if all you're looking for is to compile Sass, stick with Dart Sass.

```
Usage:
  sheetloaf [input.scss] [output.css] [OPTIONS]
  sheetloaf <input-directory> <output-directory> [OPTIONS]
  sheetloaf <input-glob-pattern> <output-directory> [OPTIONS] 

Sass Options:
  -w, --watch           Watch files for changes and recompile as needed       [boolean]
  -s, --style=<NAME>    Output style. [expanded (default), compressed]         [string]

PostCSS-CLI Options:
  -u, --use             List of postcss plugins to use (not functional)         [array]
```