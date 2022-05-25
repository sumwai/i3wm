# i3wm

This is my i3wm configure.

## clone

```bash
git clone https://github.com/sumwai/i3wm ~/.config/i3
```

## restart

```bash
i3 restart
```

## Usage

### Variables

### Startup 

### Key Binding

#### default mode

> settings 

| Key | Command | Comment |
| --- | ------- | ------- |
| `mod`+`q` | kill | 结束进程 |
| `mod`+`f` | fullscreen toggle | 切换全屏 |
| `mod`+`Shift`+`f` | floating toggle | 切换浮动 |
| `Print` | flameshot gui | 打开flameshot截图 |

> software 

| Key | Command | Comment |
| --- | ------- | ------- |
| `mod`+`d` | sh ~/.config/polybar/forest/scripts/launcher.sh | 打开启动菜单 |
| `mod`+`Shift`+`e` | sh ~/.config/polybar/forest/scripts/powermenu.sh | 打开电源菜单 |
| `mod`+`Return` | alacritty --config-file=$HOME/.config/alacritty/alacritty.yml | 打开alacritty终端 |


> change window layout

| Key | Command | Comment |
| --- | ------- | ------- |
| `mod`+`s` | layout stacking     | 使用覆盖布局 |
| `mod`+`w` | layout tabbed       | 使用tab布局  |
| `mod`+`e` | layout toggle split | 使用分割布局 |

> i3wm

| Key | Command | Comment |
| --- | ------- | ------- |
| `mod`+`Shift`+`r` | restart     | 重启i3wm |





> focus [use hjkl]

| Key | Command | Comment |
| --- | ------- | ------- |
| `mod`+`h` | focus left  | 将焦点移动到左边的窗口 |
| `mod`+`j` | focus down  | 将焦点移动到下边的窗口 |
| `mod`+`k` | focus up    | 将焦点移动到上边的窗口 |
| `mod`+`l` | focus right | 将焦点移动到右边的窗口 |

> focus [use arrow key]

| key | command | comment |
| --- | ------- | ------- |
| `mod`+`left`  | focus left  | 将焦点移动到左边的窗口 |
| `mod`+`down`  | focus down  | 将焦点移动到下边的窗口 |
| `mod`+`up`    | focus up    | 将焦点移动到上边的窗口 |
| `mod`+`right` | focus right | 将焦点移动到右边的窗口 |

> move window [use hjkl]

| key | command | comment |
| --- | ------- | ------- |
| `mod`+`Shift`+`h` | move left  | 将窗口移动到左边 |
| `mod`+`Shift`+`j` | move down  | 将窗口移动到下边 |
| `mod`+`Shift`+`k` | move up    | 将窗口移动到上边 |
| `mod`+`Shift`+`l` | move right | 将窗口移动到右边 |

> move window [use arrow key]

| key | command | comment |
| --- | ------- | ------- |
| `mod`+`Shift`+`left`  | move left  | 将窗口移动到左边 |
| `mod`+`Shift`+`down`  | move down  | 将窗口移动到下边 |
| `mod`+`Shift`+`up`    | move up    | 将窗口移动到上边 |
| `mod`+`Shift`+`right` | move right | 将窗口移动到右边 |

> change workspace

| key | command | comment |
| --- | ------- | ------- |
| `mod`+`1`  | workspace number 1   | 切换到工作区1  |
| `mod`+`2`  | workspace number 2   | 切换到工作区2  |
| `mod`+`3`  | workspace number 3   | 切换到工作区3  |
| `mod`+`4`  | workspace number 4   | 切换到工作区4  |
| `mod`+`5`  | workspace number 5   | 切换到工作区5  |
| `mod`+`6`  | workspace number 6   | 切换到工作区6  |
| `mod`+`7`  | workspace number 7   | 切换到工作区7  |
| `mod`+`8`  | workspace number 8   | 切换到工作区8  |
| `mod`+`9`  | workspace number 9   | 切换到工作区9  |
| `mod`+`0`  | workspace number 10  | 切换到工作区10 |

> move window to workspace

| key | command | comment |
| --- | ------- | ------- |
| `mod`+`Shift`+`1`  | move container to workspace number 1   | 移动窗口到工作区1  |
| `mod`+`Shift`+`2`  | move container to workspace number 2   | 移动窗口到工作区2  |
| `mod`+`Shift`+`3`  | move container to workspace number 3   | 移动窗口到工作区3  |
| `mod`+`Shift`+`4`  | move container to workspace number 4   | 移动窗口到工作区4  |
| `mod`+`Shift`+`5`  | move container to workspace number 5   | 移动窗口到工作区5  |
| `mod`+`Shift`+`6`  | move container to workspace number 6   | 移动窗口到工作区6  |
| `mod`+`Shift`+`7`  | move container to workspace number 7   | 移动窗口到工作区7  |
| `mod`+`Shift`+`8`  | move container to workspace number 8   | 移动窗口到工作区8  |
| `mod`+`Shift`+`9`  | move container to workspace number 9   | 移动窗口到工作区9  |
| `mod`+`Shift`+`0`  | move container to workspace number 10  | 移动窗口到工作区10 |


#### resize mode

> change to resize mode

| key | command | comment |
| --- | ------- | ------- |
| `mod`+`r`  | mode "resize" | 切换到"resize"模式 |

> change window size

| key | command | comment |
| --- | ------- | ------- |
| `Left`  | resize shink width 10 px or 10 pt  | 窗口横向变小 |
| `Right` | resize grow width 10 px or 10 pt   | 窗口横向变大 |
| `Up`    | resize shink height 10 px or 10 pt | 窗口纵向变小 |
| `Down`  | resize grow height 10 px or 10 pt  | 窗口纵向变大 |

> quit resize mode

| key | command | comment |
| --- | ------- | ------- |
| `Return`  | mode "default" | 切换到"default"模式 |
| `Escape`  | mode "default" | 切换到"default"模式 |
| `mod`+`r` | mode "default" | 切换到"default"模式 |

