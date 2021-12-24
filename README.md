# PHP Enhanced Snippets - VScode extension

[![VScode](https://img.shields.io/badge/Extension-VScode-blueviolet.svg)](https://marketplace.visualstudio.com/items?itemName=aspirantzhang.php-enhanced-snippets)
![PHP8](https://img.shields.io/badge/PHP-%5E8.0-blue.svg)
[![PSR-2](https://img.shields.io/badge/Standard-PSR--2-%2326A69A.svg)](https://www.php-fig.org/psr/psr-2/)
[![PSR-12](https://img.shields.io/badge/Standard-PSR--12-%2326A69A.svg)](https://www.php-fig.org/psr/psr-12/)

**This [VScode extension](https://marketplace.visualstudio.com/items?itemName=aspirantzhang.php-enhanced-snippets) provides a complete set of code snippets for PHP developers.**

You can use it to avoid wasting time typing Class blocks, function signatures or other common PHP statements.

## Usage
Maybe it's a good practice to use only the first three letters of each word.
For example, when I want 'php class with implements', then just type:
`php cla imp` (no spaces when typing)

## Snippets

### Class related
| Snippet | Output | Language
| --- | --- | --- |
| php-class | `standard php class` | html, php |
| php-class-no | `php class without strict type and namespace` | html |
| php-class-no-strict | `php class without strict type` | html |
| php-class-no-namespace | `php class without namespace` | html |
| php-class-extends | `php class with extends` | html, php |
| php-class-implements | `php class with implements` | html, php |

## Special Thanks
This extension is forked from [h4kst3r/php-awesome-snippets](https://github.com/h4kst3r/php-awesome-snippets). Because its author seems to have not maintained it for a long time. So I made this fork to make the extension suitable for new version of PHP. I re-planned the shortcut keys, and add more standardized writing methods. Great thanks to h4kst3r's excellent work.

The new version number starts from 2.x.

This work is inspired by PHPstorm (*PHP Live Templates*) and other works available on VScode marketplace like [PHP Snippets VS Code](https://github.com/heberalmeida/php-snippets) or [PHP Snippet Pack](https://github.com/jm-mwi/vscode-php-snippets/).

## License

[MIT](https://github.com/aspirantzhang/php-enhanced-snippets/blob/master/LICENSE) License
