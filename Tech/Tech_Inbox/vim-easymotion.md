---
tags:
  - Tech
  - neovim/plugin
aliases:
---
vimでの移動を便利にするplugin
文字を検索(1~2文字)してそこに高速で移動できる。

現在のキーマップはこんな感じ
f: 2文字検索(前後)
F: 1文字検索(前後)
```bash
vim.keymap.set("n", "f", "<Plug>(easymotion-overwin-f2)")
vim.keymap.set("n", "F", "<Plug>(easymotion-overwin-f)")
```


リポジトリ: [GitHub - easymotion/vim-easymotion: Vim motions on speed!](https://github.com/easymotion/vim-easymotion)