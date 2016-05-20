# Alfred Workflows

Alfred 是 mac 下最流行的提升效率的工具, 其中 Alfred workflow 又将它自身的强大性能提升了几个数量级. 下面分享几个自主研发的workflow 供大家玩味.

## Shortcuts Query *(v1.0)*

[`[Download Workflow]`](https://github.com/Louiszhai/Louiszhai/alfred-workflows/blob/master/Downloads/Shortcuts%20Query.alfredworkflow?raw=true)

推荐将启动快捷键设置为alt+k, Shortcuts Query 默认支持 Android Studio 或 WebStorm 快捷键的查询. 除此之外, 该 workflow 还内置了 vim 以及 tmux 共3种快捷键的查询. 

![shortcuts][1]

同时它还支持其他快捷键的查询, 你唯一需要做的就是参考 `tmux.shortcuts` 文件, 再写一个快捷键对照表, 并将它命名为 "queryName" + ".shortcuts".

![shortcuts][2]    ![shortcuts][3]

## License


Released under [MIT](http://rem.mit-license.org/)  LICENSE.



[1]: images/shortcuts01.png
[2]: images/shortcuts-step01.png
[3]: images/shortcuts-step02.png