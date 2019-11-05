# tumx 配置

## 使用方法
将tumx.conf放到~/.tumx.conf

## 快捷键
prefix已经从C-b更改为C-a
第二prefix为`

| 快捷键          | 功能              |
| --------------- | ----------------- |
| prefix c        | 创建新窗口        |
| prefix \        | 垂直窗格          |
| prefix -        | 水平窗格          |
| prefix <方向键> | 切换窗格          |
| prefix <num>    | 切换窗口          |
| prefix x        | 关闭窗格/窗口     |
| prefix d        | 解除会话          |
| prefix s        | 列出所有会话      |
| prefix z        | 当前窗格全屏/恢复 |

## 常用命令

- tmux ls 查看所有会话

- tmux a -t <session> 绑定会话

-   tmux kill-session -t <session-name>