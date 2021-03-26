## NeoVim Indent Guides

async render indent guides

## Usage

```lua
-- default options
indent_levels = 30;
indent_guide_size = 1;
indent_start_level = 1;
indent_enable = true;
indent_space_guides = true;
indent_tab_guides = false;
indent_soft_pattern = '\\s';
exclude_filetypes = {'help','dashboard','dashpreview','NvimTree','vista','sagahover'};
even_colors = { fg ='#2a3834',bg='#332b36' };
odd_colors = {fg='#332b36',bg='#2a3834'};

lua require('indent_guides').setup({
  -- put your options in here
})
```

## Acknowledgement

[nathanaelkane/vim-indent-guides](https://github.com/nathanaelkane/vim-indent-guides)
