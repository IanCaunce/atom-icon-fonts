# Icon Fonts for Atom

[![The MIT License](https://img.shields.io/badge/license-MIT-orange.svg?style=flat-square)](http://opensource.org/licenses/MIT)
[![apm](https://img.shields.io/apm/v/icon-fonts.svg?style=flat-square)](https://atom.io/packages/icon-fonts)
[![apm](https://img.shields.io/apm/dm/icon-fonts.svg?style=flat-square)](https://atom.io/packages/icon-fonts)
[![Travis](https://img.shields.io/travis/idleberg/atom-icon-fonts.svg?style=flat-square)](https://travis-ci.org/idleberg/atom-icon-fonts)
[![David](https://img.shields.io/david/dev/idleberg/atom-icon-fonts.svg?style=flat-square)](https://david-dm.org/idleberg/atom-icon-fonts#info=devDependencies)

Atom snippets for a variety of icon fonts ([see details](#prefixes)).

Converted from the [package](https://github.com/idleberg/Icon-Fonts-Sublime-Text) for Sublime Text.

## Installation

### apm

* Install package `apm install icon-fonts` (or use the GUI)

### GitHub

1. Change directory to `~/.atom/packages/`
2. Clone repository `git clone https://github.com/idleberg/atom-icon-fonts.git`

## Usage

Snippets are limited to the `.text.html` scope. Typing the class name of an icon using the designated prefix will complete to a tag containing the icon class. Exceptions are `fa-stack` (`<span>`) and `fa-ul` (`<ul>`).

### Prefixes

Prefix         | Icon Font | Version
---------------|-----------|--------
`ai`           | [Android Icons](http://www.androidicons.com/) | 1.0.0
`brandico`     | [Brandico Font](https://github.com/fontello/brandico.font) | –
`cc`           | [Creative Commons Icon Font](http://cc-icons.github.io/) | 1.2.1
`el-icon`      | [Elusive Icons](http://shoestrap.org/downloads/elusive-icons-webfont/) | ?
`fa`           | [Font Awesome](http://fontawesome.io/) | 4.4.0
`fi`           | [Foundation Icons](http://zurb.com/playground/foundation-icons) | 3.0
`filetypes`    | [Glyphicons Filetypes](http://glyphicons.com/) | 1.9.0
`foundico`     | [Foundation Icons](https://github.com/zurb/foundation-icons/tree/original-implementation) | 1.0
`glyphicons`   | [Glyphicons Pro](http://glyphicons.com/)* | 1.9.0
`halflings`    | [Glyphicons Halflings](http://glyphicons.com/) | 1.9.0
`line`         | [Elegant Theme Line Icons](http://www.elegantthemes.com/blog/resources/how-to-use-and-embed-an-icon-font-on-your-website) | –
`mfg`          | [MFG Labs Iconset](http://mfglabs.github.io/mfglabs-iconset/) | –
`octicon`      | [GitHub Octicons](https://octicons.github.com/) | 2.4.1
`oi`           | [Open Iconic](https://useiconic.com/open/) | 1.1.0
`openwebicons` | [OpenWeb Icons](http://pfefferle.github.io/openwebicons/) | 1.3.2
`pf`           | [PaymentFont](http://paymentfont.io/) | 1.1.2 
`ratchicon`    | [Ratchicons](http://goratchet.com/components/#ratchicons) | 2.0.2
`social`       | [Glyphicons Social](http://glyphicons.com/) | 1.9.0
`st`           | [Stack Icons](http://stackicons.com/) | 1.0.0
`typicon`      | [Typicons](http://typicons.com/) | 2.0.7
`ui`           | [Semantic UI Icons](http://semantic-ui.com/elements/icon.html) | 2.0.7

\* Vanilla Glyphicons and Bootstrap Glyphicons use different class-names, the former adding a plural-s to its classes. On completion, a tab-stop is added to support both options. Future versions will deprecate this distinction, since [Bootstrap 4](http://blog.getbootstrap.com/2015/08/19/bootstrap-4-alpha/) is likely to ship without (glyph)icons.

Examples:

* `fa-check`+`Tab` completes to `<i class="fa fa-check"></i>`
* `glyphicons-check`+`Tab` completes to `<span class="glyphicons glyphicons-check"></span>`
* `octicon-check`+`Tab` completes to `<span class="octicon octicon-check"></span>`
* well, you get the idea

## License

This work is licensed under the [The MIT License](LICENSE.md).

## Donate

You are welcome support this project using [Flattr](https://flattr.com/submit/auto?user_id=idleberg&url=https://github.com/idleberg/atom-icon-fonts) or Bitcoin `17CXJuPsmhuTzFV2k4RKYwpEHVjskJktRd`
