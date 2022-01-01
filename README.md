# PHP Enhanced Snippets - VScode extension

[![VScode](https://img.shields.io/badge/Extension-VScode-blueviolet.svg)](https://marketplace.visualstudio.com/items?itemName=aspirantzhang.php-enhanced-snippets)
![PHP8](https://img.shields.io/badge/PHP-%5E8.0-blue.svg)
[![PSR-2](https://img.shields.io/badge/Standard-PSR--2-%2326A69A.svg)](https://www.php-fig.org/psr/psr-2/)
[![PSR-12](https://img.shields.io/badge/Standard-PSR--12-%2326A69A.svg)](https://www.php-fig.org/psr/psr-12/)

**This [VScode extension](https://marketplace.visualstudio.com/items?itemName=aspirantzhang.php-enhanced-snippets) provides a complete set of code snippets for PHP developers.**

You can use it to avoid wasting time typing Class blocks, function signatures or other common PHP statements.

## Usage
It's a good practice to enter only the first two/three letters of each word. For example:

 - 'php class' = 
`ph cl` / `php cla`  **(no spaces when typing)**

- 'php class with implements' = 
`ph cl im` / `php cla imp`

## Snippets

### Shortcuts
| Snippet | Output | Language
| --- | --- | --- |
| pr | `print_r()` | php |
| vd | `var_dump()` | php |
| dirname-dir | `dirname(__DIR__)` | php |

### PHP Tag
| Snippet | Output | Language
| --- | --- | --- |
| php | `<?php ?>` | html |
| php-open | `<?php` | html |
| php-close | `?>` | html |
| php-page | `php page with strict type & namespace` | html |

### Branching
| Snippet | Output | Language
| --- | --- | --- |
| if-block | `if ($condition) {}` | php |
| if-else-block | `if ($condition) {} else {}` | php |
| if-return-block | `if ($condition) { return $foo; } return $bar;` | php |
| else-block | `else {}` | php |
| elseif-block | `elseif ($condition) {}` | php |
| switch-break | `switch(){ case: ... break; }` | php |
| switch-return | `switch(){ case: return ...; }` | php |
| if-three / ternary-operator | `(condition)?true:false;` | php |

### Loop
| Snippet | Output | Language
| --- | --- | --- |
| while-block | `while ($condition) {}` | php |
| do-while-block | `do {} while ($condition);` | php |
| for-i | `for ($i = 0; $i < $condition; $i++) {}` | php |
| for-j | `for ($j = 0; $j < $condition; $j++) {}` | php |
| foreach-block | `foreach ($array as $value) {}` | php |
| foreach-key-value | `foreach ($array as $key => $value) {}` | php |

### Functions
| Snippet | Output | Language
| --- | --- | --- |
| function | `function name($param) {}` | php |
| function-return | `function name($param): string {}` | php |
| function-anonymous | `function ($param) {}` | php |
| function-anonymous-return | `function ($param): string {}` | php |
| function-anonymous-use | `function ($param) use ($var) {}` | php |
| function-anonymous-use-return | `function ($param) use ($var): string {}` | php |
| arrow-function | `fn($foo) => $bar;` | php |
| arrow-function-return | `fn($foo): string => $bar;` | php |
| arrow-function-nested | `fn($foo) => fn($bar) => $baz;` | php |

### Methods
| Snippet | Output | Language
| --- | --- | --- |
| public-construct | `public function __construct()` | php |
| protected-construct | `protected function __construct()` | php |
| private-construct | `private function __construct()` | php |
| public-function | `public function` | php |
| protected-function | `protected function` | php |
| private-function | `private function` | php |
| public-function-return | `public function with return type` | php |
| protected-function-return | `protected function with return type` | php |
| private-function-return | `private function with return type` | php |
| public-static-function | `public static function` | php |
| protected-static-function | `protected static function` | php |
| private-static-function | `private static function` | php |
| public-static-function-return | `public static function with return type` | php |
| protected-static-function-return | `protected static function with return type` | php |
| private-static-function-return | `private static function with return type` | php |
| abstract-public-function | `abstract public function` | php |
| abstract-protected-function | `abstract protected function` | php |
| abstract-public-function-return | `abstract public function with return type` | php |
| abstract-protected-function-return | `abstract protected function with return type` | php |

### Class related
| Snippet | Output | Language
| --- | --- | --- |
| php-class | `php class` | html, php |
| php-class-no | `php class without strict type & namespace` | html |
| php-class-no-strict | `php class without strict type` | html |
| php-class-no-namespace | `php class without namespace` | html |
| php-class-extends | `php class with extends` | html, php |
| php-class-implements | `php class with implements` | html, php |
| php-abstract-class | `php abstract class` | html, php |
| php-abstract-class-no | `php abstract class without strict type & namespace` | html |
| php-abstract-class-no-strict | `php abstract class without strict type` | html |
| php-abstract-class-no-namespace | `php abstract class without namespace` | html |
| php-final-class | `php final class` | html, php |
| php-final-class-no | `php final class without strict type & namespace` | html |
| php-final-class-no-strict | `php final class without strict type` | html |
| php-final-class-no-namespace | `php final class without namespace` | html |
| php-final-class-extends | `php final class with extends` | html, php |
| php-final-class-implements | `php final class with implements` | html, php |
| php-interface | `php interface` | html, php |
| php-interface-no | `php interface without strict type & namespace` | html |
| php-interface-no-strict | `php interface without strict type` | html |
| php-interface-no-namespace | `php interface without namespace` | html |
| php-interface-extends | `php interface with extends` | html, php |
| php-trait | `php trait` | html, php |


### Error
| Snippet | Output | Language
| --- | --- | --- |
| thr | `throw new \Exception()` | php |
| try-catch | `try{} catch (){}` | php |
| try-catch-message | `try{} catch (Exception $e){ $e->getMessage() }` | php |
| try-catch-finally | `try{} catch (){} finally {}` | php |
| catch-block | `catch (){}` | php |
| finally-block | `finally {}` | php |

## Special Thanks
This extension is forked from [h4kst3r/php-awesome-snippets](https://github.com/h4kst3r/php-awesome-snippets). Because its author seems to have not maintained it for a long time. So I made this fork to make the extension suitable for new version of PHP. I reorganized the snippets and added more standardized writing. Great thanks to h4kst3r's excellent work.

The new version number starts from 2.x.

This work is inspired by PHPstorm (*PHP Live Templates*) and other works available on VScode marketplace like [PHP Snippets VS Code](https://github.com/heberalmeida/php-snippets) or [PHP Snippet Pack](https://github.com/jm-mwi/vscode-php-snippets/).

## License

[MIT](https://github.com/aspirantzhang/php-enhanced-snippets/blob/master/LICENSE) License
