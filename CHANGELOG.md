## [0.1.1] (2021-2-17)
* 重写了ReadMe和ChangeLog<br/>
rewrite ReadMe & ChangeLog
* 减小图标的大小为128 $\times$ 128像素<br/>
reduce the size of icon to 128 $\times$ 128
* 增加了伪指令匹配<br/>
add the match of directive
* 修改了数字匹配，改善了匹配未定义字符串中a-f0-9的问题，但是仍会匹配到全部由a-f0-9构成的字符串（比如“main”就不会被匹配到了，但是“abc”仍会被认为是数字）<br/>
optimize the match of number
* 学习了git的使用，插件在gitee有仓库了<br/>
create a repository at gitee

## [0.1.0] (2020-12-1)
* 删除了用命令启动插件的功能<br/>
disable the extension to be activated by command
* 稍微修改了几个正则表达式<br/>
modify several regular expression
* 之前把extension拼错了，还一直没发现……这个版本终于改掉了<br/>
change the spelling of "extension"
* 在package.json文件中添加了搜索关键字的属性<br/>
add "keyword" in package.json
* 重写了数字（包括地址和立即数等）的匹配，解决了之前匹配16进制数字无法匹配字母a-f的bug，也添加了新的bug——匹配未定义的非数字的a-f<br/>
rewrite match of number(including address, immediate, and so on), solving the problem of matching a-f in hexadecimal digit, meanwhile adding some new problem: matching undefined non-number a-f

## [0.0.2] (2020-11-18)
* 学习了ChangeLog和ReadMe的写法<br/>
learn how to write ChangeLog & Readme
* 添加了logo的图片，现在有黑色背景和透明背景的logo了<br/>
add logo icon. icons with black and tansparent background are avalable<br/>
（可以修改package.json文件的icon的文件名来切换logo图片）<br/>
(icon can be switched by modifying the icon name in package.json)
* 更改了mov等指令的颜色名<br/>
change the color name of instructions
* 优化了函数名匹配<br/>
optimize the matching of function name

## [0.0.1] (2020-11-14)
* 增加了支持的汇编语法<br/>
support more gramma of assembly language
* 优化了一些正则表达式<br/>
optimize some regular expression
* 增加了指令地址和函数名匹配的功能<br/>
add the function of match instruction address and function name
* 产生了新的bug<br/>
some new bugs appear

## [0.0.0] (2020-11-06)
* 初始版本<br/>
initial release