# mac-cmd

.重复按键
defaults write -g ApplePressAndHoldEnabled -bool false

# mdfind就是Spotlight功能的终端界面
... shell
report:aa hadoop$ mdfind -onlyin ./ "/accounts" |grep Controller.java
/Users/hadoop/Desktop/wwww/aa/web-1.1.0-SNAPSHOT.jar.src/com/ygsoft/community/web/controller/AttendanceController.java
/Users/hadoop/Desktop/wwww/aa/ygpay-1.1.0-SNAPSHOT.jar.src/com/ygsoft/ygpay/YGPayController.java
...

# 查看端口
sudo lsof -i tcp

# find
find ./ -iname "*sources*.jar"

# ngrok内网穿透 
https://www.ngrok.cc/
./sunny clientid 0de25c03849a3b30
