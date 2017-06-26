# Angular 2 + Electron Quick start
Same code base built on Angular 2 can run both web and desktop environment.


Angular
=========

Angular is a development platform for building mobile and desktop web applications.

Repository:  https://github.com/angular/angular


Electron
=========

Build cross platform desktop apps with JavaScript, HTML, and CSS http://electron.atom.io

Repository:  https://github.com/electron/electron


Usage
=========

## Usage for Web
```sh
# Clone this repository
git clone https://github.com/zhongzf/angular2-electron-quickstart.git

cd angular2-electron-quickstart

# Install development dependency
npm install

# Build and start web server and browser
npm run web
```

![web](http://files.cnblogs.com/files/zhongzf/angular2_electron_web.gif)


## Usage for desktop with Electron
```sh

# Build and start Electron
npm start
```

![desktop](http://files.cnblogs.com/files/zhongzf/angular2_electron_desktop.gif)

## Usage for desktop with Electron



## Problem
=========

问题：运行 npm start 或者 npm run web 时报错
``` shell
/bin/sh: scss: command not found
```
解决：安装 sass
``` shell
$sudo gem install sass
$sass -v
Sass 3.4.24 (Selective Steve)
```
之后再执行 npm start 或 npm run web 成功启动！
