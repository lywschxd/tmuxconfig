# tumx 配置

## 使用方法
将tumx.conf放到~/.tumx.conf

## 快捷键
prefix已经从C-b更改为C-a
第二prefix为`

| 快捷键               | 功能                   |
| -------------------- | ---------------------- |
| prefix c             | 创建新窗口             |
| prefix \             | 垂直窗格               |
| prefix -             | 水平窗格               |
| prefix <方向键>      | 切换窗格               |
| prefix <num>         | 切换窗口               |
| prefix x             | 关闭窗格/窗口          |
| prefix d             | 解除会话               |
| prefix s             | 列出所有会话           |
| prefix z             | 当前窗格全屏/恢复      |
| prefix ctrl+<方向键> | 调整panel的大小        |
| prefix pgUp/pqDown   | 滚动，使用q退出        |
| prefix t             | 显示时间，就是一个屏保 |
| prefix [             | 复制模式               |

## 复制模式

需要把复制模式的键盘布局设置为vi

```
setw -g mode-keys vi
```

1. 通过`prefix [` 进入复制模式
2. 光标移动，或者通过`/` `?`进行搜索
3. 空格开始进行需要复制的选择
4. 回车进行复制并退出复制模式
5. `prefix ]`进行粘贴，不能复制到系统粘贴板



## 常用命令

- tmux ls 查看所有会话

- tmux a -t <session> 绑定会话

-   tmux kill-session -t <session-name>