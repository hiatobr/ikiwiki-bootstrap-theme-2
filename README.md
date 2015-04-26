ikiwiki-bootstrap-theme-2
=======================

Twitter bootstrap theme for ikiwiki version 2

Forked from https://github.com/ramseydsilva/ikiwiki-bootstrap-theme

(Tries to) use the last pre-compiled version of bootstrap from
 http://getbootstrap.com

What for?
-----

This is used on ikiwiki blogs hosted at https://ninguem.tem.blog.br

You should install CaCert's certificates to use SSL on that site, get it on
 <https://www.cacert.org/index.php?id=3>. If you don't want to, you should 
use this link: http://ninguem.tem.blog.br

Install
-----

You should NOT clone this into ikiwiki. Ikiwiki already is a git
 repository. And submodules won't work as expected.

You should copy the file local.css and folders bootstrap, templates to your
 ikiwiki directory. Then rebuild the wiki:

```
git clone https://github.com/hiatobr/ikiwiki-bootstrap-theme-2.git
cd ikiwiki-bootstrap-theme-2
rsync -r local.css bootstrap templates /path/to/ikiwiki/public_html/blog/
ikiwiki --refresh --wrappers --setup /path/to/ikiwiki/blog.setup
```

Licenses
-----

Original work from [ramseydsilva](https://github.com/ramseydsilva) has no 
LICENSE

[Hacklab Independência](https://hi.ato.br)'s fork is Kopimi

Bootstrap is MIT and Twitter's copyright

See the LICENSE file on this repository.

Bugs
-----

This is being translated to brazilian portuguese because it is used on the 
[Ninguém Tem Blog!](http://ninguem.tem.blog.br) project. Sorry about that.
