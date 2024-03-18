# Astronvim user configuration example

A user configuration template for [AstroNvim](https://github.com/astronvim/astronvim)

## 💩 Words by Author (Rozenthegoat)

Currently is my own configuration. My manipulations are basically follow thise Bilibili tutorials: [【AstroNvim】第二期：配置LSP】](https://www.bilibili.com/video/BV1b6421g7ie/?share_source=copy_web&vd_source=2f7d54f6d49d848e1876f20b78edc9fe) (explanation in Mandarin).

Here are the modification details (Latest update: March 18, 2024):

+ [init.lua](https://github.com/rozenthegoat/rozen-astrovim/blob/main/init.lua): modify colorscheme to my favorate [dracula-nvim](https://github.com/astronvim/astrocommunity/tree/main/lua/astrocommunity/colorscheme/dracula-nvim)!
+ [plugins/community.lua](https://github.com/rozenthegoat/rozen-astrovim/blob/main/plugins/community.lua): import anything you like from the list of [astronvim community repository](https://github.com/astronvim/astrocommunity).
+ [plugins/null-ls.lua](https://github.com/rozenthegoat/rozen-astrovim/blob/main/plugins/null-ls.lua): i use the python formatter [black](https://github.com/averms/black-nvim) (not sure whether it is the correct one, just for demonstration), installing by `:Mason`, and uncomment the `null_ls.builtins.formatting.<your_formatter>`, and change the default formatter from `stylua` to `black`.



## 🛠️ Installation

#### Make a backup of your current nvim and shared folder

```shell
mv ~/.config/nvim ~/.config/nvim.bak
mv ~/.local/share/nvim ~/.local/share/nvim.bak
```

#### Clone AstroNvim

```shell
git clone https://github.com/AstroNvim/AstroNvim ~/.config/nvim
```

#### Create a new user repository from this template

Press the "Use this template" button above to create a new repository to store your user configuration.

You can also just clone this repository directly if you do not want to track your user configuration in GitHub.

#### Clone the repository

```shell
git clone https://github.com/<your_user>/<your_repository> ~/.config/nvim/lua/user
```

#### Start Neovim

```shell
nvim
```
