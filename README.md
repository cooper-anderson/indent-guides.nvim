## NeoVim Indent Guides

rewrite [nathanaelkane/vim-indent-guides](https://github.com/nathanaelkane/vim-indent-guides)

using lua with support pretty indent mode  and rainbow indent mode

```lua
require('indent_guides').default_opts = {
    indent_levels = 30;
    indent_guide_size = 0;
    indent_start_level = 1;
    indent_space_guides = true;
    indent_tab_guides = true;
    indent_pretty_guides = false;
    indent_soft_pattern = '\\s';
    exclude_filetypes = {'help'}
}

require('indent_guides').indent_guides_enable()
```
