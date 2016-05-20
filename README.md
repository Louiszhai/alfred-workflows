# Alfred Workflows

Alfred 是 mac 下最流行的提升效率的工具, 其中 Alfred workflow 又将它自身的强大性能提升了几个数量级. 下面分享几个自主研发的workflow 供大家玩味.

## Shortcuts Query *(v1.0)*

[`[Download Workflow]`](https://github.com/Louiszhai/alfred-workflows/blob/master/Downloads/Shortcuts%20Query.alfredworkflow?raw=true)

推荐将启动快捷键设置为alt+k, Shortcuts Query 默认支持 Android Studio 或 WebStorm 快捷键的查询. 除此之外, 该 workflow 还内置了 vim 以及 tmux 共3种快捷键的查询. 

![shortcuts][Shortcuts Query]

同时它还支持其他快捷键的查询, 你唯一需要做的就是参考 `tmux.shortcuts` 文件, 再写一个快捷键对照表, 并将它命名为 "queryName" + ".shortcuts".

![shortcuts][1]    ![shortcuts][2]



## Front End Web Query *(v1.0)*

[`[Download Workflow]`](https://github.com/Louiszhai/alfred-workflows/blob/master/Downloads/Front%20End%20Web%20Query.alfredworkflow?raw=true)

前端工程师在开发的过程中经常需要查询一些资料, 几乎每次都要经过 "输入网址—>等待网页打开—>点击输入框—>输入关键字—>按回车查询—>焦急等待查询结果出来" 这样一个漫长的过程, 其中有许多次键盘操作以及鼠标操作, 不但思路容易打断还浪费时间. 我希望的是直接输入关键字, 即刻展示搜索结果, 这便整理了一些常用的网站, 诞生了 Front End Web Query, 该 workflow 默认支持4种资源的查询, 包括 mdn, baidu, google, w3c 等, 安装后, 可以自行增加对其他网站的查询. 

- 选中查询结果按shift键可以预览网页
- 按Enter键将在默认浏览器上直接打开网页

mdn search

![shortcuts][Front End Web Query01]

baidu search

![shortcuts][Front End Web Query02]

google search 需要翻墙, 天朝的GFW, 你懂得.

![shortcuts][Front End Web Query03]

w3c search 默认搜索html的便签, 可以自行更改查询的链接实现对其他 w3c 网站的查询, 为加快对搜索结果的展示, w3c search 默认开启了缓存机制, 更新查询链接后, 需要手动运行一次 "w3school().setAlfredCache()" (w3school.py源码中注释的部分).

![shortcuts][Front End Web Query04]



## License


Released under [MIT](http://rem.mit-license.org/)  LICENSE.



[Shortcuts Query]: images/shortcuts01.png
[Front End Web Query01]: images/shortcuts02.png
[Front End Web Query02]: images/shortcuts03.png
[Front End Web Query03]: images/shortcuts04.png
[Front End Web Query04]: images/shortcuts05.png
[1]: images/shortcuts-step01.png
[2]: images/shortcuts-step02.png
