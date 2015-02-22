ikiwiki-bootstrap-theme-2
=======================

Twitter bootstrap theme for ikiwiki version 2

Forked from https://github.com/ramseydsilva/ikiwiki-bootstrap-theme

Uses the last pre-compiled version of bootstrap from
 http://getbootstrap.com

What for?
-----

This is used on ikiwiki blogs hosted at https://ninguem.tem.blog.br

You should install CaCert's certificates to use SSL on that site, get it on
 https://www.cacert.org/index.php?id=3

Install
-----

You should NOT clone this into ikiwiki. Ikiwiki already is a git
 repository.

You should copy the file local.css and folders bootstrap and templates to
 your ikiwiki directory. Then rebuild the wiki:

```
git clone https://github.com/hiatobr/ikiwiki-bootstrap-theme-2.git
cd ikiwiki-bootstrap-theme-2
cp -r local.css bootstrap templates /path/to/ikiwiki/
ikiwiki -setup /path/to/config.setup
```

Licenses
-----

Original work from ramseydsilva has no LICENSE

hiatobr's fork is Kopimi

Bootstrap is MIT and Twitter's copyright
