# Mac-Tools
玩转 Mac

玩转 Terminal
- 不要进入休眠状态
在终端中输入 `caffeinate`，取消的话可以输入 `control + C` 指令

- 重置程序坞与状态栏
将程序栏恢复为电脑刚刚激活时的状态，输入指令 `defaults delete com.apple.dock; killall Dock`

- 程序坞添加空白分解符
输入指令：`defaults write com.apple.dock persistent-apps -array-add '{"tile-type"="spacer-tile";}'; killall Dock`
如需删除，则直接拖拉删除即可
