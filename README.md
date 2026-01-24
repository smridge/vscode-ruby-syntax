# Ruby Syntax Highlighting for Visual Studio Code
[![Published Version to VS Code](https://img.shields.io/vscode-marketplace/v/SarahRidge.vscode-ruby-syntax)](https://marketplace.visualstudio.com/items?itemName=SarahRidge.vscode-ruby-syntax)
[![VS Code Downloads](https://img.shields.io/vscode-marketplace/d/SarahRidge.vscode-ruby-syntax)](https://marketplace.visualstudio.com/items?itemName=SarahRidge.vscode-ruby-syntax)
[![Open VSX Version](https://img.shields.io/open-vsx/v/sarahridge/vscode-ruby-syntax)](https://open-vsx.org/extension/SarahRidge/vscode-ruby-syntax)
[![Open VSX Downloads](https://img.shields.io/open-vsx/dt/sarahridge/vscode-ruby-syntax)](https://open-vsx.org/extension/SarahRidge/vscode-ruby-syntax)
[![GitHub License](https://img.shields.io/badge/license-MIT-gray?color=green)](https://github.com/smridge/vscode-ruby-syntax/blob/main/LICENSE)

Ruby, ERB and Gemfile Syntax Support.

This Extension allows for Ruby Syntax Support without needing to install language server, debugger etc. for a way to keep things simple and distraction free.

## Install
This extension is available at the following extension marketplaces:
- [Visual Studio Code Marketplace](https://marketplace.visualstudio.com/items?itemName=SarahRidge.vscode-ruby-syntax)
- [Open VSX Registry](https://open-vsx.org/extension/SarahRidge/vscode-ruby-syntax)

Run one of the following commands depending on the editor you are using:
- For `vscode`: `code --install-extension SarahRidge.vscode-ruby-syntax`
- For `cursor`: `cursor --install-extension SarahRidge.vscode-ruby-syntax`

Reload your editor

## Notes
- The initial language grammar was copied from [`vscode-ruby`](https://github.com/rubyide/vscode-ruby) which is no longer supported
- [`ruby-lsp`](https://github.com/Shopify/ruby-lsp) as the successor now maintains ruby grammars

### Diffs
- Added Grammar for `Gemfile` following [bundler docs](https://bundler.io/man/gemfile.5.html)
- Added Ternary `:`
- Added Ruby Ranges `..` / `...`
- Fixed variable recognition ending with `?` or `!`
- Fixed Comment Blocks for `.erb` files by adding `<%#` to each line
- Fixed multiline arithmetic operations and regex matching collisions

## References
- [Syntax Highlight Guide](https://code.visualstudio.com/api/language-extensions/syntax-highlight-guide)
- [Language Grammar Rules](https://macromates.com/manual/en/language_grammars)

## Related Extension
- [Rails Syntax Highlighting](https://github.com/smridge/vscode_rails_syntax)

## Publish (internal)
> Note: Publishing a new version of this theme is only meant for maintainers.
- `yarn run vs-package`
- Publish to VSCode Marketplace: `yarn run vs-publish`
- Publish to Open VSX Registry: `npx ovsx publish <.vsix file> -p <OpenVSX PAT>`

---

Ruby <img src="https://raw.githubusercontent.com/smridge/vscode-ruby-syntax/main/images/icon.png" width="12"> Logo &copy; 2006, Yukihiro Matsumoto: https://www.ruby-lang.org/en/about/logo/
