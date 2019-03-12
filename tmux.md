# tmux 常用指令

# 如何創建session?
- tmux new -s [session_name]

# 如何列出所有session?
- tmux ls

# 如何暫時退出session?
1. tmux detach
2. ctrl +b d
# 如何退出session?
- ctrl + d

# 如何創建windows?
- ctrl + b c

# 如何刪除window?
- ctrl +d

# 如何切換windows?
- 右一個：ctrl +b +n
- 左一個：ctrl +b +p
# 如何分割panes?
- 左右切割：ctrl +b (shift)%
- 上下切割：ctrl + b (shift)”

# 如何刪除panes?
- ctrl + b +x ->y
- ctrl + d

# 如何移動到其他的panes?
- ctrl +b o 或上下左右

