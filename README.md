# Ruby Syntax Highlighting for Visual Studio Code
Ruby, ERB and Gemfile Syntax Support.

This Extension allows for Ruby Syntax Support without needing to install language server, debugger etc.

Original Ruby and ERB Syntax Grammar extracted from [vscode-ruby](https://github.com/rubyide/vscode-ruby).

### Changes Differing from extracted syntaxes:
- Added Grammar for `Gemfile` following [bundler docs](https://bundler.io/man/gemfile.5.html).
- Added [Ternary](https://docs.ruby-lang.org/en/2.7.0/syntax/control_expressions_rdoc.html#label-Ternary+if) `:`.
- Added [Ruby Range](https://ruby-doc.org/core-2.7.1/Range.html).
- Fixed Comment Blocks for `.erb` files to allow for html block commenting `<!-- -->"` (still respects single line comments `<%# %>`).
- Fixed variable recognition ending with `?` or `!`

** Pull Requests submitted to [forked repository](https://github.com/rubyide/vscode-ruby/pulls) for `ruby` and `erb` grammar changes addressed in this repo. **

## Related Extension

[Rails Syntax Highlighting](https://github.com/smridge/vscode_rails_syntax)
