
Nodejs(Express)+MongoDB+jQuery+Bootstrap Personal blog.

## 目录结构：

```
data  数据库文件夹
model 模块目录
---- db.js      封装了对数据库的操作（增删改查）
---- md5.js     封装了md5加密函数
---- setting.js 封装了对数据库的接口
node_modules 项目依赖包
public 静态资源目录
routers 路由目录
---- router.js  对请求接口的统一处理
views 模板目录
app.js 入口文件
package.json 文件依赖配置包
```

## Install

##### 安装EJblog前要先安装node环境和MongoDB数据库


第一步：

安装依赖包

```
  npm install
```

第二步：

启动MongoDB数据库和保存数据库的位置,url是相对路径。
```
  mongod --dbpath url
```

第三步：

```
  node app.js
```

