
1、googlechrome.dmg  google chrome浏览器

2、Microsoft Office 2021 for Mac LTSC 16.66 .dmg  微软office办公套件

3、sogouwubi_mac_140 搜狗五笔输入法

4、EasyConnect_7_6_7_4.dmg  VPN

5、Microsoft Remote Desktop v10.9.1.dmg  远程桌面

6、Install Cursor  Cursor开发IDE，带GPT4

7、PDManer-mac_apple_v4.7.0.dmg  建模工具


启动时文件已损坏解决办法

sudo xattr -r -d com.apple.quarantine /Applications/PDManer.app

  

Parallels虚拟机启动后，Mac主机无法上网

sudo rm /Library/Preferences/SystemConfiguration/NetworkInterfaces.plist && sudo killall -9 configd

或在设置中搜索DNS服务器，设置为192.168.1.1

注：mac默念是192.168.110.1

DNS服务器可以设置为 8.8.8.8

  

安装库命令：

1、安装Homebrew

/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

安装完成后按提示执行两个命令

  

2、安装Node.js

brew install node

  

3、安装pnpm

npm install -g pnpm

  

换镜像安装

pip install requests -i https://mirrors.aliyun.com/pypi/simple/