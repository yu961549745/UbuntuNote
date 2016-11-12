# UbuntuNote
Ubuntu软件安装、系统使用笔记

## 装机笔记
+ 设置分辨率
+ 换源：Software & Updates

## 中文支持
+ 先安装 Language Support
+ Install/Remove Languages -> Chinese Simplified
+ 设置中文为默认语言
+ 重启生效

## sudo 关闭密码
```
sudo gedit /etc/sudoers
```
进行替换，将第一行替换为第二行
```
%sudo	ALL=(ALL:ALL) ALL
%sudo	ALL=(ALL:ALL) NOPASSWD:ALL
```

# Chrome
```
sudo dpkg -i Chrome.deb
```
出现问题就
```
sudo apt-get install -f
```

## 搜狗输入法
+ 双击安装
+ 装完重启

## git
```
sudo apt-get install git
git config --global user.name yjt
git config --global user.email 961549745@qq.com
```

## vscode 
```
sudo dpkg -i vscode.deb
```
装完之后常用的拓展有
+ maple 
+ PHP InterlliSense
+ JS-CSS-HTML Formatter
常用设置有
```
"editor.wrappingColumn": 120
```

## eclipse
双击`eclipse-inst`直接安装

## java
```
sudo apt-get install default-jre
sudo apt-get install default-jdk 
```

## Apache2+php7
```
sudo apt-get install apache2  
sudo apt-get install php
sudo apt-get install libapache2-mod-php
```

## maple 18
```
sudo Maple18LinuxX64Installer.run
```

