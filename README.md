# Ruby Syntax Highlighting for Visual Studio Code
[![Published Version to VS Code](https://img.shields.io/visual-studio-marketplace/v/SarahRidge.vscode-ruby-syntax)](https://marketplace.visualstudio.com/items?itemName=SarahRidge.vscode-ruby-syntax)
[![VS Code Downloads](https://img.shields.io/visual-studio-marketplace/d/SarahRidge.vscode-ruby-syntax)](https://marketplace.visualstudio.com/items?itemName=SarahRidge.vscode-ruby-syntax)
[![VS Code Installs](https://img.shields.io/visual-studio-marketplace/i/SarahRidge.vscode-ruby-syntax)](https://marketplace.visualstudio.com/items?itemName=SarahRidge.vscode-ruby-syntax)
[![GitHub License](https://img.shields.io/github/license/smridge/vscode-ruby-syntax.svg)](https://github.com/smridge/vscode-ruby-syntax/blob/master/LICENSE)

Ruby, ERB and Gemfile Syntax Support.

This Extension allows for Ruby Syntax Support without needing to install language server, debugger etc.

Original Ruby and ERB Syntax Grammar forked from [vscode-ruby](https://github.com/rubyide/vscode-ruby).

## Install
- Run: `code --install-extension SarahRidge.vscode-ruby-syntax`
  - Alternatively, extension can be installed via [marketplace](https://marketplace.visualstudio.com/items?itemName=SarahRidge.vscode-ruby-syntax)
- Reload VSCode

### Changes differing from forked syntaxes:
- Added Grammar for `Gemfile` following [bundler docs](https://bundler.io/man/gemfile.5.html)
- Added [Ternary](https://docs.ruby-lang.org/en/2.7.0/syntax/control_expressions_rdoc.html#label-Ternary+if) `:`
- Added [Ruby Range](https://ruby-doc.org/core-2.7.1/Range.html)
- Fixed Comment Blocks for `.erb` files to allow for html block commenting `<!-- -->"` (still respects single line comments `<%# %>`)
- Fixed variable recognition ending with `?` or `!`

** Pull Requests submitted to [forked repository](https://github.com/rubyide/vscode-ruby/pulls) for `ruby` and `erb` grammar changes addressed in this repo. **

## References
- [Syntax Highlight Guide](https://code.visualstudio.com/api/language-extensions/syntax-highlight-guide)
- [Language Grammar Rules](https://macromates.com/manual/en/language_grammars)

## Related Extension
- [Rails Syntax Highlighting](https://github.com/smridge/vscode_rails_syntax)

## Publish (internal)
> Note: Publishing a new version of this theme is only meant for maintainers.
- `yarn run vs-package`
- `yarn run vs-publish`

---

Ruby <img src="https://raw.githubusercontent.com/smridge/vscode-ruby-syntax/master/images/icon.png" width="12"> Logo &copy; 2006, Yukihiro Matsumoto: https://www.ruby-lang.org/en/about/logo/
