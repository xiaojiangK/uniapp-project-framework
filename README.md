# uni-app项目模板
> 一个5年的web前端开源的uni-app快速开发模板，参考学习一同进步
> 建议uni-app使用时间达到1年以上的程序员来学习

### 使用步骤
1. 下载下来，解压成文件夹
2. 把项目包丢到HBuilder X里面
3. HBuilder X要安装scss/sass编译插件
4. 运行项目

# 项目结构

``` bash
├── components                              // 组件
│   ├── common                              // 公共组件
│   └── module                              // 项目组件
├── config                                  // 配置
│   ├── store                          		// vuex商店
│   │	├── modules							// vuex分类
│   │	│	├── common.js					// vuex通用数据管理
│   │	│	└── user.js						// vuex用户数据管理
│   │	└── index.js						// vuex主文件
│   ├── baseUrl.js                          // 项目配置
│   ├── html5Utils.js                       // H5相关的功能（公众号支付、公众号登录）
│   ├── login.js                            // 小程序登录js代码部分和登录拦截器代码
│   ├── requestConfig.js                    // 接口请求配置
│   ├── socket.js                           // webSocket相关代码
│   └── utils.js                            // 项目相关工具（公众号分享、小程序分享数据处理、支付、获取经纬度、支付分配）
├── pages  									// 项目页面
├── plugins                                 // 公共SDK（基本上不需要改）
│   ├── APPUpdate                          	// APP版本更新
│   ├── request                          	// 接口请求封装
│   ├── share                           	// APP分享
│   ├── md5.js                           	// md5加密
│   ├── permission.js                       // APP权限判断和打开手机系统设置
│   ├── utils.js                       		// 工具（时间转换、APP和小程序获取经纬度代码）
│   └── wxJsSDK.js                       	// 微信公众号SDK去权限获取页面
├── static                                  // 公共文件
│   ├── demo                          		// 本项目相关的图片（可删除）
│   ├── icon                          		// 项目图标
│   ├── mp-h5                          		// H5第三方包（公众号JS-SDK）
│   ├── mp-weixin                          	// 微信小程序第三方包
│   ├── share                          		// 分享SDK的图标
│   └── zhouWei-navBar                      // 导航组件的图标                                
├── style
│   ├── common.scss                         // 公共样式文件
│   ├── input.scss                         	// 公共表单样式
│   ├── mixin.scss                          // 样式配置文件
│   └── table.scss                          // 本项目相关的css（可删除）
├── unpackage                               // 项目编译后的文件
├── App.vue                                 // 项目主界面
├── main.js                                 // 程序入口文件，加载各种公共组件
├── manifest.json                           // uni-app项目类型及环境配置
├── pages.json                           	// 项目路由及项目界面配置
├── README.md                               // 项目介绍文件
└── template.h5.html                        // 项目发布的时候使用的文件
```
