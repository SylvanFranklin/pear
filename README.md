# pear.nvim
Easily switch file pairs for instance c++ and h++. 

This plugin is for demo purposes, if you actually want to switch between files use other.nvim. If you really like the pear logo then use this one idc.

<p align="center">
  <img src="pear.png" alt="Alt text" width="100"/>
</p>


## Install

```lua
return {
    "sylvanfranklin/pear",
    config = function()
        local pear = require("pear")
        vim.keymap.set("n", "<leader>b", function() pear.jump_pairs() end, { silent = true })
    end
}
```
