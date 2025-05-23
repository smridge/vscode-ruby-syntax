# CHANGELOG
## main (Unreleased)
- Fix range operator to support beginless and endless ranges
- Fix `erb` block comments to add `<%#` to each line
  ```erb
  <ul>
    <%# <% @foos.each do |foo| %>
    <%#   <li><%= foo %></li>
    <%# <% end %>
  </ul>
  ```

## 1.0.0 (2025-05-22)
- Update repository with a few changes mainly from `ruby-lsp` and `textmate`:
  - Fix class/module `::` namespacing separater
  - Fix backtick highlighting
  - Fix block parameter matching
  - Fix multiline arithmetic operations and regex string collisions

## 0.0.11 (2020-04-19)
- `README` Updates

## 0.0.1 (2020-04-19)
- Capture Ruby and ERB Syntaxes from https://github.com/rubyide/vscode-ruby
- Change ERB block comments to html style
- Make a few adjustments for ruby grammar
- Add Gemfile Grammar
