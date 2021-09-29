# Agency Theme for Pelican

[Agency](http://startbootstrap.com/template-overviews/agency/) is a one page agency portfolio theme for [Bootstrap](http://getbootstrap.com/) created by [Start Bootstrap](http://startbootstrap.com/). This theme features several content sections, a responsive portfolio grid with hover effects, full page portfolio item modals, a responsive timeline, and a working PHP contact form.

This version of Agency theme was ported to be usable by [Pelican](https://blog.getpelican.com/), the static site generator powered by [python](https://www.python.org/).

It has also been modified in order to get a good score on several analyze tools such as:

* [Google Lighthouse](https://developers.google.com/web/tools/lighthouse)
* [Yellow Lab Tools](https://yellowlab.tools/)
* [WebPageTest](https://www.webpagetest.org/)
* [Pingdom Tools](https://tools.pingdom.com/)
* [Ecometer](http://www.ecometer.org/)
* [W3C Markup Validation Service](https://validator.w3.org/)

So, some modifications was made to remove external files (fonts, CSS, JS) to reduce DNS resolution and make it more portable, compress images (use [webassets](https://pypi.org/project/webassets/)), and remove unused CSS and JS (planned).

## Features

* ✅ A++ score on all tools listed above
* ✅ images optimization (WebP)
* ✅ static ressources minified (CSS and JS)
* ✅ no render blocking ressources
* ✅ all ressources are embeded with this template: number of DNS request reduced to the minimum, and no tracking via CDN.
* ⏳ images lazy-loading
* ⏳ contact form send mail using PHP
* ❌ nice Google fonts

## Getting started

``` bash
# TODO add clear configuration example
```

## Changelog / todolist

* [x] up to date (Start Bootstrap Agency v7.0.7, Bootstrap v5.1.1)
* [x] add `author` and `description` in html meta tags
* [x] remove external fonts
* [x] remove external icons (fontawesome) and embed it in template
* [x] manually minified JS and CSS files
* [ ] images lazy-loading
* [ ] embed the google fonts in template to recover nice fonts style
* [ ] verify the PHP contact form

## to use for later (move it in getting started section)

Additional configurable options in pelicanconf.py:  

SITETITLE (_also used in menu navigation_)  
SITESUBTITLE  
INTRO\_LG (_top line of landing page_)  
INTRO\_SM (_second line of landing page_)  
PORTFOLIO\_TITLE  
PORTFOLIO\_SUBTITLE

The `contents` folder contains portfolio, team, about and 'client logos' images (*see [sample_content](/sample_content) folder*).  
Each section (services, about, team, contact, clients' aside, etc) is a seperate include of the index template, making it easy to customize the order -- or removal -- of any section.

## Bugs and Issues

Want another functionnality or have an issue with this template? Open a new issue here on GitHub or send me a message.

## Creators

Start Bootstrap was created by and is maintained by **[David Miller](http://davidmiller.io/)**, Owner of [Blackrock Digital](http://blackrockdigital.io/).

* https://twitter.com/davidmillerskt
* https://github.com/davidtmiller

Start Bootstrap is based on the [Bootstrap](http://getbootstrap.com/) framework created by [Mark Otto](https://twitter.com/mdo) and [Jacob Thorton](https://twitter.com/fat).

## Copyright and License

The Agency theme code is released under the [MIT](https://github.com/BlackrockDigital/startbootstrap-agency/blob/master/LICENSE) license.

This port us also released under the [MIT](https://github.com/yaap7/Pelican-StartBootstrap-Agency/blob/master/LICENSE) license.
