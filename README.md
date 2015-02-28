zNodeClub
=======

This is a forum project fork from [NodeClub](https://github.com/cnodejs/nodeclub).

## 介绍

zNodeclub 是使用 **Node.js** 和 **MongoDB** 开发的社区系统，界面优雅，功能丰富，小巧迅速，
已在Node.js 中文技术社区 [CNode(http://cnodejs.org)](http://cnodejs.org) 得到应用，但你完全可以用它搭建自己的社区。

## 安装部署

*不保证 Windows 系统的兼容性*

```
1. install `node.js` `mongodb`
2. run mongod
3. `$ make install` 安装 Nodeclub 的依赖包
4. `$ make test` 确保各项服务都正常
5. `$ node app.js`
6. visit `localhost:3000`
7. done!
```

## 其他

跑测试

```bash
$ make test
```

跑覆盖率测试

```bash
$ make test-cov
```

## License

MIT
