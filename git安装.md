> 下载地址

[git官方下载地址](https://git-scm.com/downloads)

> 安装步骤

1. 首先，双击安装包，打开安装界面，然后点击Next下一步

![image](https://raw.githubusercontent.com/typeofYh/bookpic/master/git-3.png)

2. 配置git的安装组件，默认就行，继续点击Next下一步

![image](https://raw.githubusercontent.com/typeofYh/bookpic/master/git-4.png)
- 默认勾选的内容有：创建桌面快捷方式、右键快捷打开Git Bash Here和Git GUI Here以及后缀关联等
3. 设置能否在cmd命令行中执行git操作,选择第二项

![image](https://raw.githubusercontent.com/typeofYh/bookpic/master/git-5.png)

- 第一项的意思是：只能在Git Bash 中使用git，不会配置git命令的环境变量
- 第二项的意思是：除了Git Bash 以外，还可以在windows中的cmd命令行使用git，会自动配置好git命令的环境变量
- 第三项的意思是：Git和可选的Unix工具添加到环境配置中，git命令和unix工具命令都会添加到环境变量，但是会覆盖windows的查找和排序功能，不建议选择
4. 配置行结束,选择第一个选项

![image](https://raw.githubusercontent.com/typeofYh/bookpic/master/git-6.png)

- 第一个选项是：git在跨平台项目中提交的文本文件会自动转化格式，推荐在windows上配置的
- 第二个选项是：git在跨平台项目中提交的文本文件会自动转化格式，推荐在Unix上配置的
- 第三个选项是：git在检测或提交文本文件时不会转化格式，不推荐跨平台项目选择此选项
5. 在终端模拟器选择页面，默认选择第一个就行

![image](https://raw.githubusercontent.com/typeofYh/bookpic/master/git-7.png)
- 第一个选项是：Git使用MinTTY作为终端模拟器，Git的打开窗口可以自由调整大小
- 第二个选项是：Git使用windows的默认控制台窗口，Git的打开窗口不能自由调整大小
6. 最后配置Git的额外选项，选择默认就行，点击Install 开始安

![image](https://raw.githubusercontent.com/typeofYh/bookpic/master/git-8.png)
- 第一个选项：启动文件缓存(可选)
- 第二个选项：启动Git凭证管理器(可选)

++如果之前安装过其他版本的Git，会先卸载之前的版本，然后才会安装++

7. 安装完成后，桌面会有Git的快捷方式

![image](https://raw.githubusercontent.com/typeofYh/bookpic/master/git-9.png)
8. 在任意目录下右击，会有Git Bash Here和Git GUI Here的快捷方式

![image](https://raw.githubusercontent.com/typeofYh/bookpic/master/git-10.png)
9. 使用任意方式，打开Git

![image](https://raw.githubusercontent.com/typeofYh/bookpic/master/git-11.png)

==出现这个黑色的框框，就说明Git安装成功了！==

> git命令辅助工具

[sourcetree](https://www.sourcetreeapp.com/)




---

> 配置用户


```
git config --global user.name "用户名"
git config --global user.email "邮箱"
```
> 查看用户


```
git config --list 
```

> 删除错误配置信息


```
git config  --global --unset（user.name/user.eamil）
```

> 配置错误后：

```
git config --global --replace-all user.email 替换后的邮箱
git config --global --replace-all user.name 替换后的名字
```
---



