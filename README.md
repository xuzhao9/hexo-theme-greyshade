# Greyshade

Ported from Octopress Theme [Greyshade](https://github.com/shashankmehta/greyshade)
to [Hexo](https://github.com/tommy351/hexo).

[Demo](https://nuklly.github.io)

## Installation

Assuming that you have installed Hexo and using light theme.

    cd $hexo
    npm i hexo-theme-greyshade
    ln -s node_modules/hexo-theme-greyshade theme/

then change the value of `theme` field in your `_config.yml` to `greyshade`.

Do not forget:

    hexo generate
    hexo deploy

to see if it works. Enjoy it!

## Feature

- Responsive design.
- [Gravator](https://gravatar.com/) profile image support.
- [Addit](http://www.addthis.com/) sharing shortcut support.
- [Disqus](http://disqus.com/) comment support.
- [Mathjax](http://www.mathjax.org/) support.

## Changelog

### Version 0.0.2

- [Add Feature] Page index support
- [Removed Feature] Updated date removed
- [Removed Feature] Site title display

### Version 0.0.1

- Build basical functionalities
