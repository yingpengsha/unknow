<div align="center">

# Unknow 🌐

A translate tool in your terminal.

[![NPM version](https://img.shields.io/npm/v/unknow.svg?style=flat-square)](https://npmjs.org/package/unknow)
[![NPM downloads](http://img.shields.io/npm/dm/unknow.svg?style=flat-square)](https://npmjs.org/package/unknow)
[![](https://badge.juejin.im/entry/5be959e16fb9a049ec6a9908/likes.svg?style=flat-square)](https://juejin.im/entry/5be959e16fb9a049ec6a9908/detail)

![](http://www.yingpengsha.com/content/images/2019/10/image-12.png)

</div>

## Install

```bash
$ npm install unknow -g
```

## Usage

```bash
$ know word
```

For short:

```bash
$ kn word
```

Translation data is fetched from [fanyi.youdao.com](http://fanyi.youdao.com),
and only support translation between Chinese and English.

In Mac/Linux bash, words will be pronounced  by `say` command.

Translate one word.

```bash
$ know love
```

```js
 love  [ lʌv ] - n. 爱；爱情；喜好；（昵称）亲爱的；爱你的；心爱的人；钟爱之物；零分
 love  [ lʌv ] - v. 爱恋（某人）；关爱；喜欢（某物或某事）；忠于
 love  [ lʌv ] - n. (Love) （英、菲、瑞、美）洛夫（人名）
 
 1. love
    爱,爱情,爱心
 2. Endless Love
    无尽的爱,蓝色生死恋,不了情
 3. puppy love
    早恋,青春期恋爱,初恋
```

More words.

```bash
$ know make love
```

Support Chinese, even sentence.

```bash
$ know 和谐
```

```bash
$ know 子非鱼焉知鱼之乐
```

##  Error: spawn festival ENOENT

Try this workaround from [say.js](https://github.com/Marak/say.js#linux-notes) in Linux.

```
sudo apt-get install festival festvox-kallpc16k
```
