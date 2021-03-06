# Sass Foundation Boilerplate

This is a sample project using the [7-1 architecture pattern](http://sass-guidelin.es/#architecture) and sticking to [Sass Guidelines](http://sass-guidelin.es) writing conventions using the [foundation framework](http://foundation.zurb.com/sites/docs/) 
this version built on the [Foundation Framework 6 forked here](https://github.com/abdulhamid-alattar/foundation-sites-template)

Each folder of this project has its own `README.md` file to explain the purpose and add extra information. Be sure to browse the repository to see how it works.

## Using the indented syntax

This boilerplate does not provide a `.sass` version as it would be painful to maintain both versions without an appropriate build process. However, it is very easy to convert this boilerplate to Sass indented syntax.

Clone it, head into the project and then run:

```
sass-convert -F sass -T scss -i -R ./ && find . -iname "*.sass" -exec bash -c 'mv "$0" "${0%\.sass}.scss"' {} \;
```


[![Bitdeli Badge](https://d2weczhvl823v0.cloudfront.net/abdulhamid-alattar/sass-foundation-boilerplate/trend.png)](https://bitdeli.com/free "Bitdeli Badge")

