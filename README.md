<p align="center">
  <a href="https://tdesign.tencent.com/" target="_blank">
    <img alt="TDesign Logo" width="200" src="https://tdesign.gtimg.com/site/TDesign.png">
  </a>
</p>



# TDesign零售行业模版示例小程序

TDesign零售模版示例小程序采用 [TDesign 企业级设计体系小程序解决方案](https://tdesign.tencent.com/miniprogram/overview)进行搭建，依赖[TDesign微信小程序组件库](https://github.com/Tencent/tdesign-miniprogram)，涵盖完整的基本零售场景需求。



## 预览



## 项目介绍

### 1. 页面覆盖

零售行业模版小程序总共包含28个完整的页面，涵盖首页，商品详情页，个人中心，售后流程等基础页面。采用mock数据进行展示，提供了完整的零售商品展示、交易与售后流程。

|          | 页面                     |
| :------- | :----------------------- |
| 首页     | 首页                     |
|          | 营销活动页               |
|          | 搜索页                   |
|          | 搜索结果页               |
|          | 商品列表页               |
|          | 商品详情页               |
| 分类页   | 分类页                   |
|          | 商品评价列表页           |
|          | 商品详情评价页           |
|          | （已完成订单）商品评价页 |
| 购物车   | 购物车                   |
|          | 结算页                   |
|          | 支付结果页               |
|          | 订单列表页               |
|          | 订单详情页               |
|          | 发票页                   |
| 售后     | 申请售后页               |
|          | 售后列表页               |
|          | 售后详情页               |
| 个人中心 | 个人中心页               |
|          | 个人信息页               |
|          | 收货地址列表页           |
|          | 收货地址编辑页           |
|          | 物流详情页               |
|          | 退货物流页               |
|          | 优惠券列表页             |
|          | 优惠券详情页             |
|          | 优惠券商品页             |



### 2. 项目构成

零售行业模版小程序采用基础的 JavaScript + wxss + eslint  进行构建，降低了使用门槛。

项目目录结构如下：

```
|-- tdesign-miniprogram-starter
    |-- README.md
    |-- app.js
    |-- app.json
    |-- app.wxss
    |-- components	//	公共组件库
    |-- config	//	基础配置
    |-- custom-tab-bar	//	自定义 tabbar
    |-- model	//	mock 数据
    |-- pages
    |   |-- cart	//	购物车相关页面
    |   |-- coupon	//	优惠券相关页面
    |   |-- goods	//	商品相关页面
    |   |-- home	//	首页
    |   |-- order	//	订单售后相关页面
    |   |-- promotion-detail	//	营销活动页面
    |   |-- usercenter	//	个人中心及收货地址相关页面
    |-- services	//	请求接口
    |-- style	//	公共样式与iconfont
    |-- utils	//	工具库
```



### 3. 数据模拟

零售小程序采用真实的接口数据，模拟后端返回逻辑，在小程序展示完整的购物场景与购物体验逻辑。



### 4. 添加新页面

1. 在 `pages `目录下创建对应的页面文件夹
2. 在 `app.json` 文件中的 ` "pages"` 数组中加上页面路径
3. [可选]在 `project.config.json` 文件的 `"miniprogram-list"` 下添加页面配置



### 5. 构建运行

1. `npm install`
2. 小程序开发工具中引入工程
3. 构建 npm



### 6. 代码风格控制

`prettier`
