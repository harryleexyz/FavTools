# 下载工具

## Aria2

- [Aria2 官网](https://aria2.github.io/)

  - [官方文档地址](https://aria2.github.io/manual/en/html/index.html)
  - [官方下载地址](https://github.com/aria2/aria2/releases)
  - [配置项的中文说明](https://github.com/mayswind/AriaNg/blob/master/src/langs/zh_Hans.txt)
  - 配置Tracker服务器
    - https://stray.love/itshou-zha/wei-aria2-tian-jia-tracker-fu-wu-qi
    - https://github.com/XIU2/TrackersListCollection/blob/master/README-ZH.md
  - [Web界面地址](https://github.com/ziahamza/webui-aria2)
  - Windows 快速使用：解压 `aria2.zip`  运行 `aria2-win-64bit\Strat.bat` 
    - **注意：不要运行 aria2.exe**

  - MacOS 快速使用

  ```bash
  # 安装
  brew update
  brew upgrade
  brew install aria2
  
  # 解压 aria2.zip
  brew install unzip
  unzip aria2.zip
  # 复制配置 到 home 目录
  cp -r .aria2 ~/
  
  # 后台启动
  aria2c -D
  # 关闭
  killall aria2c
  ```
  - 进入 `aria2-webui` 目录双击 `index.html` 浏览器操作就行
  - 三个文件说明：
    - `aria2.config`  配置文件，如果更改，双击 `Restart.bat` 重启
    - `aria2.session` 记录下载的进度，保证重启后不会丢失进度
    - `aria2.log` 日志

### 搜索网站【随便找的2个，不要太多】

- https://www.ciliwang.live/
- https://btos.pw/tags