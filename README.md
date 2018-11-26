monaco-font
======

Install Monaco Font on Linux distro.

The idea started from here http://jorrel.blogspot.it/2007/11/monaco-on-ubuntu.html.
The main goal of the repo was to provide a script that download and install the `Monaco` font on ubuntu and not provide the font itself.

Unfortunately, due to license issue I removed all `Monaco_Linux.ttf` binary files form the repo, see discussion on issue [#10](https://github.com/cstrap/monaco-font/issues/10).

Nevertheless, all the scripts remain and accept a parameter that is the link to the font, see below; now all the scripts are generics and can accept a raw `url` that point to the font.
That's sound good! Some of the world's best open source fonts are hosted right here on GitHub and can be viewed form:
* https://github.com/showcases/fonts

---

**Disclaimer**: since I don't know the origin of the fonts, the original author and the original license, `Monaco` font (and potentially other fonts) will be used at own risk. Users should know the font license before download and install it. With this repo, I only provide the scripts that permits the download and then install fonts on your linux distro. All the scripts are provided as-is and have the public domain license; so you can copy, modify, use and so on without restrictions. 
**I invite all the github users that fork and forked the repository to know that there's copyright issue on using fonts without permissions.**

The `Monaco_Linux.ttf` font file can be downloaded from these links: 

* http://jorrel.blogspot.it/2007/11/monaco-on-ubuntu.html => http://jorrel.googlepages.com/Monaco_Linux.ttf
* http://www.gringod.com/ => http://www.gringod.com/wp-upload/software/Fonts/Monaco_Linux.ttf
* https://gist.github.com/epegzz/1634235#file-monaco_linux-powerline-ttf => https://gist.github.com/epegzz/1634235/raw/4691e901750591f9cab0b4ae8b7c0731ebf28cce/Monaco_Linux-Powerline.ttf
* https://github.com/todylu/monaco.ttf => https://github.com/todylu/monaco.ttf/blob/master/monaco.ttf?raw=true

On the net you'll find a plethora of variations of `Monaco`, if you want make a PR in order to update the list and please **provide and notify the license** of the font whatever it is.

Feel free to ask to the maintainer of the font file or who has the font file on his/her server what's the license and please made a PR in order to update the information on this repo. 

Many thanks for all the contributions!

---

## HOW TO

* Clone the repository
* launch the script and replace `[url]` with the url of the font, e.g. 

``` bash
./install-font-ubuntu.sh http://usystem.googlecode.com/files/MONACO.TTF
```

---
#### Install Monaco Font on Ubuntu

```bash
./install-font-ubuntu.sh [url]
```

#### Install Monaco Font on CentOS

```bash
./install-font-centos.sh [url]
```

#### Install Monaco Font on Gentoo

```bash
./install-font-gentoo.sh [url]
```

其他修改项 *https://blog.csdn.net/qq_26990831/article/details/51847416
  monaco字体是苹果系统下的字体，非常的好看，是我最喜欢的字体没有之一。现在我们就来在ubuntu下安装这个漂亮的字体
第一步：
             进入github下载这个字体，github地址是*https://github.com/cstrap/monaco-font 我们选择download zip的压缩包就可以。
第二步：
             进入本地下载目录，解压刚刚下载的压缩包，进入解压后的文件夹，我们会看到这几个文件
             install-font-archlinux.sh
             install-font-centos.sh
             install-font-gentoo.sh
             install-font-ubuntu.sh
             README.md
             接下来我们打开README.md文件，里面写的很详细，如何安装，ttf文件的下载链接都有
第三步：
             在README.md中有一行这样的命令./install-font-ubuntu.sh http://usystem.googlecode.com/files/MONACO.TTF，但是googlecode已经关闭了，所以我们要在README.md中另外找个下载链接。我用的是https://github.com/todylu/monaco.ttf/blob/master/monaco.ttf?raw=true这个链接。
第四步：
             打开终端进入解压后的目录执行sudo ./install-font-ubuntu.sh https://github.com/todylu/monaco.ttf/blob/master/monaco.ttf?raw=true这个命令，OK安装完成。这样我们就可以把终端和文本编辑器的字体设置成monaco了，你所用的开发工具也一样可以使用这个字体了。完美。

