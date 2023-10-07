# neovim
**My neovim configuration**

# Leader: `<space>`
# Requirements:
* ripgrep: for search work to work
# Special keymap:
## Movement
* `<Tab>` to go to corresponding tag
## Misc
* `++` to toggle comment
* `<Ctrl-p>` to toggle file search
* `<Ctrl-b>` to toggle file tree, (press i to show hidden files)
* `<leader>sw` to search for word (node_modules is ignored)
* `<leader>oi` to organize import(only js,ts,jsx,ts files)
* `:Mason` to manage which language-server/linter/...
* `:ESLintFixAll` to format using eslint
* `:Telescope <command>` to use Telescope, eg: `:Telescope buffers`

## If `require` inside `use` doesnt work, try run `:PackerSync`
