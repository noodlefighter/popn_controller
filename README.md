# Popn手台固件
只是简单地把PA0-PA7, PB0, PB1共9个IO口作为按键端口, 对应到ASDFGHJKL九个按键.

编译方法:
1. 检出``git@github.com:shabao-studio/ChibiOS.git`` (分支stable_17.6.x)到ChibiOS目录
2. 检出``git@github.com:shabao-studio/tmk_keyboard.git``到tmk_keyboard目录
3. 进入code目录, 执行make