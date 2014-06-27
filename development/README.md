# [WPCollab](https://github.com/WPCollab/WPCollab) > Development

## Coding Standards
- [WordPress Coding Standards](http://codex.wordpress.org/WordPress_Coding_Standards)
	- [PHP Coding Standards](http://make.wordpress.org/core/handbook/coding-standards/php/)
	- [HTML Coding Standards](http://make.wordpress.org/core/handbook/coding-standards/html/)
	- [CSS Coding Standards](http://make.wordpress.org/core/handbook/coding-standards/css/)
	- [JavaScript Coding Standards](http://make.wordpress.org/core/handbook/coding-standards/javascript/)
- [WordPress Coding Standards for PHP_CodeSniffer](https://github.com/WordPress-Coding-Standards/WordPress-Coding-Standards)
- [WPCollab Coding Standards](https://github.com/WPCollab/WPCollab/blob/master/development/code-standards_WPCollab.md)

## GitHub

### Build Testing

#### __Continuous Inspection:__ [Scrutinizer](https://scrutinizer-ci.com/)
- [WPCollab Scrutinizer Build Configs](https://github.com/WPCollab/WPCollab/blob/master/development/Scrutinizer/Scrutinizer_build-config.md)
- Tip & Tricks
	- Suppress analysis on a per-commit basis:
		- prefix the commit message with `[skip ci]`, `[ci skip]` or `[skip Scrutinizer]`
- Scrutinizer sample profiles:
	- [WPCollab WordPress plugin profile](https://github.com/WPCollab/WPCollab/blob/master/development/Scrutinizer/WPCollab_WP-plugin.scrutinizer.yml)

####__Continuous Integration:__ [Travis CI](https://travis-ci.org/)
- Travis CI sample profiles:
	- @todo
- Tip & Tricks
	- Skip build test on a per-commit basis:
		- add `[skip ci]` or `[ci skip]` to your commit message
