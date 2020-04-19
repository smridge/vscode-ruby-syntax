# Ruby Syntax Highlighting for Visual Studio Code
Ruby, ERB and Gemfile Syntax Support.

Original Ruby and ERB Syntax Grammar fork from https://github.com/rubyide/vscode-ruby - a few changes made to fix quirks.

This Extension allows for ruby syntax support without needing to install language server, debugger etc.

## Features
- Ruby, ERB and Gemfile Syntax Support.

### Changes Differing from forked repo.
- Adds Grammar for `Gemfile` following [bundler docs](https://bundler.io/man/gemfile.5.html).
- Commenting out `.erb` files properly.
- Adding Ternary if.
- Adding Ruby Range
- Adding variables that end with `?` or `!`

** Pull Requests submitted to [forked repository](https://github.com/rubyide/vscode-ruby/pulls) for `ruby` and `erb` grammar changes addressed in this repo. **
