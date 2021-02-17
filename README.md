# AT&T Highlight Extension for Visual Code Studio
## vscode AT&T语法高亮插件
## Screenshot 效果截屏
![screenshot](https://gitee.com/fred-bohr-locke/ATT/raw/master/presentation.png)
## Installation 安装方式
1.  vscode插件商店直接下载<br/>
install from vscode extention marketplace
2.  点击[这里](https://gitee.com/fred-bohr-locke/ATT/tree/master/)，进入gitee仓库，下载vsix安装包<br/>
click [here](https://gitee.com/fred-bohr-locke/ATT/tree/master/), go to the repository at gitee, and download the vsix package
## Extension Architecture 插件架构
通过yo code扩展生成器产生了插件的主要架构。<br/>
Extention architecture is mainly created by yo code.
* package.json &emsp; vscode插件的设置？
* logo.jpg &emsp; 图标文件
* README.md & CHANGELOG.md &emsp; 插件说明和版本更新说明
* language-configuration.json &emsp; AT&T语言的符号匹配
* .\syntax\att.tmLanguage.json &emsp; AT&T语言的语法词汇匹配
* .\syntax\comments.txt &emsp; 由于att.tLanguage.json不能写注释，把注释单独写在了comments.txt里，可以直接忽略