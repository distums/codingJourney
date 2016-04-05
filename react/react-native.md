#### props

1. 用react做开发
2. flex布局 

#### cons

1. css写法难受，且与web css不尽相同，比如flex
2. 需要懂得原生，特别没有现成库的情况，需要写原生转js
3. 开发体验难受，genymotion模拟器偶尔卡死，特别是在debug模式下会出现响应慢甚至无响应
4.  布局排版开发不方便，虽说用js写，但并不能用开发者工具查看dom结构以及改写样式
5. 安装有原生依赖的库非常难受，需要到处加代码
6.  小米平板命令或者其他方式都不能调出app的菜单—>设备以及系统要求，定制系统是否兼容
7.  现在还处于不成熟的阶段，更新非常快
8.  文档乱糟糟，component演示站甚至是挂的

#### conclusion

react-native之于app类似jquery之于web，然而react-native在透明性做的并不好，差异还是要开发者解决，比如TextInput，android默认是有border line，然后这时要去掉这条线就要使用待android前缀的某个属性。然而这也不能怪react-native，我觉得app开发差异要比不用浏览器差异大太多了。
