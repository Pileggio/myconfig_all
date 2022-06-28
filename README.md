# myconfig_all

### 配置nvim
#### 依赖
* 首先要安装neovim
```
brew install neovim
```
* 因为一些插件配置使用lua编写的，所以也需要安装lua
```
brew install lua
```
* 最后是vim-plug，这是vim插件管理器。
‘’‘
https://github.com/junegunn/vim-plug
’‘’

#### 文件替换
* clone两个文件夹到本地
* `nvim`文件替换本地的`~/.config/nvim`的内容
 ```
 cp -aR [path]/nvim/* ～/.config/nvim
 ```
* 同理，plugged替换本地的`~/.vim/plugged`的内容，如果没有则直接放到`.vim/`目录下
 ```
 cp -aR [path]/plugged/* ~/.vim/plugged
