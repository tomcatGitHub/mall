
### 基于Vue开发的商城前台页面
### 新增与优化
- [x] 优化页脚、增加商品搜索框组件
- [x] 优化登录注册界面
- [x] 新增搜索页面，实现高亮分页搜索
- [x] 新增捐赠页面，捐赠列表显示
- [x] 全部商品页面实现分页
- [x] 优化订单详情，实现查看订单进度，可对订单进行处理
- [x] 实现生成订单接口、优化地址管理编辑选择
- [x] 实现查看个人订单分页
- [x] 接入[XPay个人收款支付系统](https://github.com/Exrick/xpay)
- [x] 首页升级！重构首页，后台可配置，包括3D轮播图
- [x] 新增分类查看品牌周边等

![](http://oweupqzdv.bkt.clouddn.com/QQ%E6%88%AA%E5%9B%BE20171022183906.jpg "首页")

![](http://oweupqzdv.bkt.clouddn.com/QQ%E6%88%AA%E5%9B%BE20171022222841.jpg "页脚")

![](http://oweupqzdv.bkt.clouddn.com/QQ%E6%88%AA%E5%9B%BE20171022223650.jpg "搜索框组件")

![](http://oweupqzdv.bkt.clouddn.com/QQ%E6%88%AA%E5%9B%BE20171109215656.jpg "搜索结果")

![](http://oweupqzdv.bkt.clouddn.com/QQ%E6%88%AA%E5%9B%BE20171022202842.jpg "无搜索结果")

![](http://oweupqzdv.bkt.clouddn.com/QQ%E6%88%AA%E5%9B%BE20171022223142.jpg "分页")

![](http://oweupqzdv.bkt.clouddn.com/QQ%E6%88%AA%E5%9B%BE20171022190036.jpg "订单详情")

![](http://oweupqzdv.bkt.clouddn.com/QQ%E6%88%AA%E5%9B%BE20171022190107.jpg "订单进度")

![](http://oweupqzdv.bkt.clouddn.com/QQ%E6%88%AA%E5%9B%BE20171114233321.jpg "登录界面")

### 所用技术

- Vue 2.x
- Vuex
- Vue Router
- [Element UI](http://element.eleme.io/#/zh-CN)
- ES6
- webpack
- axios
- Node.js
- 第三方SDK
    - [极验Test-button人机验证码](http://www.geetest.com/Test-button.html)

### 本地开发运行
- 在 `src/api/goods.js` 中的 `getQuickSearch` 方法里修改你的Elasticseach服务器IP以及RESTful快速搜索提示接口配置
- 若不启动后端项目，勉强预览运行此前端项目可尝试注释掉 `src/main.js` 中第 `8、10、37-59` 行代码
- 在项目根文件夹下先后执行命令 `npm install` 、 `npm run dev`
- 商城前台端口默认9999 http://localhost:9999
## 部署
- 先后执行命令 `npm install` 、 `npm run build` 将打包生成的 `dist` 静态文件放置服务器中，并配置路由代理

### 后期在vue-cli项目中集成echarts图表,做数据可视化操作
