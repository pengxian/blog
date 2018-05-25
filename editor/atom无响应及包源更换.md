Atom无响应及包源更换
==

# 无响应

原因：clone插件项目到你的Atom插件目录，进行npm install安装，导致正常打开无响应

# 换源操作

切换到Atom安装目录下`~/.atom`, 编辑`.atomrc`文件，如果没有，就新建一个

`vim .atomrc`添加如下源

```
registry = https://registry.npm.taobao.org
```

之后即可在atom中通过正常安装完成
