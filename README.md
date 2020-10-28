## 1.功能与设计

### 1.1 功能分析
    搭建一个具有多人注册、登录、发表文章、登出功能的博客

### 1.2 设计目标
    未登录：主页导航显示（首页、注册、登录，下面显示已发送的文章、发表日期及作者）
    登陆后：主页导航显示 （首页、发表文章、退出，下面显示已发送的文章、发表日期及作者）
    用户登录、注册、发表成功以及等处都返回到主页

### 1.3 模块特性

## 初始化

### a.初始化并安装依赖包

```js
1.
npm init -y
2.
npm i body-parser cookie-parser debug ejs express morgan serve-favicon express-session connect-mongo mongoose connect-flash multer async -S
```

### b.初始化git

新建.gitignore文件

```js
//.gitignore
node_modules
.idea
lib
```

去github建一个空项目

