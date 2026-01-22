# CHANGELOG
## main (Unreleased)
- Add keywords (`path`, `platforms`, `git`) and support method `install_if` to `Gemfile`


## 1.1.0 (2025-05-23)
- Fix range operator to support beginless and endless ranges
- Fix `erb` block comments to add `<%#` to each line
  ```erb
  <ul>
    <%# <% @foos.each do |foo| %>
    <%#   <li><%= foo %></li>
    <%# <% end %>
  </ul>
  ```
  - **Note**: Somewhat `BREAKING` across text editors as there does not seem to be a universally agreed upon approach for `.erb` block comments. This approach is the closest to making it work as expected. For `html` only lines, such as `<%# <ul>`, an `erb` commenting out does not _actually_ comment the line and a manual `<!-- <ul> -->` is needed. In its entirety the correct approach should have a combination like the below. However, there seems to be a VSCode limitation in not being able to add a combination approach for line commenting. 
    ```erb
    <!-- <ul>
      <%# <% @foos.each do |foo| %>
      <%#   <li><%= foo %></li>
      <%# <% end %>
    </ul> -->
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
