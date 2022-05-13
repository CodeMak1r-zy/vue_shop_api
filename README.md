## Vue_shop_api    

vue_shop is an e-commerce background management system based on vue2 + elementui component library    

This is a api document for [vue_shop](https://github.com/CodeMak1r-zy/vue_shop)    

#### You can run this file `before` [vue_shop](https://github.com/CodeMak1r-zy/vue_shop) in order to run vue_shop~~

You can start with    

```
npm init -y
npm install
node ./app.js
```

Review [ONLINE](https://github1s.com/CodeMak1r-zy/vue_shop_api)     




#### 项目整体文件说明
- `config` 配置文件目录
  - `default.json` 默认配置文件（其中包含数据库配置，jwt配置）
- `dao` 数据访问层，存放对数据库的增删改查操作
  - `DAO.js` 提供的公共访问数据库的方法
- `models` 存放具体数据库 ORM 模型文件
- `modules` 当前项目模块
  - `authorization.js` API权限验证模块
  - `database.js` 数据库模块（数据库加载基于 nodejs-orm2 库加载）
  - `passport.js` 基于 passport 模块的登录搭建
  - `resextra.js` API 统一返回结果接口
- `node_modules` 项目依赖的第三方模块
- `routes` 统一路由
  - `api` 提供 api 接口
  - `mapp` 提供移动APP界面
  - `mweb` 提供移动web站点
- `services` 服务层，业务逻辑代码在这一层编写，通过不同的接口获取的数据转换成统一的前端所需要的数据
- `app.js` 主项目入口文件
- `package.json` 项目配置文件

---

`If you like this,plz star!✨✨`   
`You can contact me through:pseudonymgeanmu@163.com`   
Blog in:  [CSDN](https://blog.csdn.net/Svik_zy?spm=1000.2115.3001.5343)  
gitee:  [gitee](https://gitee.com/CodeMak1r)

🤓 🤓


---
