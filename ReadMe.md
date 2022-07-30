# Windows 应用中文打包

## 你可能需要做的

* 下载InnoSetup，然后打开CommonScript.iss
* 修改程序名、公司名、安装包名等。
* 修改需要打包的程序文件夹路径
* 修改需要忽略掉的路径



## 已实现的功能

* 一键安装。
* 可根据已有的安装包，进行更新再安装。
* 定义生成的桌面快捷方式。
* 忽略不需要的文件后缀和文件夹。（类似gitignore）

* 卸载程序放在单独的文件夹。（uninstall000.exe)



## 未实现的功能

* 添加相关文件，比如用户许可协议等
* 更新UI
* 修改uninstall的名称
* 在windows应用和功能中，无图标。



## 感谢

* 感谢tgtsml的项目[InnoSetupScript](https://github.com/tgtsml/InnoSetupScript)，本项目在此项目基础上进行调整和修改。
