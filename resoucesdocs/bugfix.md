﻿##妈的编辑器 bug list

1. \*选中多行后使用TAB键，不应该删除内容，应该是同时缩进多行。同时应该支持用Shift+TAB向前缩进。
2. [已改]html预览快捷键，建议用F5（刷新），或者可以自行设定
3. [ok]关闭没有保存的文件，会出现提示对话框，这个对话框建议加一个“取消”按钮，同时绑定ESC快捷键。
4. [ok]依然是上面这个对话框，如果单击“是”，进入到另存为对话框，这时如果单击“取消”或者按Esc，则没有保存过的文件被关闭了（悲剧），建议这种情况应该回到该文件的编辑页面。
5. 关闭一个tab后，建议回到前一个tab，而不是第一个tab。
6. [ok]拖动md文件打开，应该拖动到程序任何地方都可以。
7.自动读取文件更新
8.获取焦点上有问题

##要增加的功能##
1. tab空格替代可选，tab字符可设置
2. url的target属性？我觉得设计者不设计这个，可能是考虑，让使用者直接用HTML标签。