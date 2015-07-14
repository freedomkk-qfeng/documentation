# 安装gitbook

GitBook 可以通过Node.js的 **NPM** 工具来安装:

```
$ npm install gitbook-cli -g
```

查看gitbook的版本

```
$ gitbook versions
```

从 SUMMARY.md 来初始化一本图书的目录文件，可以这样个样子：

```
$ gitbook init
```

生成你的图书，并对外提供服务（默认端口是4000）:

```
$ gitbook serve [book] 
```

或者简单的生成图书的网页:

```
$ gitbook build [book] [output]
```