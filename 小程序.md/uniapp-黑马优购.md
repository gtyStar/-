# uniapp-黑马优购

# uniapp-黑马优购

[黑马官方在线md笔记](https://applet-base-api-t.itheima.net/docs-uni-shop/index.htm)

# Headline

TIP

基于 uniapp 开发的微信小程序商城项目

## [#](https://applet-base-api-t.itheima.net/docs-uni-shop/index.htm#tabbar-相关的页面)tabBar 相关的页面

### [#](https://applet-base-api-t.itheima.net/docs-uni-shop/index.htm#首页)首页

![w317](https://applet-base-api-t.itheima.net/docs-uni-shop/0-1.f74c4d08.png)

### [#](https://applet-base-api-t.itheima.net/docs-uni-shop/index.htm#分类)分类

![w317](https://applet-base-api-t.itheima.net/docs-uni-shop/0-2.b5fef657.png)

### [#](https://applet-base-api-t.itheima.net/docs-uni-shop/index.htm#购物车)购物车

![w317](https://applet-base-api-t.itheima.net/docs-uni-shop/0-3.9feb6833.png) ![w317](https://applet-base-api-t.itheima.net/docs-uni-shop/0-4.2f3b901d.png) ![w317](https://applet-base-api-t.itheima.net/docs-uni-shop/0-5.b98d4cbd.png)

### [#](https://applet-base-api-t.itheima.net/docs-uni-shop/index.htm#我的)我的

![w317](assets/w317-20250401193241-mlnlwrr.png) ![w317](https://applet-base-api-t.itheima.net/docs-uni-shop/0-7.73a762ca.png) ![w317](https://applet-base-api-t.itheima.net/docs-uni-shop/0-8.5fa0379f.png)

## [#](https://applet-base-api-t.itheima.net/docs-uni-shop/index.htm#搜索)搜索

![w317](assets/w317-20250401193241-q6otk1z.png) ![w317](https://applet-base-api-t.itheima.net/docs-uni-shop/0-10.a47a93b5.png)

## [#](https://applet-base-api-t.itheima.net/docs-uni-shop/index.htm#商品列表)商品列表

![w317](https://applet-base-api-t.itheima.net/docs-uni-shop/0-14.7e51b66a.png)

## [#](https://applet-base-api-t.itheima.net/docs-uni-shop/index.htm#商品详情)商品详情

![w317](https://applet-base-api-t.itheima.net/docs-uni-shop/0-11.7d8b4a84.png) ![w317](https://applet-base-api-t.itheima.net/docs-uni-shop/0-12.b0e03cee.png) ![w317](https://applet-base-api-t.itheima.net/docs-uni-shop/0-13.79de3e1d.png)

## [#](https://applet-base-api-t.itheima.net/docs-uni-shop/index.htm#微信支付)微信支付

![w317](https://applet-base-api-t.itheima.net/docs-uni-shop/0-15.c23c7a61.png)

# 1. 起步

## [#](https://applet-base-api-t.itheima.net/docs-uni-shop/1.start.html#_1-1-uni-app-简介)1.1 uni-app 简介

**uni-app 是一个使用 Vue.js 开发所有前端应用的框架**。开发者编写一套代码，可发布到 iOS、Android、H5、以及各种小程序（微信/支付宝/百度/头条/QQ/钉钉/淘宝）、快应用等多个平台。

![](https://applet-base-api-t.itheima.net/docs-uni-shop/1-7.43264ae4.png)

> 详细的 uni-app 官方文档，请翻阅 https://uniapp.dcloud.net.cn/

## [#](https://applet-base-api-t.itheima.net/docs-uni-shop/1.start.html#_1-2-开发工具)1.2 开发工具

uni-app 官方推荐使用 **HBuilderX** 来开发 uni-app 类型的项目。主要好处：

- 模板丰富
- 完善的智能提示
- 一键运行

> 当然，你依然可以根据自己的喜好，选择使用 VS Code、Sublime、~~记事本~~... 等自己喜欢的编辑器！

### [#](https://applet-base-api-t.itheima.net/docs-uni-shop/1.start.html#_1-2-1-下载-hbuilderx)1.2.1 下载 HBuilderX

1. 访问 HBuilderX 的官网首页 https://www.dcloud.io/hbuilderx.html
2. 点击首页的 `DOWNLOAD` 按钮
3. 选择下载 `正式版` -\> `App 开发版`​

### [#](https://applet-base-api-t.itheima.net/docs-uni-shop/1.start.html#_1-2-2-安装-hbuilderx)1.2.2 安装 HBuilderX

1. 将下载的 `zip包` 进行解压缩
2. 将解压之后的文件夹，存放到**纯英文**的目录中（且不能包含括号等特殊字符）
3. 双击 `HBuilderX.exe` 即可启动 HBuilderX

### [#](https://applet-base-api-t.itheima.net/docs-uni-shop/1.start.html#_1-2-3-安装-scss-sass-编译)1.2.3 安装 scss/sass 编译

为了方便编写样式（例如：`<style lang="scss"></style>`），建议安装 `scss/sass 编译` 插件。插件下载地址：

> https://ext.dcloud.net.cn/plugin?name\=compile-node-sass

进入插件下载页面之后，点击右上角的 `使用 HBuilderX 导入插件` 按钮进行自动安装，截图如下：

![](https://applet-base-api-t.itheima.net/docs-uni-shop/1-1.74fed64c.png)

### [#](https://applet-base-api-t.itheima.net/docs-uni-shop/1.start.html#_1-2-4-快捷键方案切换)1.2.4 快捷键方案切换

操作步骤：工具 -\> 预设快捷键方案切换 -\> VS Code

![](https://applet-base-api-t.itheima.net/docs-uni-shop/1-2.1c0c98c6.png)

### [#](https://applet-base-api-t.itheima.net/docs-uni-shop/1.start.html#_1-2-5-修改编辑器的基本设置)1.2.5 修改编辑器的基本设置

操作步骤：工具 -\> 设置 -\> 打开 Settings.json 按需进行配置

![](https://applet-base-api-t.itheima.net/docs-uni-shop/1-3.b48ee161.png)

**源码视图**下可用的参考配置：

```json
{
  "editor.colorScheme": "Default",
  "editor.fontSize": 12,
  "editor.fontFamily": "Consolas",
  "editor.fontFmyCHS": "微软雅黑 Light",
  "editor.insertSpaces": true,
  "editor.lineHeight": "1.5",
  "editor.minimap.enabled": false,
  "editor.mouseWheelZoom": true,
  "editor.onlyHighlightWord": false,
  "editor.tabSize": 2,
  "editor.wordWrap": true,
  "explorer.iconTheme": "vs-seti",
  "editor.codeassist.px2rem.enabel": false,
  "editor.codeassist.px2upx.enabel": false
}
```

> Tips：可以使用 **Ctrl + 鼠标滚轮** 缩放编辑器

## [#](https://applet-base-api-t.itheima.net/docs-uni-shop/1.start.html#_1-3-新建-uni-app-项目)1.3 新建 uni-app 项目

1. 文件 -\> 新建 -\> 项目
   ![](https://applet-base-api-t.itheima.net/docs-uni-shop/1-4.b7efec14.png)
2. 填写项目基本信息
   ![](https://applet-base-api-t.itheima.net/docs-uni-shop/1-5.585d746d.png)
3. 项目创建成功
   ![](https://applet-base-api-t.itheima.net/docs-uni-shop/1-6.01c783f2.png)

## [#](https://applet-base-api-t.itheima.net/docs-uni-shop/1.start.html#_1-4-目录结构)1.4 目录结构

一个 uni-app 项目，默认包含如下目录及文件：

```text
┌─components            uni-app组件目录
│  └─comp-a.vue         可复用的a组件
├─pages                 业务页面文件存放的目录
│  ├─index
│  │  └─index.vue       index页面
│  └─list
│     └─list.vue        list页面
├─static                存放应用引用静态资源（如图片、视频等）的目录，注意：静态资源只能存放于此
├─main.js               Vue初始化入口文件
├─App.vue               应用配置，用来配置小程序的全局样式、生命周期函数等
├─manifest.json         配置应用名称、appid、logo、版本等打包信息
└─pages.json            配置页面路径、页面窗口样式、tabBar、navigationBar 等页面类信息
```

## [#](https://applet-base-api-t.itheima.net/docs-uni-shop/1.start.html#_1-5-把项目运行到微信开发者工具)1.5 把项目运行到微信开发者工具

1. 填写自己的微信小程序的 AppID：
   ![](https://applet-base-api-t.itheima.net/docs-uni-shop/1-8.4c14eb68.png)
2. 在 HBuilderX 中，配置“微信开发者工具”的**安装路径**：
   ![](https://applet-base-api-t.itheima.net/docs-uni-shop/1-9.deca7c09.png)
3. 在微信开发者工具中，通过 `设置 -> 安全设置` 面板，开启“微信开发者工具”的**服务端口**：
   ![](assets/image-20250401192518-kmqubaf.png)
4. 在 HBuilderX 中，点击菜单栏中的 `运行 -> 运行到小程序模拟器 -> 微信开发者工具`，将当前 uni-app 项目编译之后，自动运行到微信开发者工具中，从而方便查看项目效果与调试：
   ![](https://applet-base-api-t.itheima.net/docs-uni-shop/1-11.2637002b.png)
5. 初次运行成功之后的项目效果：
   ![](https://applet-base-api-t.itheima.net/docs-uni-shop/1-12.1b33864e.png)

## [#](https://applet-base-api-t.itheima.net/docs-uni-shop/1.start.html#_1-6-使用-git-管理项目)1.6 使用 Git 管理项目

### [#](https://applet-base-api-t.itheima.net/docs-uni-shop/1.start.html#_1-6-1-本地管理)1.6.1 本地管理

1. 在项目根目录中新建 `.gitignore` 忽略文件，并配置如下：

```text
# 忽略 node_modules 目录
/node_modules
/unpackage/dist
```

> 注意：由于我们忽略了 unpackage 目录中**仅有的** dist 目录，因此默认情况下， unpackage 目录不会被 Git 追踪

> 此时，为了让 Git 能够正常追踪 unpackage 目录，按照惯例，我们可以在 unpackage 目录下创建一个叫做 `.gitkeep` 的文件进行占位

2. 打开终端，切换到项目根目录中，运行如下的命令，初始化本地 Git 仓库：

```bash
git init
```

3. 将所有文件都加入到暂存区：

```bash
git add .
```

4. 本地提交更新：

```bash
git commit -m "init project"
```

### [#](https://applet-base-api-t.itheima.net/docs-uni-shop/1.start.html#_1-6-2-把项目托管到码云)1.6.2 把项目托管到码云

1. 注册并激活码云账号（ 注册页面地址：[https://gitee.com/signup](https://gitee.com/signup) ）
2. 生成并配置 SSH 公钥

   在 [C:\Users\00.ssh](C:\Users\00\.ssh) 查看有没有 id_rsa.pub 文件，里面存放着 <span data-type="text" style="color: var(--b3-font-color8);">公钥</span>

   没有公钥的话在终端执行 **ssh-keygen -t rsa -C **​ **"**​**1262583075@qq.com**​ **"**

   把公钥添加到 gitee 网站里：<span data-type="text" style="color: var(--b3-font-color8);">设置</span> -> <span data-type="text" style="color: var(--b3-font-color8);">ssh公钥</span>

   终端执行 **ssh -t git@gitee.com** 检测是否配置成功，输入 yes 后，看到 **successfully**  就成功了
3. 创建空白的码云仓库

   ![image](assets/image-20250401203633-3e72kww.png)
4. 把本地项目上传到码云对应的空白仓库中

   在项目根目录里，打开终端，运行最后两行命令

   ![image](assets/image-20250401204207-qd8hosn.png)

   运行完后刷新 gitee仓库 网页

# 2. tabBar

## [#](https://applet-base-api-t.itheima.net/docs-uni-shop/2.tabbar.html#_2-0-创建-tabbar-分支)2.0 创建 tabBar 分支

运行如下的命令，基于 master 分支在本地创建 tabBar 子分支，用来开发和 tabBar 相关的功能：

```bash
git checkout -b tabbar
```

## [#](https://applet-base-api-t.itheima.net/docs-uni-shop/2.tabbar.html#_2-1-创建-tabbar-页面)2.1 创建 tabBar 页面

在 `pages` 目录中，创建首页(home)、分类(cate)、购物车(cart)、我的(my) 这 4 个 tabBar 页面。在 HBuilderX 中，可以通过如下的两个步骤，快速新建页面：

1. 在 `pages` 目录上鼠标右键，选择**新建页面**
2. 在弹出的窗口中，填写**页面的名称**、**勾选 scss 模板**之后，点击创建按钮。截图如下：
   ![](https://applet-base-api-t.itheima.net/docs-uni-shop/2-1.a57d1b5c.png)

## [#](https://applet-base-api-t.itheima.net/docs-uni-shop/2.tabbar.html#_2-2-配置-tabbar-效果)2.2 配置 tabBar 效果

1. 将 `资料` 目录下的 `static 文件夹` 拷贝一份，替换掉项目根目录中的 `static 文件夹`​

   <div>
   <span data-type="text" style="color: var(--b3-font-color8);">注意：要保留原本的 customicons 相关的文件</span>
   </div>
2. 修改项目根目录中的 `pages.json` 配置文件，新增 `tabBar` 的配置节点如下：

   ```json
   {
     "tabBar": {
       "selectedColor": "#C00000",
       "list": [
         {
           "pagePath": "pages/home/home",
           "text": "首页",
           "iconPath": "static/tab_icons/home.png",
           "selectedIconPath": "static/tab_icons/home-active.png"
         },
         {
           "pagePath": "pages/cate/cate",
           "text": "分类",
           "iconPath": "static/tab_icons/cate.png",
           "selectedIconPath": "static/tab_icons/cate-active.png"
         },
         {
           "pagePath": "pages/cart/cart",
           "text": "购物车",
           "iconPath": "static/tab_icons/cart.png",
           "selectedIconPath": "static/tab_icons/cart-active.png"
         },
         {
           "pagePath": "pages/my/my",
           "text": "我的",
           "iconPath": "static/tab_icons/my.png",
           "selectedIconPath": "static/tab_icons/my-active.png"
         }
       ]
     }
   }
   ```

## [#](https://applet-base-api-t.itheima.net/docs-uni-shop/2.tabbar.html#_2-3-删除默认的-index-首页)2.3 删除默认的 index 首页

1. 在 HBuilderX 中，把 `pages` 目录下的 `index首页文件夹` 删除掉
2. 同时，把 `page.json` 中记录的 `index 首页` 路径删除掉
3. 为了防止小程序运行失败，在微信开发者工具中，手动删除 `pages` 目录下的 `index 首页文件夹`​
4. 同时，把 `components` 目录下的 `uni-link 组件文件夹` 删除掉

## [#](https://applet-base-api-t.itheima.net/docs-uni-shop/2.tabbar.html#_2-4-修改导航条的样式效果)2.4 修改导航条的样式效果

1. 打开 `pages.json` 这个全局的配置文件
2. 修改 `globalStyle` 节点如下：

   ```json
   {
     "globalStyle": {
       "navigationBarTextStyle": "white",
       "navigationBarTitleText": "黑马优购",
       "navigationBarBackgroundColor": "#C00000",
       "backgroundColor": "#FFFFFF"
     }
   }
   ```

## [#](https://applet-base-api-t.itheima.net/docs-uni-shop/2.tabbar.html#_2-5-分支的提交与合并)2.5 分支的提交与合并

1. 将本地的 tabbar 分支进行本地的 commit 提交：

```bash
git add .
git commit -m "完成了 tabBar 的开发"
```

2. 将本地的 tabbar 分支推送到远程仓库进行保存：

```bash
git push -u origin tabbar
```

3. 将本地的 tabbar 分支合并到本地的 master 分支：

```bash
git checkout master
git merge tabbar
```

4. 删除本地的 tabbar 分支：

```bash
git branch -d tabbar
```

# 3. 首页

## [#](https://applet-base-api-t.itheima.net/docs-uni-shop/3.home.html#_3-0-创建-home-分支)3.0 创建 home 分支

运行如下的命令，基于 master 分支在本地创建 home 子分支，用来开发和 home 首页相关的功能：

```bash
git checkout -b home
```

## [#](https://applet-base-api-t.itheima.net/docs-uni-shop/3.home.html#_3-1-配置网络请求)3.1 配置网络请求

由于平台的限制，小程序项目中**不支持 axios**，而且原生的 `wx.request()` API 功能较为简单，**不支持拦截器**等全局定制的功能。因此，建议在 uni-app 项目中使用 `@escook/request-miniprogram` 第三方包发起网络数据请求。

> 请参考官方文档：[https://www.npmjs.com/package/@escook/request-miniprogram](https://www.npmjs.com/package/@escook/request-miniprogram)
>
> 进行安装、配置、使用

最终，在项目的 `main.js` 入口文件中，通过如下的方式进行配置：

```js
import { $http } from '@escook/request-miniprogram'

uni.$http = $http
// 配置请求根路径
$http.baseUrl = 'https://www.uinav.com'

// 请求开始之前做一些事情
$http.beforeRequest = function (options) {
  uni.showLoading({
    title: '数据加载中...',
  })
}

// 请求完成之后做一些事情
$http.afterRequest = function () {
  uni.hideLoading()
}
```

## [#](https://applet-base-api-t.itheima.net/docs-uni-shop/3.home.html#_3-2-轮播图区域)3.2 轮播图区域

### [#](https://applet-base-api-t.itheima.net/docs-uni-shop/3.home.html#_3-2-1-请求轮播图的数据)3.2.1 请求轮播图的数据

实现步骤：

1. 在 data 中定义轮播图的数组
2. 在 onLoad 生命周期函数中调用获取轮播图数据的方法
3. 在 methods 中定义获取轮播图数据的方法

示例代码：

```js
export default {
  data() {
    return {
      // 1. 轮播图的数据列表，默认为空数组
      swiperList: [],
    }
  },
  onLoad() {
    // 2. 在小程序页面刚加载的时候，调用获取轮播图数据的方法
    this.getSwiperList()
  },
  methods: {
    // 3. 获取轮播图数据的方法
    async getSwiperList() {
      // 3.1 发起请求
      const { data: res } = await uni.$http.get('/api/public/v1/home/swiperdata')
      // 3.2 请求失败
      if (res.meta.status !== 200) {
        return uni.showToast({
          title: '数据请求失败！',
          duration: 1500,
          icon: 'none',
        })
      }
      // 3.3 请求成功，为 data 中的数据赋值
      this.swiperList = res.message
    },
  },
}
```

### [#](https://applet-base-api-t.itheima.net/docs-uni-shop/3.home.html#_3-2-2-渲染轮播图的-ui-结构)3.2.2 渲染轮播图的 UI 结构

1. 渲染 UI 结构：

   ```xml
   <template>
     <view>
       <!-- 轮播图区域 -->
       <swiper :indicator-dots="true" :autoplay="true" :interval="3000" :duration="1000" :circular="true">
         <!-- 循环渲染轮播图的 item 项 -->
         <swiper-item v-for="(item, i) in swiperList" :key="i">
           <view class="swiper-item">
             <!-- 动态绑定图片的 src 属性 -->
             <image :src="item.image_src"></image>
           </view>
         </swiper-item>
       </swiper>
     </view>
   </template>
   ```
2. 美化 UI 结构：

   ```scss
   <style lang="scss">
   swiper {
    height: 330rpx;

    .swiper-item,
    image {
      width: 100%;
      height: 100%;
    }
   }
   </style>
   ```

### [#](https://applet-base-api-t.itheima.net/docs-uni-shop/3.home.html#_3-2-3-配置小程序分包)3.2.3 配置小程序分包

> 分包可以减少小程序首次启动时的加载时间

为此，我们在项目中，把 tabBar 相关的 4 个页面放到主包中，其它页面（例如：商品详情页、商品列表页）放到分包中。在 uni-app 项目中，配置分包的步骤如下：

1. 在项目根目录中，创建分包的根目录，命名为 `subpkg`​
2. 在 `pages.json` 中，和 `pages` 节点平级的位置声明 `subPackages` 节点，用来定义分包相关的结构：

   ```json
   {
     "pages": [
       {
         "path": "pages/home/home",
         "style": {}
       },
       {
         "path": "pages/cate/cate",
         "style": {}
       },
       {
         "path": "pages/cart/cart",
         "style": {}
       },
       {
         "path": "pages/my/my",
         "style": {}
       }
     ],
     "subPackages": [
       {
         "root": "subpkg",
         "pages": []
       }
     ]
   }
   ```
3. 在 `subpkg` 目录上鼠标右键，点击 `新建页面` 选项，并填写页面的相关信息：
   ![](https://applet-base-api-t.itheima.net/docs-uni-shop/2-2.e5e761c8.png)

### [#](https://applet-base-api-t.itheima.net/docs-uni-shop/3.home.html#_3-2-4-点击轮播图跳转到商品详情页面)3.2.4 点击轮播图跳转到商品详情页面

将 `<swiper-item></swiper-item>` 节点内的 `view` 组件，改造为 `navigator` 导航组件，并动态绑定 `url 属性` 的值。

1. 改造之前的 UI 结构：

   ```xml
   <swiper-item v-for="(item, i) in swiperList" :key="i">
     <view class="swiper-item">
       <!-- 动态绑定图片的 src 属性 -->
       <image :src="item.image_src"></image>
     </view>
   </swiper-item>
   ```
2. 改造之后的 UI 结构：

   ```xml
   <swiper-item v-for="(item, i) in swiperList" :key="i">
       <navigator class="swiper-item" :url="'/subpkg/goods_detail/goods_detail?goods_id=' + item.goods_id">
         <!-- 动态绑定图片的 src 属性 -->
         <image :src="item.image_src"></image>
       </navigator>
   </swiper-item>
   ```

### [#](https://applet-base-api-t.itheima.net/docs-uni-shop/3.home.html#_3-2-5-封装-uni-showmsg-方法)3.2.5 封装 uni.\$showMsg() 方法

当数据请求失败之后，经常需要调用 `uni.showToast({ /* 配置对象 */ })` 方法来提示用户。此时，可以在全局封装一个 `uni.$showMsg()` 方法，来简化 `uni.showToast()` 方法的调用。具体的改造步骤如下：

1. 在 `main.js` 中，为 `uni` 对象挂载自定义的 `$showMsg()` 方法：

   ```js
   // 封装的展示消息提示的方法
   uni.$showMsg = function (title = '数据加载失败！', duration = 1500) {
     uni.showToast({
       title,
       duration,
       icon: 'none',
     })
   }
   ```
2. 今后，在需要提示消息的时候，直接调用 `uni.$showMsg()` 方法即可：

   ```js
   async getSwiperList() {
      const { data: res } = await uni.$http.get('/api/public/v1/home/swiperdata')
      if (res.meta.status !== 200) return uni.$showMsg()
      this.swiperList = res.message
   }
   ```

## [#](https://applet-base-api-t.itheima.net/docs-uni-shop/3.home.html#_3-3-分类导航区域)3.3 分类导航区域

### [#](https://applet-base-api-t.itheima.net/docs-uni-shop/3.home.html#_3-3-1-获取分类导航的数据)3.3.1 获取分类导航的数据

实现思路：

1. 定义 data 数据
2. 在 onLoad 中调用获取数据的方法
3. 在 methods 中定义获取数据的方法

示例代码如下：

```js
export default {
  data() {
    return {
      // 1. 分类导航的数据列表
      navList: [],
    }
  },
  onLoad() {
    // 2. 在 onLoad 中调用获取数据的方法
    this.getNavList()
  },
  methods: {
    // 3. 在 methods 中定义获取数据的方法
    async getNavList() {
      const { data: res } = await uni.$http.get('/api/public/v1/home/catitems')
      if (res.meta.status !== 200) return uni.$showMsg()
      this.navList = res.message
    },
  },
}
```

### [#](https://applet-base-api-t.itheima.net/docs-uni-shop/3.home.html#_3-3-2-渲染分类导航的-ui-结构)3.3.2 渲染分类导航的 UI 结构

1. 定义如下的 UI 结构：

   ```xml
   <!-- 分类导航区域 -->
   <view class="nav-list">
      <view class="nav-item" v-for="(item, i) in navList" :key="i">
        <image :src="item.image_src" class="nav-img"></image>
      </view>
   </view>
   ```
2. 通过如下的样式美化页面结构：

   ```scss
   .nav-list {
     display: flex;
     justify-content: space-around;
     margin: 15px 0;

     .nav-img {
       width: 128rpx;
       height: 140rpx;
     }
   }
   ```

### [#](https://applet-base-api-t.itheima.net/docs-uni-shop/3.home.html#_3-3-2-点击第一项，切换到分类页面)3.3.2 点击第一项，切换到分类页面

1. 为 `nav-item` 绑定点击事件处理函数：

   ```js
   <!-- 分类导航区域 -->
   <view class="nav-list">
     <view class="nav-item" v-for="(item, i) in navList" :key="i" @click="navClickHandler(item)">
       <image :src="item.image_src" class="nav-img"></image>
     </view>
   </view>
   ```
2. 定义 `navClickHandler` 事件处理函数：

   ```js
   // nav-item 项被点击时候的事件处理函数
   navClickHandler(item) {
     // 判断点击的是哪个 nav
     if (item.name === '分类') {
       uni.switchTab({
         url: '/pages/cate/cate'
       })
     }
   }
   ```

## [#](https://applet-base-api-t.itheima.net/docs-uni-shop/3.home.html#_3-4-楼层区域)3.4 楼层区域

### [#](https://applet-base-api-t.itheima.net/docs-uni-shop/3.home.html#_3-4-1-获取楼层数据)3.4.1 获取楼层数据

实现思路：

1. 定义 data 数据
2. 在 onLoad 中调用获取数据的方法
3. 在 methods 中定义获取数据的方法

示例代码如下：

```js
export default {
  data() {
    return {
      // 1. 楼层的数据列表
      floorList: [],
    }
  },
  onLoad() {
    // 2. 在 onLoad 中调用获取楼层数据的方法
    this.getFloorList()
  },
  methods: {
    // 3. 定义获取楼层列表数据的方法
    async getFloorList() {
      const { data: res } = await uni.$http.get('/api/public/v1/home/floordata')
      if (res.meta.status !== 200) return uni.$showMsg()
      this.floorList = res.message
    },
  },
}
```

### [#](https://applet-base-api-t.itheima.net/docs-uni-shop/3.home.html#_3-4-2-渲染楼层的标题)3.4.2 渲染楼层的标题

1. 定义如下的 UI 结构：

   ```xml
   <!-- 楼层区域 -->
   <view class="floor-list">
     <!-- 楼层 item 项 -->
     <view class="floor-item" v-for="(item, i) in floorList" :key="i">
       <!-- 楼层标题 -->
       <image :src="item.floor_title.image_src" class="floor-title"></image>
     </view>
   </view>
   ```
2. 美化楼层标题的样式：

   ```scss
   .floor-title {
     height: 60rpx;
     width: 100%;
     display: flex;
   }
   ```

### [#](https://applet-base-api-t.itheima.net/docs-uni-shop/3.home.html#_3-4-3-渲染楼层里的图片)3.4.3 渲染楼层里的图片

1. 定义楼层图片区域的 UI 结构：

   ```xml
   <!-- 楼层图片区域 -->
   <view class="floor-img-box">
     <!-- 左侧大图片的盒子 -->
     <view class="left-img-box">
       <image :src="item.product_list[0].image_src" :style="{width: item.product_list[0].image_width + 'rpx'}" mode="widthFix"></image>
     </view>
     <!-- 右侧 4 个小图片的盒子 -->
     <view class="right-img-box">
       <view class="right-img-item" v-for="(item2, i2) in item.product_list" :key="i2" v-if="i2 !== 0">
         <image :src="item2.image_src" mode="widthFix" :style="{width: item2.image_width + 'rpx'}"></image>
       </view>
     </view>
   </view>
   ```
2. 美化楼层图片区域的样式：

   ```scss
   .right-img-box {
     display: flex;
     flex-wrap: wrap;
     justify-content: space-around;
   }

   .floor-img-box {
     display: flex;
     padding-left: 10rpx;
   }
   ```

### [#](https://applet-base-api-t.itheima.net/docs-uni-shop/3.home.html#_3-4-4-点击楼层图片跳转到商品列表页)3.4.4 点击楼层图片跳转到商品列表页

1. 在 `subpkg` 分包中，新建 `goods_list` 页面
   ![](https://applet-base-api-t.itheima.net/docs-uni-shop/2-3.de0b01ae.png)
2. 楼层数据请求成功之后，通过双层 `forEach` 循环，处理 URL 地址：

   ```js
   // 获取楼层列表数据
   async getFloorList() {
     const { data: res } = await uni.$http.get('/api/public/v1/home/floordata')
     if (res.meta.status !== 200) return uni.$showMsg()

     // 通过双层 forEach 循环，处理 URL 地址
     res.message.forEach(floor => {
       floor.product_list.forEach(prod => {
         prod.url = '/subpkg/goods_list/goods_list?' + prod.navigator_url.split('?')[1]
       })
     })

     this.floorList = res.message
   }
   ```
3. 把图片外层的 `view` 组件，改造为 `navigator` 组件，并动态绑定 `url 属性` 的值：

   ```xml
   <!-- 楼层图片区域 -->
   <view class="floor-img-box">
     <!-- 左侧大图片的盒子 -->
     <navigator class="left-img-box" :url="item.product_list[0].url">
       <image :src="item.product_list[0].image_src" :style="{width: item.product_list[0].image_width + 'rpx'}" mode="widthFix"></image>
     </navigator>
     <!-- 右侧 4 个小图片的盒子 -->
     <view class="right-img-box">
       <navigator class="right-img-item" v-for="(item2, i2) in item.product_list" :key="i2" v-if="i2 !== 0" :url="item2.url">
         <image :src="item2.image_src" mode="widthFix" :style="{width: item2.image_width + 'rpx'}"></image>
       </navigator>
     </view>
   </view>
   ```

## [#](https://applet-base-api-t.itheima.net/docs-uni-shop/3.home.html#_3-5-分支的合并与提交)3.5 分支的合并与提交

1. 将本地的 home 分支进行本地的 commit 提交：

   ```bash
   git add .
   git commit -m "完成了 home 首页的开发"
   ```
2. 将本地的 home 分支推送到远程仓库进行保存：

   ```bash
   git push -u origin home
   ```
3. 将本地的 home 分支合并到本地的 master 分支：

   ```bash
   git checkout master
   git merge home
   ```
4. 删除本地的 home 分支：

   ```bash
   git branch -d home
   ```

# 4. 分类

## [#](https://applet-base-api-t.itheima.net/docs-uni-shop/4.cate.html#_4-0-创建-cate-分支)4.0 创建 cate 分支

运行如下的命令，基于 master 分支在本地创建 cate 子分支，用来开发分类页面相关的功能：

```bash
git checkout -b cate
```

## [#](https://applet-base-api-t.itheima.net/docs-uni-shop/4.cate.html#_4-1-渲染分类页面的基本结构)4.1 渲染分类页面的基本结构

1. 定义页面结构如下：

   ```xml
   <template>
     <view>
       <view class="scroll-view-container">
         <!-- 左侧的滚动视图区域 -->
         <scroll-view class="left-scroll-view" scroll-y :style="{height: wh + 'px'}">
           <view class="left-scroll-view-item active">xxx</view>
           <view class="left-scroll-view-item">xxx</view>
           <view class="left-scroll-view-item">xxx</view>
           <view class="left-scroll-view-item">xxx</view>
           <view class="left-scroll-view-item">xxx</view>
           <view class="left-scroll-view-item">多复制一些节点，演示纵向滚动效果...</view>
         </scroll-view>
         <!-- 右侧的滚动视图区域 -->
         <scroll-view class="right-scroll-view" scroll-y :style="{height: wh + 'px'}">
           <view class="left-scroll-view-item">zzz</view>
           <view class="left-scroll-view-item">zzz</view>
           <view class="left-scroll-view-item">zzz</view>
           <view class="left-scroll-view-item">zzz</view>
           <view class="left-scroll-view-item">多复制一些节点，演示纵向滚动效果</view>
         </scroll-view>
       </view>
     </view>
   </template>
   ```
2. 动态计算窗口的剩余高度：

   ```js
   <script>
     export default {
       data() {
         return {
           // 窗口的可用高度 = 屏幕高度 - navigationBar高度 - tabBar 高度
           wh: 0
         };
       },
       onLoad() {
         // 获取当前系统的信息
         const sysInfo = uni.getSystemInfoSync()
         // 为 wh 窗口可用高度动态赋值
         this.wh = sysInfo.windowHeight
       }
     }
   </script>
   ```
3. 美化页面结构：

   ```scss
   .scroll-view-container {
     display: flex;

     .left-scroll-view {
       width: 120px;

       .left-scroll-view-item {
         line-height: 60px;
         background-color: #f7f7f7;
         text-align: center;
         font-size: 12px;

         // 激活项的样式
         &.active {
           background-color: #ffffff;
           position: relative;

           // 渲染激活项左侧的红色指示边线
           &::before {
             content: ' ';
             display: block;
             width: 3px;
             height: 30px;
             background-color: #c00000;
             position: absolute;
             left: 0;
             top: 50%;
             transform: translateY(-50%);
           }
         }
       }
     }
   }
   ```

## [#](https://applet-base-api-t.itheima.net/docs-uni-shop/4.cate.html#_4-2-获取分类数据)4.2 获取分类数据

1. 在 data 中定义分类数据节点：

   ```js
   data() {
     return {
       // 分类数据列表
       cateList: []
     }
   }
   ```
2. 调用获取分类列表数据的方法：

   ```js
   onLoad() {
     // 调用获取分类列表数据的方法
     this.getCateList()
   }
   ```
3. 定义获取分类列表数据的方法：

   ```js
   methods: {
     async getCateList() {
       // 发起请求
       const { data: res } = await uni.$http.get('/api/public/v1/categories')
       // 判断是否获取失败
       if (res.meta.status !== 200) return uni.$showMsg()
       // 转存数据
       this.cateList = res.message
     }
   }
   ```

## [#](https://applet-base-api-t.itheima.net/docs-uni-shop/4.cate.html#_4-3-动态渲染左侧的一级分类列表)4.3 动态渲染左侧的一级分类列表

1. 循环渲染列表结构：

   ```xml
   <!-- 左侧的滚动视图区域 -->
   <scroll-view class="left-scroll-view" scroll-y :style="{height: wh + 'px'}">
     <block v-for="(item, i) in cateList" :key="i">
       <view class="left-scroll-view-item">{{item.cat_name}}</view>
     </block>
   </scroll-view>
   ```
2. 在 data 中定义默认选中项的索引：

   ```js
   data() {
     return {
       // 当前选中项的索引，默认让第一项被选中
       active: 0
     }
   }
   ```
3. 循环渲染结构时，为选中项动态添加 `.active` 类名：

   ```xml
   <block v-for="(item, i) in cateList" :key="i">
     <view :class="['left-scroll-view-item', i === active ? 'active' : '']">{{item.cat_name}}</view>
   </block>
   ```
4. 为一级分类的 Item 项绑定点击事件处理函数 `activeChanged`：

   ```xml
   <block v-for="(item, i) in cateList" :key="i">
     <view :class="['left-scroll-view-item', i === active ? 'active' : '']" @click="activeChanged(i)">{{item.cat_name}}</view>
   </block>
   ```
5. 定义 `activeChanged` 事件处理函数，动态修改选中项的索引：

   ```js
   methods: {
     // 选中项改变的事件处理函数
     activeChanged(i) {
       this.active = i
     }
   }
   ```

## [#](https://applet-base-api-t.itheima.net/docs-uni-shop/4.cate.html#_4-4-动态渲染右侧的二级分类列表)4.4 动态渲染右侧的二级分类列表

1. 在 `data` 中定义二级分类列表的数据节点：

   ```js
   data() {
     return {
       // 二级分类列表
       cateLevel2: []
     }
   }
   ```
2. 修改 `getCateList` 方法，在请求到数据之后，为二级分类列表数据赋值：

   ```js
   async getCateList() {
     const { data: res } = await uni.$http.get('/api/public/v1/categories')
     if (res.meta.status !== 200) return uni.$showMsg()
     this.cateList = res.message
     // 为二级分类赋值
     this.cateLevel2 = res.message[0].children
   }
   ```
3. 修改 `activeChanged` 方法，在一级分类选中项改变之后，为二级分类列表数据重新赋值：

   ```js
   activeChanged(i) {
     this.active = i
     // 为二级分类列表重新赋值
     this.cateLevel2 = this.cateList[i].children
   }
   ```
4. 循环渲染右侧二级分类列表的 UI 结构：

   ```xml
   <!-- 右侧的滚动视图区域 -->
   <scroll-view class="right-scroll-view" scroll-y :style="{height: wh + 'px'}">
     <view class="cate-lv2" v-for="(item2, i2) in cateLevel2" :key="i2">
       <view class="cate-lv2-title">/ {{item2.cat_name}} /</view>
     </view>
   </scroll-view>
   ```
5. 美化二级分类的标题样式：

   ```scss
   .cate-lv2-title {
     font-size: 12px;
     font-weight: bold;
     text-align: center;
     padding: 15px 0;
   }
   ```

## [#](https://applet-base-api-t.itheima.net/docs-uni-shop/4.cate.html#_4-5-动态渲染右侧的三级分类列表)4.5 动态渲染右侧的三级分类列表

1. 在二级分类的 `<view>` 组件中，循环渲染三级分类的列表结构：

   ```xml
   <!-- 右侧的滚动视图区域 -->
   <scroll-view class="right-scroll-view" scroll-y :style="{height: wh + 'px'}">
     <view class="cate-lv2" v-for="(item2, i2) in cateLevel2" :key="i2">
       <view class="cate-lv2-title">/ {{item2.cat_name}} /</view>
       <!-- 动态渲染三级分类的列表数据 -->
       <view class="cate-lv3-list">
         <!-- 三级分类 Item 项 -->
         <view class="cate-lv3-item" v-for="(item3, i3) in item2.children" :key="i3">
           <!-- 图片 -->
           <image :src="item3.cat_icon"></image>
           <!-- 文本 -->
           <text>{{item3.cat_name}}</text>
         </view>
       </view>
     </view>
   </scroll-view>
   ```
2. 美化三级分类的样式：

   ```scss
   .cate-lv3-list {
     display: flex;
     flex-wrap: wrap;

     .cate-lv3-item {
       width: 33.33%;
       margin-bottom: 10px;
       display: flex;
       flex-direction: column;
       align-items: center;

       image {
         width: 60px;
         height: 60px;
       }

       text {
         font-size: 12px;
       }
     }
   }
   ```

## [#](https://applet-base-api-t.itheima.net/docs-uni-shop/4.cate.html#_4-6-切换一级分类后重置滚动条的位置)4.6 切换一级分类后重置滚动条的位置

1. 在 data 中定义 `滚动条距离顶部的距离`：

   ```js
   data() {
     return {
       // 滚动条距离顶部的距离
       scrollTop: 0
     }
   }
   ```
2. 动态为右侧的 `<scroll-view>` 组件绑定 `scroll-top` 属性的值：

   ```xml
   <!-- 右侧的滚动视图区域 -->
   <scroll-view class="right-scroll-view" scroll-y :style="{height: wh + 'px'}" :scroll-top="scrollTop"></scroll-view>
   ```
3. 切换一级分类时，动态设置 `scrollTop` 的值：

   ```js
   // 选中项改变的事件处理函数
   activeChanged(i) {
     this.active = i
     this.cateLevel2 = this.cateList[i].children

     // 让 scrollTop 的值在 0 与 1 之间切换
     this.scrollTop = this.scrollTop === 0 ? 1 : 0

     // 可以简化为如下的代码：
     // this.scrollTop = this.scrollTop ? 0 : 1
   }
   ```

## [#](https://applet-base-api-t.itheima.net/docs-uni-shop/4.cate.html#_4-7-点击三级分类跳转到商品列表页面)4.7 点击三级分类跳转到商品列表页面

1. 为三级分类的 Item 项绑定点击事件处理函数如下：

   ```xml
   <view class="cate-lv3-item" v-for="(item3, i3) in item2.children" :key="i3" @click="gotoGoodsList(item3)">
     <image :src="item3.cat_icon"></image>
     <text>{{item3.cat_name}}</text>
   </view>
   ```
2. 定义事件处理函数如下：

   ```js
   // 点击三级分类项跳转到商品列表页面
   gotoGoodsList(item3) {
     uni.navigateTo({
       url: '/subpkg/goods_list/goods_list?cid=' + item3.cat_id
     })
   }
   ```

## [#](https://applet-base-api-t.itheima.net/docs-uni-shop/4.cate.html#_4-8-分支的合并与提交)4.8 分支的合并与提交

1. 将 `cate` 分支进行本地提交：

   ```bash
   git add .
   git commit -m "完成了分类页面的开发"
   ```
2. 将本地的 `cate` 分支推送到码云：

   ```bash
   git push -u origin cate
   ```
3. 将本地 `cate` 分支中的代码合并到 `master` 分支：

   ```bash
   git checkout master
   git merge cate
   git push
   ```
4. 删除本地的 `cate` 分支：

   ```bash
   git branch -d cate
   ```

# 5. 搜索

## [#](https://applet-base-api-t.itheima.net/docs-uni-shop/5.search.html#_5-0-创建-search-分支)5.0 创建 search 分支

运行如下的命令，基于 master 分支在本地创建 search 子分支，用来开发搜索相关的功能：

```bash
git checkout -b search
```

## [#](https://applet-base-api-t.itheima.net/docs-uni-shop/5.search.html#_5-1-自定义搜索组件)5.1 自定义搜索组件

### [#](https://applet-base-api-t.itheima.net/docs-uni-shop/5.search.html#_5-1-1-自定义-my-search-组件)5.1.1 自定义 my-search 组件

1. 在项目根目录的 `components` 目录上，鼠标右键，选择 `新建组件`，填写组件信息后，最后点击 `创建` 按钮：
   ![](https://applet-base-api-t.itheima.net/docs-uni-shop/5-1.25ab714d.png)
2. 在分类页面的 UI 结构中，直接以标签的形式使用 `my-search` 自定义组件：

   ```xml
   <!-- 使用自定义的搜索组件 -->
   <my-search></my-search>
   ```
3. 定义 `my-search` 组件的 UI 结构如下：

   ```xml
   <template>
     <view class="my-search-container">
       <!-- 使用 view 组件模拟 input 输入框的样式 -->
       <view class="my-search-box">
         <uni-icons type="search" size="17"></uni-icons>
         <text class="placeholder">搜索</text>
       </view>
     </view>
   </template>
   ```

   > 注意：在当前组件中，我们使用 view 组件模拟 input 输入框的效果；并不会在页面上渲染真正的 input 输入框
   >
4. 美化自定义 search 组件的样式：

   ```scss
   .my-search-container {
     background-color: #c00000;
     height: 50px;
     padding: 0 10px;
     display: flex;
     align-items: center;
   }

   .my-search-box {
     height: 36px;
     background-color: #ffffff;
     border-radius: 15px;
     width: 100%;
     display: flex;
     align-items: center;
     justify-content: center;

     .placeholder {
       font-size: 15px;
       margin-left: 5px;
     }
   }
   ```
5. 由于自定义的 `my-search` 组件高度为 `50px`，因此，需要重新计算分类页面窗口的可用高度：

   ```js
   onLoad() {
     const sysInfo = uni.getSystemInfoSync()
     // 可用高度 = 屏幕高度 - navigationBar高度 - tabBar高度 - 自定义的search组件高度
     this.wh = sysInfo.windowHeight - 50
   }
   ```

### [#](https://applet-base-api-t.itheima.net/docs-uni-shop/5.search.html#_5-1-2-通过自定义属性增强组件的通用性)5.1.2 通过自定义属性增强组件的通用性

为了增强组件的通用性，我们允许使用者自定义搜索组件的 `背景颜色` 和 `圆角尺寸`。

1. 通过 `props` 定义 `bgcolor` 和 `radius` 两个属性，并指定值类型和属性默认值：

   ```js
   props: {
     // 背景颜色
     bgcolor: {
       type: String,
       default: '#C00000'
     },
     // 圆角尺寸
     radius: {
       type: Number,
       // 单位是 px
       default: 18
     }
   }
   ```
2. 通过属性绑定的形式，为 `.my-search-container` 盒子和 `.my-search-box` 盒子动态绑定 `style` 属性：

   ```xml
   <view class="my-search-container" :style="{'background-color': bgcolor}">
     <view class="my-search-box" :style="{'border-radius': radius + 'px'}">
       <uni-icons type="search" size="17"></uni-icons>
       <text class="placeholder">搜索</text>
     </view>
   </view>
   ```
3. 移除对应 `scss` 样式中的 `背景颜色` 和 `圆角尺寸`：

   ```scss
   .my-search-container {
     // 移除背景颜色，改由 props 属性控制
     // background-color: #C00000;
     height: 50px;
     padding: 0 10px;
     display: flex;
     align-items: center;
   }

   .my-search-box {
     height: 36px;
     background-color: #ffffff;
     // 移除圆角尺寸，改由 props 属性控制
     // border-radius: 15px;
     width: 100%;
     display: flex;
     align-items: center;
     justify-content: center;

     .placeholder {
       font-size: 15px;
       margin-left: 5px;
     }
   }
   ```

### [#](https://applet-base-api-t.itheima.net/docs-uni-shop/5.search.html#_5-1-3-为自定义组件封装-click-事件)5.1.3 为自定义组件封装 click 事件

1. 在 `my-search` 自定义组件内部，给类名为 `.my-search-box` 的 `view` 绑定 `click` 事件处理函数：

   ```xml
   <view class="my-search-box" :style="{'border-radius': radius + 'px'}" @click="searchBoxHandler">
     <uni-icons type="search" size="17"></uni-icons>
     <text class="placeholder">搜索</text>
   </view>
   ```
2. 在 `my-search` 自定义组件的 `methods` 节点中，声明事件处理函数如下：

   ```js
   methods: {
     // 点击了模拟的 input 输入框
     searchBoxHandler() {
       // 触发外界通过 @click 绑定的 click 事件处理函数
       this.$emit('click')
     }
   }
   ```
3. 在分类页面中使用 `my-search` 自定义组件时，即可通过 `@click` 为其绑定点击事件处理函数：

   ```xml
   <!-- 使用自定义的搜索组件 -->
   <my-search @click="gotoSearch"></my-search>
   ```

   同时在分类页面中，定义 `gotoSearch` 事件处理函数如下：

   ```js
   methods: {
      // 跳转到分包中的搜索页面
      gotoSearch() {
        uni.navigateTo({
          url: '/subpkg/search/search'
        })
      }
   }
   ```

### [#](https://applet-base-api-t.itheima.net/docs-uni-shop/5.search.html#_5-1-4-实现首页搜索组件的吸顶效果)5.1.4 实现首页搜索组件的吸顶效果

1. 在 home 首页定义如下的 UI 结构：

   ```xml
   <!-- 使用自定义的搜索组件 -->
   <view class="search-box">
     <my-search @click="gotoSearch"></my-search>
   </view>
   ```
2. 在 home 首页定义如下的事件处理函数：

   ```js
   gotoSearch() {
     uni.navigateTo({
       url: '/subpkg/search/search'
     })
   }
   ```
3. 通过如下的样式实现吸顶的效果：

   ```scss
   .search-box {
     // 设置定位效果为“吸顶”
     position: sticky;
     // 吸顶的“位置”
     top: 0;
     // 提高层级，防止被轮播图覆盖
     z-index: 999;
   }
   ```

## [#](https://applet-base-api-t.itheima.net/docs-uni-shop/5.search.html#_5-2-搜索建议)5.2 搜索建议

### [#](https://applet-base-api-t.itheima.net/docs-uni-shop/5.search.html#_5-2-1-渲染搜索页面的基本结构)5.2.1 渲染搜索页面的基本结构

1. 定义如下的 UI 结构：

   ```xml
   <view class="search-box">
     <!-- 使用 uni-ui 提供的搜索组件 -->
     <uni-search-bar @input="input" :radius="100" cancelButton="none"></uni-search-bar>
   </view>
   ```
2. 修改 `components -> uni-search-bar -> uni-search-bar.vue` 组件，将默认的白色搜索背景改为 `#C00000` 的红色背景：

   ```css
   .uni-searchbar {
     /* #ifndef APP-NVUE */
     display: flex;
     /* #endif */
     flex-direction: row;
     position: relative;
     padding: 16rpx;
     /* 将默认的 #FFFFFF 改为 #C00000 */
     background-color: #c00000;
   }
   ```
3. 实现搜索框的吸顶效果：

   ```scss
   .search-box {
     position: sticky;
     top: 0;
     z-index: 999;
   }
   ```
4. 定义如下的 input 事件处理函数：

   ```js
   methods: {
     input(e) {
       // e.value 是最新的搜索内容
       console.log(e.value)
     }
   }
   ```

### [#](https://applet-base-api-t.itheima.net/docs-uni-shop/5.search.html#_5-2-2-实现搜索框自动获取焦点)5.2.2 实现搜索框自动获取焦点

1. 修改 `components -> uni-search-bar -> uni-search-bar.vue` 组件，把 data 数据中的 `show` 和 `showSync` 的值，从默认的 `false` 改为 `true` 即可：

   ```js
   data() {
     return {
       show: true,
       showSync: true,
       searchVal: ""
     }
   }
   ```
2. 使用手机扫码预览，即可在真机上查看效果。

### [#](https://applet-base-api-t.itheima.net/docs-uni-shop/5.search.html#_5-2-3-实现搜索框的防抖处理)5.2.3 实现搜索框的防抖处理

1. 在 data 中定义防抖的延时器 timerId 如下：

   ```js
   data() {
     return {
       // 延时器的 timerId
       timer: null,
       // 搜索关键词
       kw: ''
     }
   }
   ```
2. 修改 `input` 事件处理函数如下：

   ```js
   input(e) {
     // 清除 timer 对应的延时器
     clearTimeout(this.timer)
     // 重新启动一个延时器，并把 timerId 赋值给 this.timer
     this.timer = setTimeout(() => {
       // 如果 500 毫秒内，没有触发新的输入事件，则为搜索关键词赋值
       this.kw = e.value
       console.log(this.kw)
     }, 500)
   }
   ```

### [#](https://applet-base-api-t.itheima.net/docs-uni-shop/5.search.html#_5-2-4-根据关键词查询搜索建议列表)5.2.4 根据关键词查询搜索建议列表

1. 在 data 中定义如下的数据节点，用来存放搜索建议的列表数据：

   ```js
   data() {
     return {
       // 搜索结果列表
       searchResults: []
     }
   }
   ```
2. 在防抖的 `setTimeout` 中，调用 `getSearchList` 方法获取搜索建议列表：

   ```js
   this.timer = setTimeout(() => {
     this.kw = e.value
     // 根据关键词，查询搜索建议列表
     this.getSearchList()
   }, 500)
   ```
3. 在 `methods` 中定义 `getSearchList` 方法如下：

   ```js
   // 根据搜索关键词，搜索商品建议列表
   async getSearchList() {
     // 判断关键词是否为空
     if (this.kw === '') {
       this.searchResults = []
       return
     }
     // 发起请求，获取搜索建议列表
     const { data: res } = await uni.$http.get('/api/public/v1/goods/qsearch', { query: this.kw })
     if (res.meta.status !== 200) return uni.$showMsg()
     this.searchResults = res.message
   }
   ```

### [#](https://applet-base-api-t.itheima.net/docs-uni-shop/5.search.html#_5-2-5-渲染搜索建议列表)5.2.5 渲染搜索建议列表

1. 定义如下的 UI 结构：

   ```xml
   <!-- 搜索建议列表 -->
   <view class="sugg-list">
     <view class="sugg-item" v-for="(item, i) in searchResults" :key="i" @click="gotoDetail(item.goods_id)">
       <view class="goods-name">{{item.goods_name}}</view>
       <uni-icons type="arrowright" size="16"></uni-icons>
     </view>
   </view>
   ```
2. 美化搜索建议列表：

   ```scss
   .sugg-list {
     padding: 0 5px;

     .sugg-item {
       font-size: 12px;
       padding: 13px 0;
       border-bottom: 1px solid #efefef;
       display: flex;
       align-items: center;
       justify-content: space-between;

       .goods-name {
         // 文字不允许换行（单行文本）
         white-space: nowrap;
         // 溢出部分隐藏
         overflow: hidden;
         // 文本溢出后，使用 ... 代替
         text-overflow: ellipsis;
         margin-right: 3px;
       }
     }
   }
   ```
3. 点击搜索建议的 Item 项，跳转到商品详情页面：

   ```js
   gotoDetail(goods_id) {
     uni.navigateTo({
       // 指定详情页面的 URL 地址，并传递 goods_id 参数
       url: '/subpkg/goods_detail/goods_detail?goods_id=' + goods_id
     })
   }
   ```

## [#](https://applet-base-api-t.itheima.net/docs-uni-shop/5.search.html#_5-3-搜索历史)5.3 搜索历史

### [#](https://applet-base-api-t.itheima.net/docs-uni-shop/5.search.html#_5-3-1-渲染搜索历史记录的基本结构)5.3.1 渲染搜索历史记录的基本结构

1. 在 data 中定义搜索历史的`假数据`：

   ```js
   data() {
     return {
       // 搜索关键词的历史记录
       historyList: ['a', 'app', 'apple']
     }
   }
   ```
2. 渲染搜索历史区域的 UI 结构：

   ```xml
   <!-- 搜索历史 -->
   <view class="history-box">
     <!-- 标题区域 -->
     <view class="history-title">
       <text>搜索历史</text>
       <uni-icons type="trash" size="17"></uni-icons>
     </view>
     <!-- 列表区域 -->
     <view class="history-list">
       <uni-tag :text="item" v-for="(item, i) in historyList" :key="i"></uni-tag>
     </view>
   </view>
   ```
3. 美化搜索历史区域的样式：

   ```scss
   .history-box {
     padding: 0 5px;

     .history-title {
       display: flex;
       justify-content: space-between;
       align-items: center;
       height: 40px;
       font-size: 13px;
       border-bottom: 1px solid #efefef;
     }

     .history-list {
       display: flex;
       flex-wrap: wrap;

       .uni-tag {
         margin-top: 5px;
         margin-right: 5px;
       }
     }
   }
   ```

### [#](https://applet-base-api-t.itheima.net/docs-uni-shop/5.search.html#_5-3-2-实现搜索建议和搜索历史的按需展示)5.3.2 实现搜索建议和搜索历史的按需展示

1. 当搜索结果列表的长度`不为 0`的时候（`searchResults.length !== 0`），需要展示搜索建议区域，隐藏搜索历史区域
2. 当搜索结果列表的长度`等于 0`的时候（`searchResults.length === 0`），需要隐藏搜索建议区域，展示搜索历史区域
3. 使用 `v-if` 和 `v-else` 控制这两个区域的显示和隐藏，示例代码如下：

   ```xml
   <!-- 搜索建议列表 -->
   <view class="sugg-list" v-if="searchResults.length !== 0">
     <!-- 省略其它代码... -->
   </view>

   <!-- 搜索历史 -->
   <view class="history-box" v-else>
     <!-- 省略其它代码... -->
   </view>
   ```

### [#](https://applet-base-api-t.itheima.net/docs-uni-shop/5.search.html#_5-3-3-将搜索关键词存入-historylist)5.3.3 将搜索关键词存入 historyList

1. 直接将搜索关键词 `push` 到 `historyList` 数组中即可

   ```js
   methods: {
     // 根据搜索关键词，搜索商品建议列表
     async getSearchList() {
       // 省略其它不必要的代码...

       // 1. 查询到搜索建议之后，调用 saveSearchHistory() 方法保存搜索关键词
       this.saveSearchHistory()
     },
     // 2. 保存搜索关键词的方法
     saveSearchHistory() {
       // 2.1 直接把搜索关键词 push 到 historyList 数组中
       this.historyList.push(this.kw)
     }
   }
   ```
2. 上述实现思路存在的问题：

   - 关键词**前后顺序**的问题（可以调用数组的 `reverse() 方法`对数组进行反转）
   - 关键词**重复**的问题（可以使用 [Set 对象]()进行**去重操作**）

### [#](https://applet-base-api-t.itheima.net/docs-uni-shop/5.search.html#_5-3-4-解决关键字前后顺序的问题)5.3.4 解决关键字前后顺序的问题

1. data 中的 `historyList` 不做任何修改，依然使用 push 进行**末尾追加**
2. 定义一个计算属性 `historys`，将 `historyList` 数组 `reverse` 反转之后，就是此计算属性的值：

   ```js
   computed: {
     historys() {
       // 注意：由于数组是引用类型，所以不要直接基于原数组调用 reverse 方法，以免修改原数组中元素的顺序
       // 而是应该新建一个内存无关的数组，再进行 reverse 反转
       return [...this.historyList].reverse()
     }
   }
   ```
3. 页面中渲染搜索关键词的时候，不再使用 data 中的 `historyList`，而是使用计算属性 `historys`：

   ```xml
   <view class="history-list">
     <uni-tag :text="item" v-for="(item, i) in historys" :key="i"></uni-tag>
   </view>
   ```

### [#](https://applet-base-api-t.itheima.net/docs-uni-shop/5.search.html#_5-3-5-解决关键词重复的问题)5.3.5 解决关键词重复的问题

1. 修改 `saveSearchHistory` 方法如下：

   ```js
   // 保存搜索关键词为历史记录
   saveSearchHistory() {
     // this.historyList.push(this.kw)

     // 1. 将 Array 数组转化为 Set 对象
     const set = new Set(this.historyList)
     // 2. 调用 Set 对象的 delete 方法，移除对应的元素
     set.delete(this.kw)
     // 3. 调用 Set 对象的 add 方法，向 Set 中添加元素
     set.add(this.kw)
     // 4. 将 Set 对象转化为 Array 数组
     this.historyList = Array.from(set)
   }
   ```

### [#](https://applet-base-api-t.itheima.net/docs-uni-shop/5.search.html#_5-3-6-将搜索历史记录持久化存储到本地)5.3.6 将搜索历史记录持久化存储到本地

1. 修改 `saveSearchHistory` 方法如下：

   ```js
   // 保存搜索关键词为历史记录
   saveSearchHistory() {
     const set = new Set(this.historyList)
     set.delete(this.kw)
     set.add(this.kw)
     this.historyList = Array.from(set)
     // 调用 uni.setStorageSync(key, value) 将搜索历史记录持久化存储到本地
     uni.setStorageSync('kw', JSON.stringify(this.historyList))
   }
   ```
2. 在 `onLoad` 生命周期函数中，加载本地存储的搜索历史记录：

   ```js
   onLoad() {
     this.historyList = JSON.parse(uni.getStorageSync('kw') || '[]')
   }
   ```

### [#](https://applet-base-api-t.itheima.net/docs-uni-shop/5.search.html#_5-3-7-清空搜索历史记录)5.3.7 清空搜索历史记录

1. 为清空的图标按钮绑定 `click` 事件：

   ```xml
   <uni-icons type="trash" size="17" @click="cleanHistory"></uni-icons>
   ```
2. 在 `methods` 中定义 `cleanHistory` 处理函数：

   ```js
   // 清空搜索历史记录
   cleanHistory() {
     // 清空 data 中保存的搜索历史
     this.historyList = []
     // 清空本地存储中记录的搜索历史
     uni.setStorageSync('kw', '[]')
   }
   ```

### [#](https://applet-base-api-t.itheima.net/docs-uni-shop/5.search.html#_5-3-8-点击搜索历史跳转到商品列表页面)5.3.8 点击搜索历史跳转到商品列表页面

1. 为搜索历史的 Item 项绑定 `click` 事件处理函数：

   ```xml
   <uni-tag :text="item" v-for="(item, i) in historys" :key="i" @click="gotoGoodsList(item)"></uni-tag>
   ```
2. 在 `methods` 中定义 `gotoGoodsList` 处理函数：

   ```js
   // 点击跳转到商品列表页面
   gotoGoodsList(kw) {
     uni.navigateTo({
       url: '/subpkg/goods_list/goods_list?query=' + kw
     })
   }
   ```

## [#](https://applet-base-api-t.itheima.net/docs-uni-shop/5.search.html#_5-4-分支的合并与提交)5.4 分支的合并与提交

1. 将 `search` 分支进行本地提交：

   ```bash
   git add .
   git commit -m "完成了搜索功能的开发"
   ```
2. 将本地的 `search` 分支推送到码云：

   ```bash
   git push -u origin search
   ```
3. 将本地 `search` 分支中的代码合并到 `master` 分支：

   ```bash
   git checkout master
   git merge search
   git push
   ```
4. 删除本地的 `search` 分支：

   ```bash
   git branch -d search
   ```

# 6. 商品列表

## [#](https://applet-base-api-t.itheima.net/docs-uni-shop/6.goodslist.html#_6-0-创建-goodslist-分支)6.0 创建 goodslist 分支

运行如下的命令，基于 master 分支在本地创建 goodslist 子分支，用来开发商品列表相关的功能：

```bash
git checkout -b search
```

## [#](https://applet-base-api-t.itheima.net/docs-uni-shop/6.goodslist.html#_6-1-定义请求参数对象)6.1 定义请求参数对象

1. 为了方便发起请求获取商品列表的数据，我们要根据接口的要求，事先定义一个**请求参数对象**：

   ```js
   data() {
     return {
       // 请求参数对象
       queryObj: {
         // 查询关键词
         query: '',
         // 商品分类Id
         cid: '',
         // 页码值
         pagenum: 1,
         // 每页显示多少条数据
         pagesize: 10
       }
     }
   }
   ```
2. 将页面跳转时**携带的参数**，转存到 `queryObj` 对象中：

   ```js
   onLoad(options) {
     // 将页面参数转存到 this.queryObj 对象中
     this.queryObj.query = options.query || ''
     this.queryObj.cid = options.cid || ''
   }
   ```
3. 为了方便开发商品分类页面，建议大家通过**微信开发者工具**，新建商品列表页面的**编译模式**：
   ![](assets/image-20250401193026-y0hdp8d.png)

## [#](https://applet-base-api-t.itheima.net/docs-uni-shop/6.goodslist.html#_6-2-获取商品列表数据)6.2 获取商品列表数据

1. 在 data 中新增如下的数据节点：

   ```js
   data() {
     return {
       // 商品列表的数据
       goodsList: [],
       // 总数量，用来实现分页
       total: 0
     }
   }
   ```
2. 在 `onLoad` 生命周期函数中，调用 `getGoodsList` 方法获取商品列表数据：

   ```js
   onLoad(options) {
     // 调用获取商品列表数据的方法
     this.getGoodsList()
   }
   ```
3. 在 `methods` 节点中，声明 `getGoodsList` 方法如下：

   ```js
   methods: {
     // 获取商品列表数据的方法
     async getGoodsList() {
       // 发起请求
       const { data: res } = await uni.$http.get('/api/public/v1/goods/search', this.queryObj)
       if (res.meta.status !== 200) return uni.$showMsg()
       // 为数据赋值
       this.goodsList = res.message.goods
       this.total = res.message.total
     }
   }
   ```

## [#](https://applet-base-api-t.itheima.net/docs-uni-shop/6.goodslist.html#_6-3-渲染商品列表结构)6.3 渲染商品列表结构

1. 在页面中，通过 `v-for` 指令，循环渲染出商品的 UI 结构：

   ```xml
   <template>
     <view>
       <view class="goods-list">
         <block v-for="(goods, i) in goodsList" :key="i">
           <view class="goods-item">
             <!-- 商品左侧图片区域 -->
             <view class="goods-item-left">
               <image :src="goods.goods_small_logo || defaultPic" class="goods-pic"></image>
             </view>
             <!-- 商品右侧信息区域 -->
             <view class="goods-item-right">
               <!-- 商品标题 -->
               <view class="goods-name">{{goods.goods_name}}</view>
               <view class="goods-info-box">
                 <!-- 商品价格 -->
                 <view class="goods-price">￥{{goods.goods_price}}</view>
               </view>
             </view>
           </view>
         </block>
       </view>
     </view>
   </template>
   ```
2. 为了防止某些商品的图片不存在，需要在 data 中定义一个默认的图片：

   ```js
   data() {
     return {
       // 默认的空图片
       defaultPic: 'https://img3.doubanio.com/f/movie/8dd0c794499fe925ae2ae89ee30cd225750457b4/pics/movie/celebrity-default-medium.png'
     }
   }
   ```

   并在页面渲染时按需使用：

   ```xml
   <image :src="goods.goods_small_logo || defaultPic" class="goods-pic"></image>
   ```
3. 美化商品列表的 UI 结构：

   ```scss
   .goods-item {
     display: flex;
     padding: 10px 5px;
     border-bottom: 1px solid #f0f0f0;

     .goods-item-left {
       margin-right: 5px;

       .goods-pic {
         width: 100px;
         height: 100px;
         display: block;
       }
     }

     .goods-item-right {
       display: flex;
       flex-direction: column;
       justify-content: space-between;

       .goods-name {
         font-size: 13px;
       }

       .goods-price {
         font-size: 16px;
         color: #c00000;
       }
     }
   }
   ```

## [#](https://applet-base-api-t.itheima.net/docs-uni-shop/6.goodslist.html#_6-4-把商品-item-项封装为自定义组件)6.4 把商品 item 项封装为自定义组件

1. 在 `components` 目录上鼠标右键，选择 `新建组件`：
   ![](https://applet-base-api-t.itheima.net/docs-uni-shop/6-2.6a66124f.png)
2. 将 `goods_list` 页面中，关于商品 item 项相关的 UI 结构、样式、data 数据，封装到 `my-goods` 组件中：

   ```html
   <template>
     <view class="goods-item">
       <!-- 商品左侧图片区域 -->
       <view class="goods-item-left">
         <image :src="goods.goods_small_logo || defaultPic" class="goods-pic"></image>
       </view>
       <!-- 商品右侧信息区域 -->
       <view class="goods-item-right">
         <!-- 商品标题 -->
         <view class="goods-name">{{goods.goods_name}}</view>
         <view class="goods-info-box">
           <!-- 商品价格 -->
           <view class="goods-price">￥{{goods.goods_price}}</view>
         </view>
       </view>
     </view>
   </template>

   <script>
     export default {
       // 定义 props 属性，用来接收外界传递到当前组件的数据
       props: {
         // 商品的信息对象
         goods: {
           type: Object,
           defaul: {},
         },
       },
       data() {
         return {
           // 默认的空图片
           defaultPic: 'https://img3.doubanio.com/f/movie/8dd0c794499fe925ae2ae89ee30cd225750457b4/pics/movie/celebrity-default-medium.png',
         }
       },
     }
   </script>

   <style lang="scss">
     .goods-item {
       display: flex;
       padding: 10px 5px;
       border-bottom: 1px solid #f0f0f0;

       .goods-item-left {
         margin-right: 5px;

         .goods-pic {
           width: 100px;
           height: 100px;
           display: block;
         }
       }

       .goods-item-right {
         display: flex;
         flex-direction: column;
         justify-content: space-between;

         .goods-name {
           font-size: 13px;
         }

         .goods-price {
           font-size: 16px;
           color: #c00000;
         }
       }
     }
   </style>
   ```
3. 在 `goods_list` 组件中，循环渲染 `my-goods` 组件即可：

   ```xml
   <view class="goods-list">
     <block v-for="(item, i) in goodsList" :key="i">
       <!-- 为 my-goods 组件动态绑定 goods 属性的值 -->
       <my-goods :goods="item"></my-goods>
     </block>
   </view>
   ```

## [#](https://applet-base-api-t.itheima.net/docs-uni-shop/6.goodslist.html#_6-5-使用过滤器处理价格)6.5 使用过滤器处理价格

1. 在 `my-goods` 组件中，和 `data` 节点平级，声明 `filters` 过滤器节点如下：

   ```js
   filters: {
     // 把数字处理为带两位小数点的数字
     tofixed(num) {
       return Number(num).toFixed(2)
     }
   }
   ```
2. 在渲染商品价格的时候，通过管道符 `|` 调用过滤器：

   ```xml
   <!-- 商品价格 -->
   <view class="goods-price">￥{{goods.goods_price | tofixed}}</view>
   ```

## [#](https://applet-base-api-t.itheima.net/docs-uni-shop/6.goodslist.html#_6-6-上拉加载更多)6.6 上拉加载更多

### [#](https://applet-base-api-t.itheima.net/docs-uni-shop/6.goodslist.html#_6-6-1-初步实现上拉加载更多)6.6.1 初步实现上拉加载更多

1. 打开项目根目录中的 `pages.json` 配置文件，为 `subPackages` 分包中的 `goods_list` 页面配置上拉触底的距离：

   ```js
    "subPackages": [
      {
        "root": "subpkg",
        "pages": [
          {
            "path": "goods_detail/goods_detail",
            "style": {}
          },
          {
            "path": "goods_list/goods_list",
            "style": {
              "onReachBottomDistance": 150
            }
          },
          {
            "path": "search/search",
            "style": {}
          }
        ]
      }
    ]
   ```
2. 在 `goods_list` 页面中，和 `methods` 节点平级，声明 `onReachBottom` 事件处理函数，用来监听页面的上拉触底行为：

   ```js
   // 触底的事件
   onReachBottom() {
     // 让页码值自增 +1
     this.queryObj.pagenum += 1
     // 重新获取列表数据
     this.getGoodsList()
   }
   ```
3. 改造 `methods` 中的 `getGoodsList` 函数，当列表数据请求成功之后，进行新旧数据的拼接处理：

   ```js
   // 获取商品列表数据的方法
   async getGoodsList() {
     // 发起请求
     const { data: res } = await uni.$http.get('/api/public/v1/goods/search', this.queryObj)
     if (res.meta.status !== 200) return uni.$showMsg()

     // 为数据赋值：通过展开运算符的形式，进行新旧数据的拼接
     this.goodsList = [...this.goodsList, ...res.message.goods]
     this.total = res.message.total
   }
   ```

### [#](https://applet-base-api-t.itheima.net/docs-uni-shop/6.goodslist.html#_6-6-2-通过节流阀防止发起额外的请求)6.6.2 通过节流阀防止发起额外的请求

1. 在 data 中定义 `isloading` 节流阀如下：

   ```js
   data() {
     return {
       // 是否正在请求数据
       isloading: false
     }
   }
   ```
2. 修改 `getGoodsList` 方法，在请求数据前后，分别打开和关闭节流阀：

   ```js
   // 获取商品列表数据的方法
   async getGoodsList() {
     // ** 打开节流阀
     this.isloading = true
     // 发起请求
     const { data: res } = await uni.$http.get('/api/public/v1/goods/search', this.queryObj)
     // ** 关闭节流阀
     this.isloading = false

     // 省略其它代码...
   }
   ```
3. 在 `onReachBottom` 触底事件处理函数中，根据节流阀的状态，来决定是否发起请求：

   ```js
   // 触底的事件
   onReachBottom() {
     // 判断是否正在请求其它数据，如果是，则不发起额外的请求
     if (this.isloading) return

     this.queryObj.pagenum += 1
     this.getGoodsList()
   }
   ```

### [#](https://applet-base-api-t.itheima.net/docs-uni-shop/6.goodslist.html#_6-6-3-判断数据是否加载完毕)6.6.3 判断数据是否加载完毕

1. 如果下面的公式成立，则证明没有下一页数据了：

   ```text
   当前的页码值 * 每页显示多少条数据 >= 总数条数
   pagenum * pagesize >= total
   ```
2. 修改 `onReachBottom` 事件处理函数如下：

   ```js
   // 触底的事件
   onReachBottom() {
     // 判断是否还有下一页数据
     if (this.queryObj.pagenum * this.queryObj.pagesize >= this.total) return uni.$showMsg('数据加载完毕！')

     // 判断是否正在请求其它数据，如果是，则不发起额外的请求
     if (this.isloading) return

     this.queryObj.pagenum += 1
     this.getGoodsList()
   }
   ```

## [#](https://applet-base-api-t.itheima.net/docs-uni-shop/6.goodslist.html#_6-7-下拉刷新)6.7 下拉刷新

1. 在 `pages.json` 配置文件中，为当前的 `goods_list` 页面单独开启下拉刷新效果：

   ```js
   "subPackages": [{
     "root": "subpkg",
     "pages": [{
       "path": "goods_detail/goods_detail",
       "style": {}
     }, {
       "path": "goods_list/goods_list",
       "style": {
         "onReachBottomDistance": 150,
         "enablePullDownRefresh": true,
         "backgroundColor": "#F8F8F8"
       }
     }, {
       "path": "search/search",
       "style": {}
     }]
   }]
   ```
2. 监听页面的 `onPullDownRefresh` 事件处理函数：

   ```js
   // 下拉刷新的事件
   onPullDownRefresh() {
     // 1. 重置关键数据
     this.queryObj.pagenum = 1
     this.total = 0
     this.isloading = false
     this.goodsList = []

     // 2. 重新发起请求
     this.getGoodsList(() => uni.stopPullDownRefresh())
   }
   ```
3. 修改 `getGoodsList` 函数，接收 `cb` 回调函数并按需进行调用：

   ```js
   // 获取商品列表数据的方法
   async getGoodsList(cb) {
     this.isloading = true
     const { data: res } = await uni.$http.get('/api/public/v1/goods/search', this.queryObj)
     this.isloading = false
     // 只要数据请求完毕，就立即按需调用 cb 回调函数
     cb && cb()

     if (res.meta.status !== 200) return uni.$showMsg()
     this.goodsList = [...this.goodsList, ...res.message.goods]
     this.total = res.message.total
   }
   ```

## [#](https://applet-base-api-t.itheima.net/docs-uni-shop/6.goodslist.html#_6-8-点击商品-item-项跳转到详情页面)6.8 点击商品 item 项跳转到详情页面

1. 将循环时的 `block` 组件修改为 `view` 组件，并绑定 `click` 点击事件处理函数：

   ```xml
   <view class="goods-list">
     <view v-for="(item, i) in goodsList" :key="i" @click="gotoDetail(item)">
       <!-- 为 my-goods 组件动态绑定 goods 属性的值 -->
       <my-goods :goods="item"></my-goods>
     </view>
   </view>
   ```
2. 在 `methods` 节点中，定义 `gotoDetail` 事件处理函数：

   ```js
   // 点击跳转到商品详情页面
   gotoDetail(item) {
     uni.navigateTo({
       url: '/subpkg/goods_detail/goods_detail?goods_id=' + item.goods_id
     })
   }
   ```

## [#](https://applet-base-api-t.itheima.net/docs-uni-shop/6.goodslist.html#_6-9-分支的合并与提交)6.9 分支的合并与提交

1. 将 `goodslist` 分支进行本地提交：

   ```bash
   git add .
   git commit -m "完成了商品列表页面的开发"
   ```
2. 将本地的 `goodslist` 分支推送到码云：

   ```bash
   git push -u origin goodslist
   ```
3. 将本地 `goodslist` 分支中的代码合并到 `master` 分支：

   ```bash
   git checkout master
   git merge goodslist
   git push
   ```
4. 删除本地的 `goodslist` 分支：

   ```bash
   git branch -d goodslist
   ```

# 7. 商品详情

## [#](https://applet-base-api-t.itheima.net/docs-uni-shop/7.goodsdetail.html#_7-0-创建-goodsdetail-分支)7.0 创建 goodsdetail 分支

运行如下的命令，基于 master 分支在本地创建 goodsdetail 子分支，用来开发商品详情页相关的功能：

```bash
git checkout -b goodsdetail
```

## [#](https://applet-base-api-t.itheima.net/docs-uni-shop/7.goodsdetail.html#_7-1-添加商品详情页的编译模式)7.1 添加商品详情页的编译模式

1. 在微信开发者工具中，点击工具栏上的编译模式下拉菜单，选择 `添加编译模式` 选项：
   ![](assets/image-20250401193036-envai1m.png)
2. 勾选 `启动页面` 的路径，并填写了 `启动参数` 之后，点击 `确定` 按钮，添加详情页面的编译模式：
   ![](https://applet-base-api-t.itheima.net/docs-uni-shop/7-2.82dd8e0f.png)

## [#](https://applet-base-api-t.itheima.net/docs-uni-shop/7.goodsdetail.html#_7-2-获取商品详情数据)7.2 获取商品详情数据

1. 在 `data` 中定义商品详情的数据节点：

   ```js
   data() {
     return {
       // 商品详情对象
       goods_info: {}
     }
   }
   ```
2. 在 `onLoad` 中获取商品的 Id，并调用请求商品详情的方法：

   ```js
   onLoad(options) {
     // 获取商品 Id
     const goods_id = options.goods_id
     // 调用请求商品详情数据的方法
     this.getGoodsDetail(goods_id)
   }
   ```
3. 在 `methods` 中声明 `getGoodsDetail` 方法：

   ```js
   methods: {
     // 定义请求商品详情数据的方法
     async getGoodsDetail(goods_id) {
       const { data: res } = await uni.$http.get('/api/public/v1/goods/detail', { goods_id })
       if (res.meta.status !== 200) return uni.$showMsg()
       // 为 data 中的数据赋值
       this.goods_info = res.message
     }
   }
   ```

## [#](https://applet-base-api-t.itheima.net/docs-uni-shop/7.goodsdetail.html#_7-3-渲染商品详情页的-ui-结构)7.3 渲染商品详情页的 UI 结构

### [#](https://applet-base-api-t.itheima.net/docs-uni-shop/7.goodsdetail.html#_7-3-1-渲染轮播图区域)7.3.1 渲染轮播图区域

1. 使用 `v-for` 指令，循环渲染如下的轮播图 UI 结构：

   ```xml
   <!-- 轮播图区域 -->
   <swiper :indicator-dots="true" :autoplay="true" :interval="3000" :duration="1000" :circular="true">
     <swiper-item v-for="(item, i) in goods_info.pics" :key="i">
       <image :src="item.pics_big"></image>
     </swiper-item>
   </swiper>
   ```
2. 美化轮播图的样式：

   ```scss
   swiper {
     height: 750rpx;

     image {
       width: 100%;
       height: 100%;
     }
   }
   ```

### [#](https://applet-base-api-t.itheima.net/docs-uni-shop/7.goodsdetail.html#_7-3-2-实现轮播图预览效果)7.3.2 实现轮播图预览效果

1. 为轮播图中的 `image` 图片绑定 `click` 事件处理函数：

   ```xml
   <swiper-item v-for="(item, i) in goods_info.pics" :key="i">
     <!-- 把当前点击的图片的索引，传递到 preview() 处理函数中 -->
     <image :src="item.pics_big" @click="preview(i)"></image>
   </swiper-item>
   ```
2. 在 `methods` 中定义 `preview` 事件处理函数：

   ```js
   // 实现轮播图的预览效果
   preview(i) {
     // 调用 uni.previewImage() 方法预览图片
     uni.previewImage({
       // 预览时，默认显示图片的索引
       current: i,
       // 所有图片 url 地址的数组
       urls: this.goods_info.pics.map(x => x.pics_big)
     })
   }
   ```

### [#](https://applet-base-api-t.itheima.net/docs-uni-shop/7.goodsdetail.html#_7-3-3-渲染商品信息区域)7.3.3 渲染商品信息区域

1. 定义商品信息区域的 UI 结构如下：

   ```xml
   <!-- 商品信息区域 -->
   <view class="goods-info-box">
     <!-- 商品价格 -->
     <view class="price">￥{{goods_info.goods_price}}</view>
     <!-- 信息主体区域 -->
     <view class="goods-info-body">
       <!-- 商品名称 -->
       <view class="goods-name">{{goods_info.goods_name}}</view>
       <!-- 收藏 -->
       <view class="favi">
         <uni-icons type="star" size="18" color="gray"></uni-icons>
         <text>收藏</text>
       </view>
     </view>
     <!-- 运费 -->
     <view class="yf">快递：免运费</view>
   </view>
   ```
2. 美化商品信息区域的样式：

   ```scss
   // 商品信息区域的样式
   .goods-info-box {
     padding: 10px;
     padding-right: 0;

     .price {
       color: #c00000;
       font-size: 18px;
       margin: 10px 0;
     }

     .goods-info-body {
       display: flex;
       justify-content: space-between;

       .goods-name {
         font-size: 13px;
         padding-right: 10px;
       }
       // 收藏区域
       .favi {
         width: 120px;
         font-size: 12px;
         display: flex;
         flex-direction: column;
         justify-content: center;
         align-items: center;
         border-left: 1px solid #efefef;
         color: gray;
       }
     }

     // 运费
     .yf {
       margin: 10px 0;
       font-size: 12px;
       color: gray;
     }
   }
   ```

### [#](https://applet-base-api-t.itheima.net/docs-uni-shop/7.goodsdetail.html#_7-3-4-渲染商品详情信息)7.3.4 渲染商品详情信息

1. 在页面结构中，使用 `rich-text` 组件，将带有 HTML 标签的内容，渲染为小程序的页面结构：

   ```xml
   <!-- 商品详情信息 -->
   <rich-text :nodes="goods_info.goods_introduce"></rich-text>
   ```
2. 修改 `getGoodsDetail` 方法，从而解决图片底部 `空白间隙` 的问题：

   ```js
   // 定义请求商品详情数据的方法
   async getGoodsDetail(goods_id) {
     const { data: res } = await uni.$http.get('/api/public/v1/goods/detail', { goods_id })
     if (res.meta.status !== 200) return uni.$showMsg()

     // 使用字符串的 replace() 方法，为 img 标签添加行内的 style 样式，从而解决图片底部空白间隙的问题
     res.message.goods_introduce = res.message.goods_introduce.replace(/<img /g, '<img style="display:block;" ')
     this.goods_info = res.message
   }
   ```
3. 解决 `.webp` 格式图片在 `ios` 设备上无法正常显示的问题：

   ```js
   // 定义请求商品详情数据的方法
   async getGoodsDetail(goods_id) {
     const { data: res } = await uni.$http.get('/api/public/v1/goods/detail', { goods_id })
     if (res.meta.status !== 200) return uni.$showMsg()

     // 使用字符串的 replace() 方法，将 webp 的后缀名替换为 jpg 的后缀名
     res.message.goods_introduce = res.message.goods_introduce.replace(/<img /g, '<img style="display:block;" ').replace(/webp/g, 'jpg')
     this.goods_info = res.message
   }
   ```

### [#](https://applet-base-api-t.itheima.net/docs-uni-shop/7.goodsdetail.html#_7-3-5-解决商品价格闪烁的问题)7.3.5 解决商品价格闪烁的问题

1. 导致问题的原因：在商品详情数据请求回来之前，data 中 `goods_info` 的值为 `{}`，因此初次渲染页面时，会导致 `商品价格、商品名称` 等闪烁的问题。
2. 解决方案：判断 `goods_info.goods_name` 属性的值是否存在，从而使用 `v-if` 指令控制页面的显示与隐藏：

   ```xml
   <template>
     <view v-if="goods_info.goods_name">
      <!-- 省略其它代码 -->
     </view>
   </template>
   ```

## [#](https://applet-base-api-t.itheima.net/docs-uni-shop/7.goodsdetail.html#_7-4-渲染详情页底部的商品导航区域)7.4 渲染详情页底部的商品导航区域

### [#](https://applet-base-api-t.itheima.net/docs-uni-shop/7.goodsdetail.html#_7-4-1-渲染商品导航区域的-ui-结构)7.4.1 渲染商品导航区域的 UI 结构

> 基于 uni-ui 提供的 [GoodsNav]() 组件来实现商品导航区域的效果

1. 在 data 中，通过 `options` 和 `buttonGroup` 两个数组，来声明商品导航组件的按钮配置对象：

   ```js
   data() {
     return {
       // 商品详情对象
       goods_info: {},
       // 左侧按钮组的配置对象
       options: [{
         icon: 'shop',
         text: '店铺'
       }, {
         icon: 'cart',
         text: '购物车',
         info: 2
       }],
       // 右侧按钮组的配置对象
       buttonGroup: [{
           text: '加入购物车',
           backgroundColor: '#ff0000',
           color: '#fff'
         },
         {
           text: '立即购买',
           backgroundColor: '#ffa200',
           color: '#fff'
         }
       ]
     }
   }
   ```
2. 在页面中使用 `uni-goods-nav` 商品导航组件：

   ```xml
   <!-- 商品导航组件 -->
   <view class="goods_nav">
     <!-- fill 控制右侧按钮的样式 -->
     <!-- options 左侧按钮的配置项 -->
     <!-- buttonGroup 右侧按钮的配置项 -->
     <!-- click 左侧按钮的点击事件处理函数 -->
     <!-- buttonClick 右侧按钮的点击事件处理函数 -->
     <uni-goods-nav :fill="true" :options="options" :buttonGroup="buttonGroup" @click="onClick" @buttonClick="buttonClick" />
   </view>
   ```
3. 美化商品导航组件，使之固定在页面最底部：

   ```scss
   .goods-detail-container {
     // 给页面外层的容器，添加 50px 的内padding，
     // 防止页面内容被底部的商品导航组件遮盖
     padding-bottom: 50px;
   }

   .goods_nav {
     // 为商品导航组件添加固定定位
     position: fixed;
     bottom: 0;
     left: 0;
     width: 100%;
   }
   ```

### [#](https://applet-base-api-t.itheima.net/docs-uni-shop/7.goodsdetail.html#_7-4-2-点击跳转到购物车页面)7.4.2 点击跳转到购物车页面

1. 点击商品导航组件左侧的按钮，会触发 `uni-goods-nav` 的 `@click` 事件处理函数，事件对象 `e` 中会包含当前点击的按钮相关的信息：

   ```js
   // 左侧按钮的点击事件处理函数
   onClick(e) {
     console.log(e)
   }
   ```

   打印的按钮信息对象如下：
   ![](assets/image-20250401193036-dkhqzi6.png)
2. 根据 `e.content.text` 的值，来决定进一步的操作：

   ```js
   // 左侧按钮的点击事件处理函数
   onClick(e) {
     if (e.content.text === '购物车') {
       // 切换到购物车页面
       uni.switchTab({
         url: '/pages/cart/cart'
       })
     }
   }
   ```

## [#](https://applet-base-api-t.itheima.net/docs-uni-shop/7.goodsdetail.html#_7-5-分支的合并与提交)7.5 分支的合并与提交

1. 将 `goodsdetail` 分支进行本地提交：

   ```bash
   git add .
   git commit -m "完成了商品详情页面的开发"
   ```
2. 将本地的 `goodsdetail` 分支推送到码云：

   ```bash
   git push -u origin goodsdetail
   ```
3. 将本地 `goodsdetail` 分支中的代码合并到 `master` 分支：

   ```bash
   git checkout master
   git merge goodsdetail
   git push
   ```
4. 删除本地的 `goodsdetail` 分支：

   ```bash
   git branch -d goodsdetail
   ```

# 8. 加入购物车

## [#](https://applet-base-api-t.itheima.net/docs-uni-shop/8.add2cart.html#_8-0-创建-cart-分支)8.0 创建 cart 分支

运行如下的命令，基于 master 分支在本地创建 cart 子分支，用来开发购物车相关的功能：

```bash
git checkout -b cart
```

## [#](https://applet-base-api-t.itheima.net/docs-uni-shop/8.add2cart.html#_8-1-配置-vuex)8.1 配置 vuex

1. 在项目根目录中创建 `store` 文件夹，专门用来存放 vuex 相关的模块
2. 在 `store` 目录上鼠标右键，选择 `新建 -> js文件`，新建 `store.js` 文件：
   ![](assets/image-20250401193048-nbusrs0.png)
3. 在 `store.js` 中按照如下 4 个步骤**初始化 Store 的实例对象**：

   ```js
   // 1. 导入 Vue 和 Vuex
   import Vue from 'vue'
   import Vuex from 'vuex'

   // 2. 将 Vuex 安装为 Vue 的插件
   Vue.use(Vuex)

   // 3. 创建 Store 的实例对象
   const store = new Vuex.Store({
     // TODO：挂载 store 模块
     modules: {},
   })

   // 4. 向外共享 Store 的实例对象
   export default store
   ```
4. 在 `main.js` 中导入 `store` 实例对象并挂载到 Vue 的实例上：

   ```js
   // 1. 导入 store 的实例对象
   import store from './store/store.js'

   // 省略其它代码...

   const app = new Vue({
     ...App,
     // 2. 将 store 挂载到 Vue 实例上
     store,
   })
   app.$mount()
   ```

## [#](https://applet-base-api-t.itheima.net/docs-uni-shop/8.add2cart.html#_8-2-创建购物车的-store-模块)8.2 创建购物车的 store 模块

1. 在 `store` 目录上鼠标右键，选择 `新建 -> js文件`，创建购物车的 store 模块，命名为 `cart.js`：
   ![](assets/image-20250401193048-8zm470m.png)
2. 在 `cart.js` 中，初始化如下的 vuex 模块：

   ```js
   export default {
     // 为当前模块开启命名空间
     namespaced: true,

     // 模块的 state 数据
     state: () => ({
       // 购物车的数组，用来存储购物车中每个商品的信息对象
       // 每个商品的信息对象，都包含如下 6 个属性：
       // { goods_id, goods_name, goods_price, goods_count, goods_small_logo, goods_state }
       cart: [],
     }),

     // 模块的 mutations 方法
     mutations: {},

     // 模块的 getters 属性
     getters: {},
   }
   ```
3. 在 `store/store.js` 模块中，导入并挂载购物车的 vuex 模块，示例代码如下：

   ```js
   import Vue from 'vue'
   import Vuex from 'vuex'
   // 1. 导入购物车的 vuex 模块
   import moduleCart from './cart.js'

   Vue.use(Vuex)

   const store = new Vuex.Store({
     // TODO：挂载 store 模块
     modules: {
       // 2. 挂载购物车的 vuex 模块，模块内成员的访问路径被调整为 m_cart，例如：
       //    购物车模块中 cart 数组的访问路径是 m_cart/cart
       m_cart: moduleCart,
     },
   })

   export default store
   ```

## [#](https://applet-base-api-t.itheima.net/docs-uni-shop/8.add2cart.html#_8-3-在商品详情页中使用-store-中的数据)8.3 在商品详情页中使用 Store 中的数据

1. 在 `goods_detail.vue` 页面中，修改 `<script></script>` 标签中的代码如下：

   ```js
   // 从 vuex 中按需导出 mapState 辅助方法
   import { mapState } from 'vuex'

   export default {
     computed: {
       // 调用 mapState 方法，把 m_cart 模块中的 cart 数组映射到当前页面中，作为计算属性来使用
       // ...mapState('模块的名称', ['要映射的数据名称1', '要映射的数据名称2'])
       ...mapState('m_cart', ['cart']),
     },
     // 省略其它代码...
   }
   ```

   > 注意：今后无论映射 mutations 方法，还是 getters 属性，还是 state 中的数据，都需要指定模块的名称，才能进行映射。
   >
2. 在页面渲染时，可以直接使用映射过来的数据，例如：

   ```xml
   <!-- 运费 -->
   <view class="yf">快递：免运费 -- {{cart.length}}</view>
   ```

## [#](https://applet-base-api-t.itheima.net/docs-uni-shop/8.add2cart.html#_8-4-实现加入购物车的功能)8.4 实现加入购物车的功能

1. 在 store 目录下的 `cart.js` 模块中，封装一个将商品信息加入购物车的 mutations 方法，命名为 `addToCart`。示例代码如下：

   ```js
   export default {
     // 为当前模块开启命名空间
     namespaced: true,

     // 模块的 state 数据
     state: () => ({
       // 购物车的数组，用来存储购物车中每个商品的信息对象
       // 每个商品的信息对象，都包含如下 6 个属性：
       // { goods_id, goods_name, goods_price, goods_count, goods_small_logo, goods_state }
       cart: [],
     }),

     // 模块的 mutations 方法
     mutations: {
       addToCart(state, goods) {
         // 根据提交的商品的Id，查询购物车中是否存在这件商品
         // 如果不存在，则 findResult 为 undefined；否则，为查找到的商品信息对象
         const findResult = state.cart.find((x) => x.goods_id === goods.goods_id)

         if (!findResult) {
           // 如果购物车中没有这件商品，则直接 push
           state.cart.push(goods)
         } else {
           // 如果购物车中有这件商品，则只更新数量即可
           findResult.goods_count++
         }
       },
     },

     // 模块的 getters 属性
     getters: {},
   }
   ```
2. 在商品详情页面中，通过 `mapMutations` 这个辅助方法，把 vuex 中 `m_cart` 模块下的 `addToCart` 方法映射到当前页面：

   ```js
   // 按需导入 mapMutations 这个辅助方法
   import { mapMutations } from 'vuex'

   export default {
     methods: {
       // 把 m_cart 模块中的 addToCart 方法映射到当前页面使用
       ...mapMutations('m_cart', ['addToCart']),
     },
   }
   ```
3. 为商品导航组件 `uni-goods-nav` 绑定 `@buttonClick="buttonClick"` 事件处理函数：

   ```js
   // 右侧按钮的点击事件处理函数
   buttonClick(e) {
      // 1. 判断是否点击了 加入购物车 按钮
      if (e.content.text === '加入购物车') {

         // 2. 组织一个商品的信息对象
         const goods = {
            goods_id: this.goods_info.goods_id,       // 商品的Id
            goods_name: this.goods_info.goods_name,   // 商品的名称
            goods_price: this.goods_info.goods_price, // 商品的价格
            goods_count: 1,                           // 商品的数量
            goods_small_logo: this.goods_info.goods_small_logo, // 商品的图片
            goods_state: true                         // 商品的勾选状态
         }

         // 3. 通过 this 调用映射过来的 addToCart 方法，把商品信息对象存储到购物车中
         this.addToCart(goods)

      }
   }
   ```

## [#](https://applet-base-api-t.itheima.net/docs-uni-shop/8.add2cart.html#_8-5-动态统计购物车中商品的总数量)8.5 动态统计购物车中商品的总数量

1. 在 `cart.js` 模块中，在 `getters` 节点下定义一个 `total` 方法，用来统计购物车中商品的总数量：

   ```js
   // 模块的 getters 属性
   getters: {
      // 统计购物车中商品的总数量
      total(state) {
         let c = 0
         // 循环统计商品的数量，累加到变量 c 中
         state.cart.forEach(goods => c += goods.goods_count)
         return c
      }
   }
   ```
2. 在商品详情页面的 `script` 标签中，按需导入 `mapGetters` 方法并进行使用：

   ```js
   // 按需导入 mapGetters 这个辅助方法
   import { mapGetters } from 'vuex'

   export default {
     computed: {
       // 把 m_cart 模块中名称为 total 的 getter 映射到当前页面中使用
       ...mapGetters('m_cart', ['total']),
     },
   }
   ```
3. 通过 `watch` 侦听器，监听计算属性 `total` 值的变化，从而**动态为购物车按钮的徽标赋值**：

   ```js
   export default {
     watch: {
       // 1. 监听 total 值的变化，通过第一个形参得到变化后的新值
       total(newVal) {
         // 2. 通过数组的 find() 方法，找到购物车按钮的配置对象
         const findResult = this.options.find((x) => x.text === '购物车')

         if (findResult) {
           // 3. 动态为购物车按钮的 info 属性赋值
           findResult.info = newVal
         }
       },
     },
   }
   ```

## [#](https://applet-base-api-t.itheima.net/docs-uni-shop/8.add2cart.html#_8-6-持久化存储购物车中的商品)8.6 持久化存储购物车中的商品

1. 在 `cart.js` 模块中，声明一个叫做 `saveToStorage` 的 mutations 方法，此方法负责将购物车中的数据持久化存储到本地：

   ```js
   // 将购物车中的数据持久化存储到本地
   saveToStorage(state) {
      uni.setStorageSync('cart', JSON.stringify(state.cart))
   }
   ```
2. 修改 `mutations` 节点中的 `addToCart` 方法，在处理完商品信息后，调用步骤 1 中定义的 `saveToStorage` 方法：

   ```js
   addToCart(state, goods) {
      // 根据提交的商品的Id，查询购物车中是否存在这件商品
      // 如果不存在，则 findResult 为 undefined；否则，为查找到的商品信息对象
      const findResult = state.cart.find(x => x.goods_id === goods.goods_id)

      if (!findResult) {
         // 如果购物车中没有这件商品，则直接 push
         state.cart.push(goods)
      } else {
         // 如果购物车中有这件商品，则只更新数量即可
         findResult.goods_count++
      }

      // 通过 commit 方法，调用 m_cart 命名空间下的 saveToStorage 方法
      this.commit('m_cart/saveToStorage')
   }
   ```
3. 修改 `cart.js` 模块中的 `state` 函数，读取本地存储的购物车数据，对 cart 数组进行初始化：

   ```js
   // 模块的 state 数据
   state: () => ({
      // 购物车的数组，用来存储购物车中每个商品的信息对象
      // 每个商品的信息对象，都包含如下 6 个属性：
      // { goods_id, goods_name, goods_price, goods_count, goods_small_logo, goods_state }
      cart: JSON.parse(uni.getStorageSync('cart') || '[]')
   }),
   ```

## [#](https://applet-base-api-t.itheima.net/docs-uni-shop/8.add2cart.html#_8-7-优化商品详情页的-total-侦听器)8.7 优化商品详情页的 total 侦听器

1. 使用**普通函数的形式**定义的 watch 侦听器，**在页面首次加载后不会被调用**。因此导致了商品详情页在首次加载完毕之后，不会将商品的总数量显示到商品导航区域：

   ```js
   watch: {
      // 页面首次加载完毕后，不会调用这个侦听器
      total(newVal) {
         const findResult = this.options.find(x => x.text === '购物车')
         if (findResult) {
            findResult.info = newVal
         }
      }
   }
   ```
2. 为了防止这个上述问题，可以使用**对象的形式**来定义 watch 侦听器（详细文档请参考 Vue 官方的 [watch 侦听器]()教程），示例代码如下：

   ```js
   watch: {
      // 定义 total 侦听器，指向一个配置对象
      total: {
         // handler 属性用来定义侦听器的 function 处理函数
         handler(newVal) {
            const findResult = this.options.find(x => x.text === '购物车')
            if (findResult) {
               findResult.info = newVal
            }
         },
         // immediate 属性用来声明此侦听器，是否在页面初次加载完毕后立即调用
         immediate: true
      }
   }
   ```

## [#](https://applet-base-api-t.itheima.net/docs-uni-shop/8.add2cart.html#_8-8-动态为-tabbar-页面设置数字徽标)8.8 动态为 tabBar 页面设置数字徽标

> 需求描述：从商品详情页面导航到购物车页面之后，需要为 tabBar 中的购物车动态设置数字徽标。

1. 把 Store 中的 total 映射到 `cart.vue` 中使用：

   ```js
   // 按需导入 mapGetters 这个辅助方法
   import { mapGetters } from 'vuex'

   export default {
     data() {
       return {}
     },
     computed: {
       // 将 m_cart 模块中的 total 映射为当前页面的计算属性
       ...mapGetters('m_cart', ['total']),
     },
   }
   ```
2. 在页面刚显示出来的时候，立即调用 `setBadge` 方法，为 tabBar 设置数字徽标：

   ```js
   onShow() {
      // 在页面刚展示的时候，设置数字徽标
      this.setBadge()
   }
   ```
3. 在 `methods` 节点中，声明 `setBadge` 方法如下，通过 `uni.setTabBarBadge()` 为 tabBar 设置数字徽标：

   ```js
   methods: {
      setBadge() {
         // 调用 uni.setTabBarBadge() 方法，为购物车设置右上角的徽标
         uni.setTabBarBadge({
            index: 2, // 索引
            text: this.total + '' // 注意：text 的值必须是字符串，不能是数字
         })
      }
   }
   ```

## [#](https://applet-base-api-t.itheima.net/docs-uni-shop/8.add2cart.html#_8-9-将设置-tabbar-徽标的代码抽离为-mixins)8.9 将设置 tabBar 徽标的代码抽离为 mixins

> 注意：除了要在 cart.vue 页面中设置购物车的数字徽标，还需要在其它 3 个 tabBar 页面中，为购物车设置数字徽标。

> 此时可以使用 Vue 提供的 [mixins]() 特性，提高代码的可维护性。

1. 在项目根目录中新建 `mixins` 文件夹，并在 `mixins` 文件夹之下新建 `tabbar-badge.js` 文件，用来把设置 tabBar 徽标的代码封装为一个 mixin 文件：

   ```js
   import { mapGetters } from 'vuex'

   // 导出一个 mixin 对象
   export default {
     computed: {
       ...mapGetters('m_cart', ['total']),
     },
     onShow() {
       // 在页面刚展示的时候，设置数字徽标
       this.setBadge()
     },
     methods: {
       setBadge() {
         // 调用 uni.setTabBarBadge() 方法，为购物车设置右上角的徽标
         uni.setTabBarBadge({
           index: 2,
           text: this.total + '', // 注意：text 的值必须是字符串，不能是数字
         })
       },
     },
   }
   ```
2. 修改 `home.vue`，`cate.vue`，`cart.vue`，`my.vue` 这 4 个 tabBar 页面的源代码，分别导入 `@/mixins/tabbar-badge.js` 模块并进行使用：

   ```js
   // 导入自己封装的 mixin 模块
   import badgeMix from '@/mixins/tabbar-badge.js'

   export default {
     // 将 badgeMix 混入到当前的页面中进行使用
     mixins: [badgeMix],
     // 省略其它代码...
   }
   ```

# 9. 购物车页面

## [#](https://applet-base-api-t.itheima.net/docs-uni-shop/9.cart.html#_9-0-创建购物车页面的编译模式)9.0 创建购物车页面的编译模式

1. 打开微信开发者工具，点击工具栏上的“编译模式”下拉菜单，选择“添加编译模式”：
   ![](assets/image-20250401193102-x9cjali.png)
2. 勾选“启动页面的路径”之后，点击“确定”按钮，新增购物车页面的编译模式：
   ![](https://applet-base-api-t.itheima.net/docs-uni-shop/9-2.583cf2f7.png)

## [#](https://applet-base-api-t.itheima.net/docs-uni-shop/9.cart.html#_9-1-商品列表区域)9.1 商品列表区域

### [#](https://applet-base-api-t.itheima.net/docs-uni-shop/9.cart.html#_9-1-1-渲染购物车商品列表的标题区域)9.1.1 渲染购物车商品列表的标题区域

1. 定义如下的 UI 结构：

   ```xml
   <!-- 购物车商品列表的标题区域 -->
   <view class="cart-title">
     <!-- 左侧的图标 -->
     <uni-icons type="shop" size="18"></uni-icons>
     <!-- 描述文本 -->
     <text class="cart-title-text">购物车</text>
   </view>
   ```
2. 美化样式：

   ```scss
   .cart-title {
     height: 40px;
     display: flex;
     align-items: center;
     font-size: 14px;
     padding-left: 5px;
     border-bottom: 1px solid #efefef;
     .cart-title-text {
       margin-left: 10px;
     }
   }
   ```

### [#](https://applet-base-api-t.itheima.net/docs-uni-shop/9.cart.html#_9-1-2-渲染商品列表区域的基本结构)9.1.2 渲染商品列表区域的基本结构

1. 通过 `mapState` 辅助函数，将 Store 中的 `cart` 数组映射到当前页面中使用：

   ```js
   import badgeMix from '@/mixins/tabbar-badge.js'
   // 按需导入 mapState 这个辅助函数
   import { mapState } from 'vuex'

   export default {
     mixins: [badgeMix],
     computed: {
       // 将 m_cart 模块中的 cart 数组映射到当前页面中使用
       ...mapState('m_cart', ['cart']),
     },
     data() {
       return {}
     },
   }
   ```
2. 在 UI 结构中，通过 `v-for` 指令循环渲染自定义的 `my-goods` 组件：

   ```xml
   <!-- 商品列表区域 -->
   <block v-for="(goods, i) in cart" :key="i">
     <my-goods :goods="goods"></my-goods>
   </block>
   ```

### [#](https://applet-base-api-t.itheima.net/docs-uni-shop/9.cart.html#_9-1-3-为-my-goods-组件封装-radio-勾选状态)9.1.3 为 my-goods 组件封装 radio 勾选状态

1. 打开 `my-goods.vue` 组件的源代码，为商品的左侧图片区域添加 `radio` 组件：

   ```xml
   <!-- 商品左侧图片区域 -->
   <view class="goods-item-left">
     <radio checked color="#C00000"></radio>
     <image :src="goods.goods_small_logo || defaultPic" class="goods-pic"></image>
   </view>
   ```
2. 给类名为 `goods-item-left` 的 `view` 组件添加样式，实现 `radio` 组件和 `image` 组件的左右布局：

   ```css
   .goods-item-left {
     margin-right: 5px;
     display: flex;
     justify-content: space-between;
     align-items: center;

     .goods-pic {
       width: 100px;
       height: 100px;
       display: block;
     }
   }
   ```
3. 封装名称为 `showRadio` 的 `props` 属性，来控制当前组件中是否显示 radio 组件：

   ```js
   export default {
     // 定义 props 属性，用来接收外界传递到当前组件的数据
     props: {
       // 商品的信息对象
       goods: {
         type: Object,
         default: {},
       },
       // 是否展示图片左侧的 radio
       showRadio: {
         type: Boolean,
         // 如果外界没有指定 show-radio 属性的值，则默认不展示 radio 组件
         default: false,
       },
     },
   }
   ```
4. 使用 `v-if` 指令控制 `radio` 组件的按需展示：

   ```xml
   <!-- 商品左侧图片区域 -->
   <view class="goods-item-left">
     <!-- 使用 v-if 指令控制 radio 组件的显示与隐藏 -->
     <radio checked color="#C00000" v-if="showRadio"></radio>
     <image :src="goods.goods_small_logo || defaultPic" class="goods-pic"></image>
   </view>
   ```
5. 在 `cart.vue` 页面中的商品列表区域，指定 `:show-radio="true"` 属性，从而显示 radio 组件：

   ```xml
   <!-- 商品列表区域 -->
   <block v-for="(goods, i) in cart" :key="i">
     <my-goods :goods="goods" :show-radio="true"></my-goods>
   </block>
   ```
6. 修改 `my-goods.vue` 组件，动态为 `radio` 绑定选中状态：

   ```xml
   <!-- 商品左侧图片区域 -->
   <view class="goods-item-left">
     <!-- 存储在购物车中的商品，包含 goods_state 属性，表示商品的勾选状态 -->
     <radio :checked="goods.goods_state" color="#C00000" v-if="showRadio"></radio>
     <image :src="goods.goods_small_logo || defaultPic" class="goods-pic"></image>
   </view>
   ```

### [#](https://applet-base-api-t.itheima.net/docs-uni-shop/9.cart.html#_9-1-4-为-my-goods-组件封装-radio-change-事件)9.1.4 为 my-goods 组件封装 radio-change 事件

1. 当用户点击 radio 组件，**希望修改当前商品的勾选状态**，此时用户可以为 `my-goods` 组件绑定 `@radio-change` 事件，从而获取当前商品的 `goods_id` 和 `goods_state`：

   ```xml
   <!-- 商品列表区域 -->
   <block v-for="(goods, i) in cart" :key="i">
     <!-- 在 radioChangeHandler 事件处理函数中，通过事件对象 e，得到商品的 goods_id 和 goods_state -->
     <my-goods :goods="goods" :show-radio="true" @radio-change="radioChangeHandler"></my-goods>
   </block>
   ```

   定义 `radioChangeHandler` 事件处理函数如下：

   ```js
   methods: {
     // 商品的勾选状态发生了变化
     radioChangeHandler(e) {
       console.log(e) // 输出得到的数据 -> {goods_id: 395, goods_state: false}
     }
   }
   ```
2. 在 `my-goods.vue` 组件中，为 `radio` 组件绑定 `@click` 事件处理函数如下：

   ```xml
   <!-- 商品左侧图片区域 -->
   <view class="goods-item-left">
     <radio :checked="goods.goods_state" color="#C00000" v-if="showRadio" @click="radioClickHandler"></radio>
     <image :src="goods.goods_small_logo || defaultPic" class="goods-pic"></image>
   </view>
   ```
3. 在 `my-goods.vue` 组件的 methods 节点中，定义 `radioClickHandler` 事件处理函数：

   ```js
   methods: {
     // radio 组件的点击事件处理函数
     radioClickHandler() {
       // 通过 this.$emit() 触发外界通过 @ 绑定的 radio-change 事件，
       // 同时把商品的 Id 和 勾选状态 作为参数传递给 radio-change 事件处理函数
       this.$emit('radio-change', {
         // 商品的 Id
         goods_id: this.goods.goods_id,
         // 商品最新的勾选状态
         goods_state: !this.goods.goods_state
       })
     }
   }
   ```

### [#](https://applet-base-api-t.itheima.net/docs-uni-shop/9.cart.html#_9-1-5-修改购物车中商品的勾选状态)9.1.5 修改购物车中商品的勾选状态

1. 在 `store/cart.js` 模块中，声明如下的 `mutations` 方法，用来修改对应商品的勾选状态：

   ```js
   // 更新购物车中商品的勾选状态
   updateGoodsState(state, goods) {
     // 根据 goods_id 查询购物车中对应商品的信息对象
     const findResult = state.cart.find(x => x.goods_id === goods.goods_id)

     // 有对应的商品信息对象
     if (findResult) {
       // 更新对应商品的勾选状态
       findResult.goods_state = goods.goods_state
       // 持久化存储到本地
       this.commit('m_cart/saveToStorage')
     }
   }
   ```
2. 在 `cart.vue` 页面中，导入 `mapMutations` 这个辅助函数，从而将需要的 mutations 方法映射到当前页面中使用：

   ```js
   import badgeMix from '@/mixins/tabbar-badge.js'
   import { mapState, mapMutations } from 'vuex'

   export default {
     mixins: [badgeMix],
     computed: {
       ...mapState('m_cart', ['cart']),
     },
     data() {
       return {}
     },
     methods: {
       ...mapMutations('m_cart', ['updateGoodsState']),
       // 商品的勾选状态发生了变化
       radioChangeHandler(e) {
         this.updateGoodsState(e)
       },
     },
   }
   ```

### [#](https://applet-base-api-t.itheima.net/docs-uni-shop/9.cart.html#_9-1-6-为-my-goods-组件封装-numberbox)9.1.6 为 my-goods 组件封装 NumberBox

> 注意：[NumberBox]() 组件是 uni-ui 提供的

1. 修改 `my-goods.vue` 组件的源代码，在类名为 `goods-info-box` 的 view 组件内部渲染 `NumberBox` 组件的基本结构：

   ```xml
   <view class="goods-info-box">
     <!-- 商品价格 -->
     <view class="goods-price">￥{{goods.goods_price | tofixed}}</view>
     <!-- 商品数量 -->
     <uni-number-box :min="1"></uni-number-box>
   </view>
   ```
2. 美化页面的结构：

   ```scss
   .goods-item-right {
     display: flex;
     flex: 1;
     flex-direction: column;
     justify-content: space-between;

     .goods-name {
       font-size: 13px;
     }

     .goods-info-box {
       display: flex;
       align-items: center;
       justify-content: space-between;
     }

     .goods-price {
       font-size: 16px;
       color: #c00000;
     }
   }
   ```
3. 在 `my-goods.vue` 组件中，动态为 `NumberBox` 组件绑定商品的数量值：

   ```xml
   <view class="goods-info-box">
     <!-- 商品价格 -->
     <view class="goods-price">￥{{goods.goods_price | tofixed}}</view>
     <!-- 商品数量 -->
     <uni-number-box :min="1" :value="goods.goods_count"></uni-number-box>
   </view>
   ```
4. 在 `my-goods.vue` 组件中，封装名称为 `showNum` 的 `props` 属性，来控制当前组件中是否显示 `NumberBox` 组件：

   ```js
   export default {
     // 定义 props 属性，用来接收外界传递到当前组件的数据
     props: {
       // 商品的信息对象
       goods: {
         type: Object,
         defaul: {},
       },
       // 是否展示图片左侧的 radio
       showRadio: {
         type: Boolean,
         // 如果外界没有指定 show-radio 属性的值，则默认不展示 radio 组件
         default: false,
       },
       // 是否展示价格右侧的 NumberBox 组件
       showNum: {
         type: Boolean,
         default: false,
       },
     },
   }
   ```
5. 在 `my-goods.vue` 组件中，使用 `v-if` 指令控制 `NumberBox` 组件的按需展示：

   ```xml
   <view class="goods-info-box">
     <!-- 商品价格 -->
     <view class="goods-price">￥{{goods.goods_price | tofixed}}</view>
     <!-- 商品数量 -->
     <uni-number-box :min="1" :value="goods.goods_count" @change="numChangeHandler" v-if="showNum"></uni-number-box>
   </view>
   ```
6. 在 `cart.vue` 页面中的商品列表区域，指定 `:show-num="true"` 属性，从而显示 `NumberBox` 组件：

   ```xml
   <!-- 商品列表区域 -->
   <block v-for="(goods, i) in cart" :key="i">
     <my-goods :goods="goods" :show-radio="true" :show-num="true" @radio-change="radioChangeHandler"></my-goods>
   </block>
   ```

### [#](https://applet-base-api-t.itheima.net/docs-uni-shop/9.cart.html#_9-1-7-为-my-goods-组件封装-num-change-事件)9.1.7 为 my-goods 组件封装 num-change 事件

1. 当用户修改了 `NumberBox` 的值以后，希望将最新的商品数量更新到购物车中，此时用户可以为 `my-goods` 组件绑定 `@num-change` 事件，从而获取当前商品的 `goods_id` 和 `goods_count：`​

   ```xml
   <!-- 商品列表区域 -->
   <block v-for="(goods, i) in cart" :key="i">
     <my-goods :goods="goods" :show-radio="true" :show-num="true" @radio-change="radioChangeHandler" @num-change="numberChangeHandler"></my-goods>
   </block>
   ```

   定义 `numberChangeHandler` 事件处理函数如下：

   ```js
   // 商品的数量发生了变化
   numberChangeHandler(e) {
     console.log(e)
   }
   ```
2. 在 `my-goods.vue` 组件中，为 `uni-number-box` 组件绑定 `@change` 事件处理函数如下：

   ```xml
   <view class="goods-info-box">
     <!-- 商品价格 -->
     <view class="goods-price">￥{{goods.goods_price | tofixed}}</view>
     <!-- 商品数量 -->
     <uni-number-box :min="1" :value="goods.goods_count" @change="numChangeHandler"></uni-number-box>
   </view>
   ```
3. 在 `my-goods.vue` 组件的 `methods` 节点中，定义 `numChangeHandler` 事件处理函数：

   ```js
   methods: {
     // NumberBox 组件的 change 事件处理函数
     numChangeHandler(val) {
       // 通过 this.$emit() 触发外界通过 @ 绑定的 num-change 事件
       this.$emit('num-change', {
         // 商品的 Id
         goods_id: this.goods.goods_id,
         // 商品的最新数量
         goods_count: +val
       })
     }
   }
   ```

### [#](https://applet-base-api-t.itheima.net/docs-uni-shop/9.cart.html#_9-1-8-解决-numberbox-数据不合法的问题)9.1.8 解决 NumberBox 数据不合法的问题

> 问题说明：当用户在 NumberBox 中输入字母等非法字符之后，会导致 NumberBox 数据紊乱的问题

1. 打开项目根目录中 `components/uni-number-box/uni-number-box.vue` 组件，修改 `methods` 节点中的 `_onBlur` 函数如下：

   ```js
   _onBlur(event) {
     // 官方的代码没有进行数值转换，用户输入的 value 值可能是非法字符：
     // let value = event.detail.value;

     // 将用户输入的内容转化为整数
     let value = parseInt(event.detail.value);

     if (!value) {
       // 如果转化之后的结果为 NaN，则给定默认值为 1
       this.inputValue = 1;
       return;
     }

     // 省略其它代码...
   }
   ```
2. 修改完毕之后，用户输入**小数**会**被转化为整数**，用户输入**非法字符**会**被替换为默认值 1**

### [#](https://applet-base-api-t.itheima.net/docs-uni-shop/9.cart.html#_9-1-9-完善-numberbox-的-inputvalue-侦听器)9.1.9 完善 NumberBox 的 inputValue 侦听器

> 问题说明：在用户每次输入内容之后，都会触发 inputValue 侦听器，从而调用 this.\$emit("change", newVal) 方法。这种做法可能会把不合法的内容传递出去！

1. 打开项目根目录中 `components/uni-number-box/uni-number-box.vue` 组件，修改 `watch` 节点中的 `inputValue` 侦听器如下：

   ```js
   inputValue(newVal, oldVal) {
     // 官方提供的 if 判断条件，在用户每次输入内容时，都会调用 this.$emit("change", newVal)
     // if (+newVal !== +oldVal) {

     // 新旧内容不同 && 新值内容合法 && 新值中不包含小数点
     if (+newVal !== +oldVal && Number(newVal) && String(newVal).indexOf('.') === -1) {
       this.$emit("change", newVal);
     }
   }
   ```
2. 修改完毕之后，NumberBox 组件只会把**合法的、且不包含小数点的新值**传递出去

### [#](https://applet-base-api-t.itheima.net/docs-uni-shop/9.cart.html#_9-1-10-修改购物车中商品的数量)9.1.10 修改购物车中商品的数量

1. 在 `store/cart.js` 模块中，声明如下的 mutations 方法，用来修改对应商品的数量：

   ```js
   // 更新购物车中商品的数量
   updateGoodsCount(state, goods) {
     // 根据 goods_id 查询购物车中对应商品的信息对象
     const findResult = state.cart.find(x => x.goods_id === goods.goods_id)

     if(findResult) {
       // 更新对应商品的数量
       findResult.goods_count = goods.goods_count
       // 持久化存储到本地
       this.commit('m_cart/saveToStorage')
     }
   }
   ```
2. 在 `cart.vue` 页面中，通过 `mapMutations` 这个辅助函数，将需要的 `mutations` 方法映射到当前页面中使用：

   ```js
   import badgeMix from '@/mixins/tabbar-badge.js'
   import { mapState, mapMutations } from 'vuex'

   export default {
     mixins: [badgeMix],
     computed: {
       ...mapState('m_cart', ['cart']),
     },
     data() {
       return {}
     },
     methods: {
       ...mapMutations('m_cart', ['updateGoodsState', 'updateGoodsCount']),
       // 商品的勾选状态发生了变化
       radioChangeHandler(e) {
         this.updateGoodsState(e)
       },
       // 商品的数量发生了变化
       numberChangeHandler(e) {
         this.updateGoodsCount(e)
       },
     },
   }
   ```

### [#](https://applet-base-api-t.itheima.net/docs-uni-shop/9.cart.html#_9-1-11-渲染滑动删除的-ui-效果)9.1.11 渲染滑动删除的 UI 效果

> 滑动删除需要用到 uni-ui 的 uni-swipe-action 组件和 uni-swipe-action-item。详细的官方文档请参考[SwipeAction 滑动操作]()。

1. 改造 `cart.vue` 页面的 UI 结构，将商品列表区域的结构修改如下（可以使用 **uSwipeAction** 代码块快速生成基本的 UI 结构）：

   ```xml
   <!-- 商品列表区域 -->
   <!-- uni-swipe-action 是最外层包裹性质的容器 -->
   <uni-swipe-action>
     <block v-for="(goods, i) in cart" :key="i">
       <!-- uni-swipe-action-item 可以为其子节点提供滑动操作的效果。需要通过 options 属性来指定操作按钮的配置信息 -->
       <uni-swipe-action-item :options="options" @click="swipeActionClickHandler(goods)">
         <my-goods :goods="goods" :show-radio="true" :show-num="true" @radio-change="radioChangeHandler" @num-change="numberChangeHandler"></my-goods>
       </uni-swipe-action-item>
     </block>
   </uni-swipe-action>
   ```
2. 在 data 节点中声明 `options` 数组，用来定义操作按钮的配置信息：

   ```js
   data() {
     return {
       options: [{
         text: '删除', // 显示的文本内容
         style: {
           backgroundColor: '#C00000' // 按钮的背景颜色
         }
       }]
     }
   }
   ```
3. 在 `methods` 中声明 `uni-swipe-action-item` 组件的 `@click` 事件处理函数：

   ```js
   // 点击了滑动操作按钮
   swipeActionClickHandler(goods) {
     console.log(goods)
   }
   ```
4. 美化 `my-goods.vue` 组件的样式：

   ```scss
   .goods-item {
     // 让 goods-item 项占满整个屏幕的宽度
     width: 750rpx;
     // 设置盒模型为 border-box
     box-sizing: border-box;
     display: flex;
     padding: 10px 5px;
     border-bottom: 1px solid #f0f0f0;
   }
   ```

### [#](https://applet-base-api-t.itheima.net/docs-uni-shop/9.cart.html#_9-1-12-实现滑动删除的功能)9.1.12 实现滑动删除的功能

1. 在 `store/cart.js` 模块的 `mutations` 节点中声明如下的方法，从而根据商品的 Id 从购物车中移除对应的商品：

   ```js
   // 根据 Id 从购物车中删除对应的商品信息
   removeGoodsById(state, goods_id) {
     // 调用数组的 filter 方法进行过滤
     state.cart = state.cart.filter(x => x.goods_id !== goods_id)
     // 持久化存储到本地
     this.commit('m_cart/saveToStorage')
   }
   ```
2. 在 `cart.vue` 页面中，使用 `mapMutations` 辅助函数，把需要的方法映射到当前页面中使用：

   ```js
   methods: {
     ...mapMutations('m_cart', ['updateGoodsState', 'updateGoodsCount', 'removeGoodsById']),
     // 商品的勾选状态发生了变化
     radioChangeHandler(e) {
       this.updateGoodsState(e)
     },
     // 商品的数量发生了变化
     numberChangeHandler(e) {
       this.updateGoodsCount(e)
     },
     // 点击了滑动操作按钮
     swipeActionClickHandler(goods) {
       this.removeGoodsById(goods.goods_id)
     }
   }
   ```

## [#](https://applet-base-api-t.itheima.net/docs-uni-shop/9.cart.html#_9-2-收货地址区域)9.2 收货地址区域

### [#](https://applet-base-api-t.itheima.net/docs-uni-shop/9.cart.html#_9-2-1-创建收货地址组件)9.2.1 创建收货地址组件

1. 在 `components` 目录上鼠标右键，选择 `新建组件`，并填写组件相关的信息：
   ![](https://applet-base-api-t.itheima.net/docs-uni-shop/9-3.d168684c.png)
2. 渲染收货地址组件的基本结构：

   ```xml
   <view>

     <!-- 选择收货地址的盒子 -->
     <view class="address-choose-box">
       <button type="primary" size="mini" class="btnChooseAddress">请选择收货地址+</button>
     </view>

     <!-- 渲染收货信息的盒子 -->
     <view class="address-info-box">
       <view class="row1">
         <view class="row1-left">
           <view class="username">收货人：<text>escook</text></view>
         </view>
         <view class="row1-right">
           <view class="phone">电话：<text>138XXXX5555</text></view>
           <uni-icons type="arrowright" size="16"></uni-icons>
         </view>
       </view>
       <view class="row2">
         <view class="row2-left">收货地址：</view>
         <view class="row2-right">河北省邯郸市肥乡区xxx 河北省邯郸市肥乡区xxx 河北省邯郸市肥乡区xxx 河北省邯郸市肥乡区xxx </view>
       </view>
     </view>

     <!-- 底部的边框线 -->
     <image src="/static/cart_border@2x.png" class="address-border"></image>
   </view>
   ```
3. 美化收货地址组件的样式：

   ```scss
   // 底部边框线的样式
   .address-border {
     display: block;
     width: 100%;
     height: 5px;
   }

   // 选择收货地址的盒子
   .address-choose-box {
     height: 90px;
     display: flex;
     align-items: center;
     justify-content: center;
   }

   // 渲染收货信息的盒子
   .address-info-box {
     font-size: 12px;
     height: 90px;
     display: flex;
     flex-direction: column;
     justify-content: center;
     padding: 0 5px;

     // 第一行
     .row1 {
       display: flex;
       justify-content: space-between;

       .row1-right {
         display: flex;
         align-items: center;

         .phone {
           margin-right: 5px;
         }
       }
     }

     // 第二行
     .row2 {
       display: flex;
       align-items: center;
       margin-top: 10px;

       .row2-left {
         white-space: nowrap;
       }
     }
   }
   ```

### [#](https://applet-base-api-t.itheima.net/docs-uni-shop/9.cart.html#_9-2-2-实现收货地址区域的按需展示)9.2.2 实现收货地址区域的按需展示

1. 在 data 中定义收货地址的信息对象：

   ```js
   export default {
     data() {
       return {
         // 收货地址
         address: {},
       }
     },
   }
   ```
2. 使用 `v-if` 和 `v-else` 实现按需展示：

   ```xml
   <!-- 选择收货地址的盒子 -->
   <view class="address-choose-box" v-if="JSON.stringify(address) === '{}'">
     <button type="primary" size="mini" class="btnChooseAddress">请选择收货地址+</button>
   </view>

   <!-- 渲染收货信息的盒子 -->
   <view class="address-info-box" v-else>
     <!-- 省略其它代码 -->
   </view>
   ```

### [#](https://applet-base-api-t.itheima.net/docs-uni-shop/9.cart.html#_9-2-3-实现选择收货地址的功能)9.2.3 实现选择收货地址的功能

1. 为 `请选择收货地址+` 的 `button` 按钮绑定点击事件处理函数：

   ```xml
   <!-- 选择收货地址的盒子 -->
   <view class="address-choose-box" v-if="JSON.stringify(address) === '{}'">
     <button type="primary" size="mini" class="btnChooseAddress" @click="chooseAddress">请选择收货地址+</button>
   </view>
   ```
2. 定义 `chooseAddress` 事件处理函数，调用小程序提供的 `chooseAddress()` API 实现选择收货地址的功能：

   ```js
   methods: {
     // 选择收货地址
     async chooseAddress() {
       // 1. 调用小程序提供的 chooseAddress() 方法，即可使用选择收货地址的功能
       //    返回值是一个数组：第 1 项为错误对象；第 2 项为成功之后的收货地址对象
       const [err, succ] = await uni.chooseAddress().catch(err => err)

       // 2. 用户成功的选择了收货地址
       if (err === null && succ.errMsg === 'chooseAddress:ok') {
         // 为 data 里面的收货地址对象赋值
         this.address = succ
       }
     }
   }
   ```
3. 定义**收货详细地址**的计算属性：

   ```js
   computed: {
     // 收货详细地址的计算属性
     addstr() {
       if (!this.address.provinceName) return ''

       // 拼接 省，市，区，详细地址 的字符串并返回给用户
       return this.address.provinceName + this.address.cityName + this.address.countyName + this.address.detailInfo
     }
   }
   ```
4. 渲染收货地址区域的数据：

   ```xml
   <!-- 渲染收货信息的盒子 -->
   <view class="address-info-box" v-else>
     <view class="row1">
       <view class="row1-left">
         <view class="username">收货人：<text>{{address.userName}}</text></view>
       </view>
       <view class="row1-right">
         <view class="phone">电话：<text>{{address.telNumber}}</text></view>
         <uni-icons type="arrowright" size="16"></uni-icons>
       </view>
     </view>
     <view class="row2">
       <view class="row2-left">收货地址：</view>
       <view class="row2-right">{{addstr}}</view>
     </view>
   </view>
   ```

### [#](https://applet-base-api-t.itheima.net/docs-uni-shop/9.cart.html#_9-2-4-将-address-信息存储到-vuex-中)9.2.4 将 address 信息存储到 vuex 中

1. 在 `store` 目录中，创建用户相关的 `vuex` 模块，命名为 `user.js`：

   ```js
   export default {
     // 开启命名空间
     namespaced: true,

     // state 数据
     state: () => ({
       // 收货地址
       address: {},
     }),

     // 方法
     mutations: {
       // 更新收货地址
       updateAddress(state, address) {
         state.address = address
       },
     },

     // 数据包装器
     getters: {},
   }
   ```
2. 在 `store/store.js` 模块中，导入并挂载 `user.js` 模块：

   ```js
   // 1. 导入 Vue 和 Vuex
   import Vue from 'vue'
   import Vuex from 'vuex'
   // 导入购物车的 vuex 模块
   import moduleCart from './cart.js'
   // 导入用户的 vuex 模块
   import moduleUser from './user.js'

   // 2. 将 Vuex 安装为 Vue 的插件
   Vue.use(Vuex)

   // 3. 创建 Store 的实例对象
   const store = new Vuex.Store({
     // TODO：挂载 store 模块
     modules: {
       // 挂载购物车的 vuex 模块，模块内成员的访问路径被调整为 m_cart，例如：
       // 购物车模块中 cart 数组的访问路径是 m_cart/cart
       m_cart: moduleCart,
       // 挂载用户的 vuex 模块，访问路径为 m_user
       m_user: moduleUser,
     },
   })

   // 4. 向外共享 Store 的实例对象
   export default store
   ```
3. 改造 `address.vue` 组件中的代码，使用 **vuex 提供的 address 计算属性** 替代 **data 中定义的本地 address 对象**：

   ```js
   // 1. 按需导入 mapState 和 mapMutations 这两个辅助函数
   import { mapState, mapMutations } from 'vuex'

   export default {
     data() {
       return {
         // 2.1 注释掉下面的 address 对象，使用 2.2 中的代码替代之
         // address: {}
       }
     },
     methods: {
       // 3.1 把 m_user 模块中的 updateAddress 函数映射到当前组件
       ...mapMutations('m_user', ['updateAddress']),
       // 选择收货地址
       async chooseAddress() {
         const [err, succ] = await uni.chooseAddress().catch((err) => err)

         // 用户成功的选择了收货地址
         if (err === null && succ.errMsg === 'chooseAddress:ok') {
           // 3.2 把下面这行代码注释掉，使用 3.3 中的代码替代之
           // this.address = succ

           // 3.3 调用 Store 中提供的 updateAddress 方法，将 address 保存到 Store 里面
           this.updateAddress(succ)
         }
       },
     },
     computed: {
       // 2.2 把 m_user 模块中的 address 对象映射当前组件中使用，代替 data 中 address 对象
       ...mapState('m_user', ['address']),
       // 收货详细地址的计算属性
       addstr() {
         if (!this.address.provinceName) return ''

         // 拼接 省，市，区，详细地址 的字符串并返回给用户
         return this.address.provinceName + this.address.cityName + this.address.countyName + this.address.detailInfo
       },
     },
   }
   ```

### [#](https://applet-base-api-t.itheima.net/docs-uni-shop/9.cart.html#_9-2-5-将-store-中的-address-持久化存储到本地)9.2.5 将 Store 中的 address 持久化存储到本地

1. 修改 `store/user.js` 模块中的代码如下：

   ```js
   export default {
     // 开启命名空间
     namespaced: true,

     // state 数据
     state: () => ({
       // 3. 读取本地的收货地址数据，初始化 address 对象
       address: JSON.parse(uni.getStorageSync('address') || '{}'),
     }),

     // 方法
     mutations: {
       // 更新收货地址
       updateAddress(state, address) {
         state.address = address

         // 2. 通过 this.commit() 方法，调用 m_user 模块下的 saveAddressToStorage 方法将 address 对象持久化存储到本地
         this.commit('m_user/saveAddressToStorage')
       },
       // 1. 定义将 address 持久化存储到本地 mutations 方法
       saveAddressToStorage(state) {
         uni.setStorageSync('address', JSON.stringify(state.address))
       },
     },

     // 数据包装器
     getters: {},
   }
   ```

### [#](https://applet-base-api-t.itheima.net/docs-uni-shop/9.cart.html#_9-2-6-将-addstr-抽离为-getters)9.2.6 将 addstr 抽离为 getters

> 目的：为了提高代码的复用性，可以把收货的详细地址抽离为 getters，方便在多个页面和组件之间实现复用。

1. 剪切 `my-address.vue` 组件中的 `addstr` 计算属性的代码，粘贴到 `user.js` 模块中，作为一个 getters 节点：

   ```js
   // 数据包装器
   getters: {
     // 收货详细地址的计算属性
     addstr(state) {
       if (!state.address.provinceName) return ''

       // 拼接 省，市，区，详细地址 的字符串并返回给用户
       return state.address.provinceName + state.address.cityName + state.address.countyName + state.address.detailInfo
     }
   }
   ```
2. 改造 `my-address.vue` 组件中的代码，通过 `mapGetters` 辅助函数，将 `m_user` 模块中的 `addstr` 映射到当前组件中使用：

   ```js
   // 按需导入 mapGetters 辅助函数
   import { mapState, mapMutations, mapGetters } from 'vuex'

   export default {
     // 省略其它代码
     computed: {
       ...mapState('m_user', ['address']),
       // 将 m_user 模块中的 addstr 映射到当前组件中使用
       ...mapGetters('m_user', ['addstr']),
     },
   }
   ```

### [#](https://applet-base-api-t.itheima.net/docs-uni-shop/9.cart.html#_9-2-7-重新选择收货地址)9.2.7 重新选择收货地址

1. 为 class 类名为 `address-info-box` 的盒子绑定 `click` 事件处理函数如下：

   ```xml
   <!-- 渲染收货信息的盒子 -->
   <view class="address-info-box" v-else @click="chooseAddress">
     <!-- 省略其它代码 -->
   </view>
   ```

### [#](https://applet-base-api-t.itheima.net/docs-uni-shop/9.cart.html#_9-2-8-解决收货地址授权失败的问题)9.2.8 解决收货地址授权失败的问题

> 如果在选择收货地址的时候，用户点击了**取消授权**，则需要进行**特殊的处理**，否则**用户将无法再次选择收货地址**！

1. 改造 `chooseAddress` 方法如下：

   ```js
   // 选择收货地址
   async chooseAddress() {
     // 1. 调用小程序提供的 chooseAddress() 方法，即可使用选择收货地址的功能
     //    返回值是一个数组：第1项为错误对象；第2项为成功之后的收货地址对象
     const [err, succ] = await uni.chooseAddress().catch(err => err)

     // 2. 用户成功的选择了收货地址
     if (succ && succ.errMsg === 'chooseAddress:ok') {
       // 更新 vuex 中的收货地址
       this.updateAddress(succ)
     }

     // 3. 用户没有授权
     if (err && err.errMsg === 'chooseAddress:fail auth deny') {
       this.reAuth() // 调用 this.reAuth() 方法，向用户重新发起授权申请
     }
   }
   ```
2. 在 `methods` 节点中声明 `reAuth` 方法如下：

   ```js
   // 调用此方法，重新发起收货地址的授权
   async reAuth() {
     // 3.1 提示用户对地址进行授权
     const [err2, confirmResult] = await uni.showModal({
       content: '检测到您没打开地址权限，是否去设置打开？',
       confirmText: "确认",
       cancelText: "取消",
     })

     // 3.2 如果弹框异常，则直接退出
     if (err2) return

     // 3.3 如果用户点击了 “取消” 按钮，则提示用户 “您取消了地址授权！”
     if (confirmResult.cancel) return uni.$showMsg('您取消了地址授权！')

     // 3.4 如果用户点击了 “确认” 按钮，则调用 uni.openSetting() 方法进入授权页面，让用户重新进行授权
     if (confirmResult.confirm) return uni.openSetting({
       // 3.4.1 授权结束，需要对授权的结果做进一步判断
       success: (settingResult) => {
         // 3.4.2 地址授权的值等于 true，提示用户 “授权成功”
         if (settingResult.authSetting['scope.address']) return uni.$showMsg('授权成功！请选择地址')
         // 3.4.3 地址授权的值等于 false，提示用户 “您取消了地址授权”
         if (!settingResult.authSetting['scope.address']) return uni.$showMsg('您取消了地址授权！')
       }
     })
   }
   ```

### [#](https://applet-base-api-t.itheima.net/docs-uni-shop/9.cart.html#_9-2-9-解决-iphone-真机上无法重新授权的问题)9.2.9 解决 iPhone 真机上无法重新授权的问题

> 问题说明：在 iPhone 设备上，当用户取消授权之后，再次点击选择收货地址按钮的时候，无法弹出授权的提示框！

1. 导致问题的原因 - 用户取消授权后，再次点击 “选择收货地址” 按钮的时候：

   - 在**模拟器**和**安卓真机**上，错误消息 `err.errMsg` 的值为 `chooseAddress:fail auth deny`​
   - 在 **iPhone 真机**上，错误消息 `err.errMsg` 的值为 `chooseAddress:fail authorize no response`​
2. 解决问题的方案 - 修改 `chooseAddress` 方法中的代码，进一步完善用户没有授权时的 `if` 判断条件即可：

   ```js
   async chooseAddress() {
     // 1. 调用小程序提供的 chooseAddress() 方法，即可使用选择收货地址的功能
     //    返回值是一个数组：第1项为错误对象；第2项为成功之后的收货地址对象
     const [err, succ] = await uni.chooseAddress().catch(err => err)

     // 2. 用户成功的选择了收货地址
     if (succ && succ.errMsg === 'chooseAddress:ok') {
       this.updateAddress(succ)
     }

     // 3. 用户没有授权
     if (err && (err.errMsg === 'chooseAddress:fail auth deny' || err.errMsg === 'chooseAddress:fail authorize no response')) {
       this.reAuth()
     }
   }
   ```

## [#](https://applet-base-api-t.itheima.net/docs-uni-shop/9.cart.html#_9-3-结算区域)9.3 结算区域

### [#](https://applet-base-api-t.itheima.net/docs-uni-shop/9.cart.html#_9-3-1-把结算区域封装为组件)9.3.1 把结算区域封装为组件

1. 在 `components` 目录中，新建 `my-settle` 结算组件：
   ![](https://applet-base-api-t.itheima.net/docs-uni-shop/9-4.1739d570.png)
2. 初始化 `my-settle` 组件的基本结构和样式：

   ```vue
   <template>
     <!-- 最外层的容器 -->
     <view class="my-settle-container">
       结算组件
     </view>
   </template>

   <script>
   export default {
     data() {
       return {}
     },
   }
   </script>

   <style lang="scss">
   .my-settle-container {
     /* 底部固定定位 */
     position: fixed;
     bottom: 0;
     left: 0;
     /* 设置宽高和背景色 */
     width: 100%;
     height: 50px;
     background-color: cyan;
   }
   </style>
   ```
3. 在 `cart.vue` 页面中使用自定义的 `my-settle` 组件，并美化页面样式，防止页面底部被覆盖：

   ```vue
   <template>
     <view class="cart-container">
       <!-- 使用自定义的 address 组件 -->

       <!-- 购物车商品列表的标题区域 -->

       <!-- 商品列表区域 -->

       <!-- 结算区域 -->
       <my-settle></my-settle>
     </view>
   </template>

   <style lang="scss">
   .cart-container {
     padding-bottom: 50px;
   }
   </style>
   ```

### [#](https://applet-base-api-t.itheima.net/docs-uni-shop/9.cart.html#_9-3-2-渲染结算区域的结构和样式)9.3.2 渲染结算区域的结构和样式

1. 定义如下的 UI 结构：

   ```xml
   <!-- 最外层的容器 -->
   <view class="my-settle-container">
     <!-- 全选区域 -->
     <label class="radio">
       <radio color="#C00000" :checked="true" /><text>全选</text>
     </label>

     <!-- 合计区域 -->
     <view class="amount-box">
       合计:<text class="amount">￥1234.00</text>
     </view>

     <!-- 结算按钮 -->
     <view class="btn-settle">结算(0)</view>
   </view>
   ```
2. 美化样式：

   ```scss
   .my-settle-container {
     position: fixed;
     bottom: 0;
     left: 0;
     width: 100%;
     height: 50px;
     // 将背景色从 cyan 改为 white
     background-color: white;
     display: flex;
     justify-content: space-between;
     align-items: center;
     padding-left: 5px;
     font-size: 14px;

     .radio {
       display: flex;
       align-items: center;
     }

     .amount {
       color: #c00000;
     }

     .btn-settle {
       height: 50px;
       min-width: 100px;
       background-color: #c00000;
       color: white;
       line-height: 50px;
       text-align: center;
       padding: 0 10px;
     }
   }
   ```

### [#](https://applet-base-api-t.itheima.net/docs-uni-shop/9.cart.html#_9-3-3-动态渲染已勾选商品的总数量)9.3.3 动态渲染已勾选商品的总数量

1. 在 `store/cart.js` 模块中，定义一个名称为 `checkedCount` 的 getters，用来统计已勾选商品的总数量：

   ```js
   // 勾选的商品的总数量
   checkedCount(state) {
     // 先使用 filter 方法，从购物车中过滤器已勾选的商品
     // 再使用 reduce 方法，将已勾选的商品总数量进行累加
     // reduce() 的返回值就是已勾选的商品的总数量
     return state.cart.filter(x => x.goods_state).reduce((total, item) => total += item.goods_count, 0)
   }
   ```
2. 在 `my-settle` 组件中，通过 `mapGetters` 辅助函数，将需要的 getters 映射到当前组件中使用：

   ```js
   import { mapGetters } from 'vuex'

   export default {
     computed: {
       ...mapGetters('m_cart', ['checkedCount']),
     },
     data() {
       return {}
     },
   }
   ```
3. 将 `checkedCount` 的值渲染到页面中：

   ```xml
   <!-- 结算按钮 -->
   <view class="btn-settle">结算({{checkedCount}})</view>
   ```

### [#](https://applet-base-api-t.itheima.net/docs-uni-shop/9.cart.html#_9-3-4-动态渲染全选按钮的选中状态)9.3.4 动态渲染全选按钮的选中状态

1. 使用 `mapGetters` 辅助函数，将**商品的总数量**映射到当前组件中使用，并定义一个叫做 `isFullCheck` 的计算属性：

   ```js
   import { mapGetters } from 'vuex'

   export default {
     computed: {
       // 1. 将 total 映射到当前组件中
       ...mapGetters('m_cart', ['checkedCount', 'total']),
       // 2. 是否全选
       isFullCheck() {
         return this.total === this.checkedCount
       },
     },
     data() {
       return {}
     },
   }
   ```
2. 为 radio 组件动态绑定 `checked` 属性的值：

   ```xml
   <!-- 全选区域 -->
   <label class="radio">
     <radio color="#C00000" :checked="isFullCheck" /><text>全选</text>
   </label>
   ```

### [#](https://applet-base-api-t.itheima.net/docs-uni-shop/9.cart.html#_9-3-5-实现商品的全选-反选功能)9.3.5 实现商品的全选/反选功能

1. 在 `store/cart.js` 模块中，定义一个叫做 `updateAllGoodsState` 的 mutations 方法，用来修改所有商品的勾选状态：

   ```js
   // 更新所有商品的勾选状态
   updateAllGoodsState(state, newState) {
     // 循环更新购物车中每件商品的勾选状态
     state.cart.forEach(x => x.goods_state = newState)
     // 持久化存储到本地
     this.commit('m_cart/saveToStorage')
   }
   ```
2. 在 `my-settle` 组件中，通过 `mapMutations` 辅助函数，将需要的 mutations 方法映射到当前组件中使用：

   ```js
   // 1. 按需导入 mapMutations 辅助函数
   import { mapGetters, mapMutations } from 'vuex'

   export default {
     // 省略其它代码
     methods: {
       // 2. 使用 mapMutations 辅助函数，把 m_cart 模块提供的 updateAllGoodsState 方法映射到当前组件中使用
       ...mapMutations('m_cart', ['updateAllGoodsState']),
     },
   }
   ```
3. 为 UI 中的 `label` 组件绑定 `click` 事件处理函数：

   ```xml
   <!-- 全选区域 -->
   <label class="radio" @click="changeAllState">
     <radio color="#C00000" :checked="isFullCheck" /><text>全选</text>
   </label>
   ```
4. 在 `my-settle` 组件的 methods 节点中，声明 `changeAllState` 事件处理函数：

   ```js
   methods: {
     ...mapMutations('m_cart', ['updateAllGoodsState']),
     // label 的点击事件处理函数
     changeAllState() {
       // 修改购物车中所有商品的选中状态
       // !this.isFullCheck 表示：当前全选按钮的状态取反之后，就是最新的勾选状态
       this.updateAllGoodsState(!this.isFullCheck)
     }
   }
   ```

### [#](https://applet-base-api-t.itheima.net/docs-uni-shop/9.cart.html#_9-3-6-动态渲染已勾选商品的总价格)9.3.6 动态渲染已勾选商品的总价格

1. 在 `store/cart.js` 模块中，定义一个叫做 `checkedGoodsAmount` 的 getters，用来统计已勾选商品的总价格：

   ```js
   // 已勾选的商品的总价
   checkedGoodsAmount(state) {
     // 先使用 filter 方法，从购物车中过滤器已勾选的商品
     // 再使用 reduce 方法，将已勾选的商品数量 * 单价之后，进行累加
     // reduce() 的返回值就是已勾选的商品的总价
     // 最后调用 toFixed(2) 方法，保留两位小数
     return state.cart.filter(x => x.goods_state)
                      .reduce((total, item) => total += item.goods_count * item.goods_price, 0)
                      .toFixed(2)
   }
   ```
2. 在 `my-settle` 组件中，使用 `mapGetters` 辅助函数，把需要的 `checkedGoodsAmount` 映射到当前组件中使用：

   ```js
   ...mapGetters('m_cart', ['total', 'checkedCount', 'checkedGoodsAmount'])
   ```
3. 在组件的 UI 结构中，渲染已勾选的商品的总价：

   ```xml
   <!-- 合计区域 -->
   <view class="amount-box">
     合计:<text class="amount">￥{{checkedGoodsAmount}}</text>
   </view>
   ```

### [#](https://applet-base-api-t.itheima.net/docs-uni-shop/9.cart.html#_9-3-7-动态计算购物车徽标的数值)9.3.7 动态计算购物车徽标的数值

1. **问题说明**：当修改购物车中商品的数量之后，tabBar 上的数字徽标不会自动更新。
2. **解决方案**：改造 `mixins/tabbar-badge.js` 中的代码，使用 `watch` 侦听器，监听 `total` 总数量的变化，从而动态为 tabBar 的徽标赋值：

   ```js
   import { mapGetters } from 'vuex'

   // 导出一个 mixin 对象
   export default {
     computed: {
       ...mapGetters('m_cart', ['total']),
     },
     watch: {
       // 监听 total 值的变化
       total() {
         // 调用 methods 中的 setBadge 方法，重新为 tabBar 的数字徽章赋值
         this.setBadge()
       },
     },
     onShow() {
       // 在页面刚展示的时候，设置数字徽标
       this.setBadge()
     },
     methods: {
       setBadge() {
         // 调用 uni.setTabBarBadge() 方法，为购物车设置右上角的徽标
         uni.setTabBarBadge({
           index: 2,
           text: this.total + '', // 注意：text 的值必须是字符串，不能是数字
         })
       },
     },
   }
   ```

### [#](https://applet-base-api-t.itheima.net/docs-uni-shop/9.cart.html#_9-3-8-渲染购物车为空时的页面结构)9.3.8 渲染购物车为空时的页面结构

1. 将 `资料` 目录中的 `cart_empty@2x.png` 图片复制到项目的 `/static/` 目录中
2. 改造 `cart.vue` 页面的 UI 结构，使用 `v-if` 和 `v-else` 控制**购物车区域**和**空白购物车区域**的按需展示：

   ```xml
   <template>
     <view class="cart-container" v-if="cart.length !== 0">

       <!-- 使用自定义的 address 组件 -->

       <!-- 购物车商品列表的标题区域 -->

       <!-- 商品列表区域 -->

       <!-- 结算区域 -->

     </view>

     <!-- 空白购物车区域 -->
     <view class="empty-cart" v-else>
       <image src="/static/cart_empty@2x.png" class="empty-img"></image>
       <text class="tip-text">空空如也~</text>
     </view>
   </template>
   ```
3. 美化空白购物车区域的样式：

   ```scss
   .empty-cart {
     display: flex;
     flex-direction: column;
     align-items: center;
     padding-top: 150px;

     .empty-img {
       width: 90px;
       height: 90px;
     }

     .tip-text {
       font-size: 12px;
       color: gray;
       margin-top: 15px;
     }
   }
   ```

## [#](https://applet-base-api-t.itheima.net/docs-uni-shop/9.cart.html#_9-4-分支的合并与提交)9.4 分支的合并与提交

1. 将 `cart` 分支进行本地提交：

   ```bash
   git add .
   git commit -m "完成了购物车的开发"
   ```
2. 将本地的 `cart` 分支推送到码云：

   ```bash
   git push -u origin cart
   ```
3. 将本地 `cart` 分支中的代码合并到 `master` 分支：

   ```bash
   git checkout master
   git merge cart
   git push
   ```
4. 删除本地的 `cart` 分支：

   ```bash
   git branch -d cart
   ```

# 10. 登录与支付

## [#](https://applet-base-api-t.itheima.net/docs-uni-shop/10.settle.html#_10-0-创建-settle-分支)10.0 创建 settle 分支

运行如下的命令，基于 `master` 分支在本地创建 `settle` 子分支，用来开发登录与支付相关的功能：

```bash
git checkout -b settle
```

## [#](https://applet-base-api-t.itheima.net/docs-uni-shop/10.settle.html#_10-1-点击结算按钮进行条件判断)10.1 点击结算按钮进行条件判断

> 说明：用户点击了结算按钮之后，需要先后判断**是否勾选了要结算的商品**、**是否选择了收货地址**、**是否登录**。

1. 在 `my-settle` 组件中，为结算按钮绑定点击事件处理函数：

   ```xml
   <!-- 结算按钮 -->
   <view class="btn-settle" @click="settlement">结算({{checkedCount}})</view>
   ```
2. 在 `my-settle` 组件的 methods 节点中声明 settlement 事件处理函数如下：

   ```js
   // 点击了结算按钮
   settlement() {
     // 1. 先判断是否勾选了要结算的商品
     if (!this.checkedCount) return uni.$showMsg('请选择要结算的商品！')

     // 2. 再判断用户是否选择了收货地址
     if (!this.addstr) return uni.$showMsg('请选择收货地址！')

     // 3. 最后判断用户是否登录了
     if (!this.token) return uni.$showMsg('请先登录！')
   }
   ```
3. 在 `my-settle` 组件中，使用 `mapGetters` 辅助函数，从 `m_user` 模块中将 `addstr` 映射到当前组件中使用：

   ```js
   export default {
     computed: {
       ...mapGetters('m_cart', ['total', 'checkedCount', 'checkedGoodsAmount']),
       // addstr 是详细的收货地址
       ...mapGetters('m_user', ['addstr']),
       isFullCheck() {
         return this.total === this.checkedCount
       },
     },
   }
   ```
4. 在 `store/user.js` 模块的 `state` 节点中，声明 `token` 字符串：

   ```js
   export default {
     // 开启命名空间
     namespaced: true,

     // state 数据
     state: () => ({
       // 收货地址
       address: JSON.parse(uni.getStorageSync('address') || '{}'),
       // 登录成功之后的 token 字符串
       token: '',
     }),

     // 省略其它代码
   }
   ```
5. 在 `my-settle` 组件中，使用 `mapState` 辅助函数，从 `m_user` 模块中将 `token` 映射到当前组件中使用：

   ```js
   // 按需从 vuex 中导入 mapState 辅助函数
   import { mapGetters, mapMutations, mapState } from 'vuex'

   export default {
     computed: {
       ...mapGetters('m_cart', ['total', 'checkedCount', 'checkedGoodsAmount']),
       ...mapGetters('m_user', ['addstr']),
       // token 是用户登录成功之后的 token 字符串
       ...mapState('m_user', ['token']),
       isFullCheck() {
         return this.total === this.checkedCount
       },
     },
   }
   ```

## [#](https://applet-base-api-t.itheima.net/docs-uni-shop/10.settle.html#_10-2-登录)10.2 登录

### [#](https://applet-base-api-t.itheima.net/docs-uni-shop/10.settle.html#_10-2-1-定义-my-页面的编译模式)10.2.1 定义 my 页面的编译模式

1. 点击 `微信开发者工具` 工具栏上的编译模式下拉菜单，选择 `添加编译模式`：
   ![](assets/image-20250401193121-dyi5zv0.png)
2. 勾选启动页面的路径之后，点击确定按钮：
   ![](https://applet-base-api-t.itheima.net/docs-uni-shop/10-4.4d78ed78.png)

### [#](https://applet-base-api-t.itheima.net/docs-uni-shop/10.settle.html#_10-2-2-实现登录和用户信息组件的按需展示)10.2.2 实现登录和用户信息组件的按需展示

1. 在 `components` 目录中新建**登录组件**：
2. 在 `components` 目录中新建**用户信息组件**：
   ![](https://applet-base-api-t.itheima.net/docs-uni-shop/10-2.ace63114.png)
3. 在 `my.vue` 页面中，通过 `mapState` 辅助函数，导入需要的 `token` 字符串：

   ```js
   import badgeMix from '@/mixins/tabbar-badge.js'
   // 1. 从 vuex 中按需导入 mapState 辅助函数
   import { mapState } from 'vuex'

   export default {
     mixins: [badgeMix],
     computed: {
       // 2. 从 m_user 模块中导入需要的 token 字符串
       ...mapState('m_user', ['token']),
     },
     data() {
       return {}
     },
   }
   ```
4. 在 `my.vue` 页面中，实现**登录组件**和**用户信息组件**的按需展示：

   ```xml
   <template>
     <view>

       <!-- 用户未登录时，显示登录组件 -->
       <my-login v-if="!token"></my-login>

       <!-- 用户登录后，显示用户信息组件 -->
       <my-userinfo v-else></my-userinfo>

     </view>
   </template>
   ```

### [#](https://applet-base-api-t.itheima.net/docs-uni-shop/10.settle.html#_10-2-3-实现登录组件的基本布局)10.2.3 实现登录组件的基本布局

1. 为 `my-login` 组件定义如下的 UI 结构：

   ```xml
   <template>
     <view class="login-container">
       <!-- 提示登录的图标 -->
       <uni-icons type="contact-filled" size="100" color="#AFAFAF"></uni-icons>
       <!-- 登录按钮 -->
       <button type="primary" class="btn-login">一键登录</button>
       <!-- 登录提示 -->
       <view class="tips-text">登录后尽享更多权益</view>
     </view>
   </template>
   ```
2. 美化登录组件的样式：

   ```scss
   .login-container {
     // 登录盒子的样式
     height: 750rpx;
     display: flex;
     flex-direction: column;
     align-items: center;
     justify-content: center;
     background-color: #f8f8f8;
     position: relative;
     overflow: hidden;

     // 绘制登录盒子底部的半椭圆造型
     &::after {
       content: ' ';
       display: block;
       position: absolute;
       width: 100%;
       height: 40px;
       left: 0;
       bottom: 0;
       background-color: white;
       border-radius: 100%;
       transform: translateY(50%);
     }

     // 登录按钮的样式
     .btn-login {
       width: 90%;
       border-radius: 100px;
       margin: 15px 0;
       background-color: #c00000;
     }

     // 按钮下方提示消息的样式
     .tips-text {
       font-size: 12px;
       color: gray;
     }
   }
   ```

### [#](https://applet-base-api-t.itheima.net/docs-uni-shop/10.settle.html#_10-2-4-点击登录按钮获取微信用户的基本信息)10.2.4 点击登录按钮获取微信用户的基本信息

> 需求描述：需要获取微信用户的**头像**、**昵称**等基本信息。

1. 为登录的 `button` 按钮绑定 `open-type="getUserInfo"` 属性，表示点击按钮时，希望获取用户的基本信息：

   ```xml
   <!-- 登录按钮 -->
   <!-- 可以从 @getuserinfo 事件处理函数的形参中，获取到用户的基本信息 -->
   <button type="primary" class="btn-login" open-type="getUserInfo" @getuserinfo="getUserInfo">一键登录</button>
   ```
2. 在 `methods` 节点中声明 `getUserInfo` 事件处理函数如下：

   ```js
   methods: {
     // 获取微信用户的基本信息
     getUserInfo(e) {
       // 判断是否获取用户信息成功
       if (e.detail.errMsg === 'getUserInfo:fail auth deny') return uni.$showMsg('您取消了登录授权！')

       // 获取用户信息成功， e.detail.userInfo 就是用户的基本信息
       console.log(e.detail.userInfo)
     }
   }
   ```

### [#](https://applet-base-api-t.itheima.net/docs-uni-shop/10.settle.html#_10-2-5-将用户的基本信息存储到-vuex)10.2.5 将用户的基本信息存储到 vuex

1. 在 `store/user.js` 模块的 state 节点中，声明 `userinfo` 的信息对象如下：

   ```js
   // state 数据
   state: () => ({
     // 收货地址
     // address: {}
     address: JSON.parse(uni.getStorageSync('address') || '{}'),
     // 登录成功之后的 token 字符串
     token: '',
     // 用户的基本信息
     userinfo: JSON.parse(uni.getStorageSync('userinfo') || '{}')
   }),
   ```
2. 在 `store/user.js` 模块的 mutations 节点中，声明如下的两个方法：

   ```js
   // 方法
   mutations: {
     // 省略其它代码...

     // 更新用户的基本信息
     updateUserInfo(state, userinfo) {
       state.userinfo = userinfo
       // 通过 this.commit() 方法，调用 m_user 模块下的 saveUserInfoToStorage 方法，将 userinfo 对象持久化存储到本地
       this.commit('m_user/saveUserInfoToStorage')
     },

     // 将 userinfo 持久化存储到本地
     saveUserInfoToStorage(state) {
       uni.setStorageSync('userinfo', JSON.stringify(state.userinfo))
     }
   }
   ```
3. 使用 `mapMutations` 辅助函数，将需要的方法映射到 `my-login` 组件中使用：

   ```js
   // 1. 按需导入 mapMutations 辅助函数
   import { mapMutations } from 'vuex'

   export default {
     data() {
       return {}
     },
     methods: {
       // 2. 调用 mapMutations 辅助方法，把 m_user 模块中的 updateUserInfo 映射到当前组件中使用
       ...mapMutations('m_user', ['updateUserInfo']),
       // 获取微信用户的基本信息
       getUserInfo(e) {
         // 判断是否获取用户信息成功
         if (e.detail.errMsg === 'getUserInfo:fail auth deny') return uni.$showMsg('您取消了登录授权！')
         // 获取用户信息成功， e.detail.userInfo 就是用户的基本信息
         // console.log(e.detail.userInfo)

         // 3. 将用户的基本信息存储到 vuex 中
         this.updateUserInfo(e.detail.userInfo)
       },
     },
   }
   ```

### [#](https://applet-base-api-t.itheima.net/docs-uni-shop/10.settle.html#_10-2-6-登录获取-token-字符串)10.2.6 登录获取 Token 字符串

> 需求说明：当获取到了微信用户的基本信息之后，还需要进一步**调用登录相关的接口**，从而**换取登录成功之后的 Token 字符串**。

1. 在 `getUserInfo` 方法中，预调用 `this.getToken()` 方法，同时把获取到的用户信息传递进去：

   ```js
   // 获取微信用户的基本信息
   getUserInfo(e) {
     // 判断是否获取用户信息成功
     if (e.detail.errMsg === 'getUserInfo:fail auth deny') return uni.$showMsg('您取消了登录授权！')

     // 将用户的基本信息存储到 vuex 中
     this.updateUserInfo(e.detail.userInfo)

     // 获取登录成功后的 Token 字符串
     this.getToken(e.detail)
   }
   ```
2. 在 `methods` 中定义 `getToken` 方法，调用登录相关的 API，实现登录的功能：

   ```js
   // 调用登录接口，换取永久的 token
   async getToken(info) {
     // 调用微信登录接口
     const [err, res] = await uni.login().catch(err => err)
     // 判断是否 uni.login() 调用失败
     if (err || res.errMsg !== 'login:ok') return uni.$showError('登录失败！')

     // 准备参数对象
     const query = {
       code: res.code,
       encryptedData: info.encryptedData,
       iv: info.iv,
       rawData: info.rawData,
       signature: info.signature
     }

     // 换取 token
     const { data: loginResult } = await uni.$http.post('/api/public/v1/users/wxlogin', query)
     if (loginResult.meta.status !== 200) return uni.$showMsg('登录失败！')
     uni.$showMsg('登录成功')
   }
   ```

### [#](https://applet-base-api-t.itheima.net/docs-uni-shop/10.settle.html#_10-2-7-将-token-存储到-vuex)10.2.7 将 Token 存储到 vuex

1. 在 `store/user.js` 模块的 `mutations` 节点中，声明如下的两个方法：

   ```js
   mutations: {
     // 省略其它代码...

     // 更新 token 字符串
     updateToken(state, token) {
       state.token = token
       // 通过 this.commit() 方法，调用 m_user 模块下的 saveTokenToStorage 方法，将 token 字符串持久化存储到本地
       this.commit('m_user/saveTokenToStorage')
     },

     // 将 token 字符串持久化存储到本地
     saveTokenToStorage(state) {
       uni.setStorageSync('token', state.token)
     }
   }
   ```
2. 修改 `store/user.js` 模块的 `state` 节点如下：

   ```js
   // state 数据
   state: () => ({
     // 收货地址
     address: JSON.parse(uni.getStorageSync('address') || '{}'),
     // 登录成功之后的 token 字符串
     token: uni.getStorageSync('token') || '',
     // 用户的基本信息
     userinfo: JSON.parse(uni.getStorageSync('userinfo') || '{}')
   }),
   ```
3. 在 `my-login` 组件中，把 vuex 中的 `updateToken` 方法映射到当前组件中使用：

   ```js
   methods: {
     // 1. 使用 mapMutations 辅助方法，把 m_user 模块中的 updateToken 方法映射到当前组件中使用
     ...mapMutations('m_user', ['updateUserInfo', 'updateToken'])

     // 省略其它代码...

     // 调用登录接口，换取永久的 token
     async getToken(info) {
       // 调用微信登录接口
       const [err, res] = await uni.login().catch(err => err)
       // 判断是否 uni.login() 调用失败
       if (err || res.errMsg !== 'login:ok') return uni.$showError('登录失败！')

       // 准备参数对象
       const query = {
         code: res.code,
         encryptedData: info.encryptedData,
         iv: info.iv,
         rawData: info.rawData,
         signature: info.signature
       }

       // 换取 token
       const { data: loginResult } = await uni.$http.post('/api/public/v1/users/wxlogin', query)
       if (loginResult.meta.status !== 200) return uni.$showMsg('登录失败！')

       // 2. 更新 vuex 中的 token
       this.updateToken(loginResult.message.token)
     }
   }
   ```

## [#](https://applet-base-api-t.itheima.net/docs-uni-shop/10.settle.html#_10-3-用户信息)10.3 用户信息

### [#](https://applet-base-api-t.itheima.net/docs-uni-shop/10.settle.html#_10-3-1-实现用户头像昵称区域的基本布局)10.3.1 实现用户头像昵称区域的基本布局

1. 在 `my-userinfo` 组件中，定义如下的 UI 结构：

   ```xml
   <template>
     <view class="my-userinfo-container">

       <!-- 头像昵称区域 -->
       <view class="top-box">
         <image src="" class="avatar"></image>
         <view class="nickname">xxx</view>
       </view>

     </view>
   </template>
   ```
2. 美化当前组件的样式：

   ```scss
   .my-userinfo-container {
     height: 100%;
     // 为整个组件的结构添加浅灰色的背景
     background-color: #f4f4f4;

     .top-box {
       height: 400rpx;
       background-color: #c00000;
       display: flex;
       flex-direction: column;
       align-items: center;
       justify-content: center;

       .avatar {
         display: block;
         width: 90px;
         height: 90px;
         border-radius: 45px;
         border: 2px solid white;
         box-shadow: 0 1px 5px black;
       }

       .nickname {
         color: white;
         font-weight: bold;
         font-size: 16px;
         margin-top: 10px;
       }
     }
   }
   ```
3. 在 `my.vue` 页面中，为最外层包裹性质的 `view` 容器，添加 `class="my-container"` 的类名，并美化样式如下：

   ```scss
   page,
   .my-container {
     height: 100%;
   }
   ```

### [#](https://applet-base-api-t.itheima.net/docs-uni-shop/10.settle.html#_10-3-2-渲染用户的头像和昵称)10.3.2 渲染用户的头像和昵称

1. 在 `my-userinfo` 组件中，通过 `mapState` 辅助函数，将需要的成员映射到当前组件中使用：

   ```js
   // 按需导入 mapState 辅助函数
   import { mapState } from 'vuex'

   export default {
     computed: {
       // 将 m_user 模块中的 userinfo 映射到当前页面中使用
       ...mapState('m_user', ['userinfo']),
     },
     data() {
       return {}
     },
   }
   ```
2. 将用户的头像和昵称渲染到页面中：

   ```xml
   <!-- 头像昵称区域 -->
   <view class="top-box">
     <image :src="userinfo.avatarUrl" class="avatar"></image>
     <view class="nickname">{{userinfo.nickName}}</view>
   </view>
   ```

### [#](https://applet-base-api-t.itheima.net/docs-uni-shop/10.settle.html#_10-3-3-渲染第一个面板区域)10.3.3 渲染第一个面板区域

1. 在 `my-userinfo` 组件中，定义如下的 UI 结构：

   ```xml
   <!-- 面板的列表区域 -->
   <view class="panel-list">
     <!-- 第一个面板 -->
     <view class="panel">
       <!-- panel 的主体区域 -->
       <view class="panel-body">
         <!-- panel 的 item 项 -->
         <view class="panel-item">
           <text>8</text>
           <text>收藏的店铺</text>
         </view>
         <view class="panel-item">
           <text>14</text>
           <text>收藏的商品</text>
         </view>
         <view class="panel-item">
           <text>18</text>
           <text>关注的商品</text>
         </view>
         <view class="panel-item">
           <text>84</text>
           <text>足迹</text>
         </view>
       </view>
     </view>

     <!-- 第二个面板 -->

     <!-- 第三个面板 -->
   </view>
   ```
2. 美化第一个面板的样式：

   ```scss
   .panel-list {
     padding: 0 10px;
     position: relative;
     top: -10px;

     .panel {
       background-color: white;
       border-radius: 3px;
       margin-bottom: 8px;

       .panel-body {
         display: flex;
         justify-content: space-around;

         .panel-item {
           display: flex;
           flex-direction: column;
           align-items: center;
           justify-content: space-around;
           font-size: 13px;
           padding: 10px 0;
         }
       }
     }
   }
   ```

### [#](https://applet-base-api-t.itheima.net/docs-uni-shop/10.settle.html#_10-3-4-渲染第二个面板区域)10.3.4 渲染第二个面板区域

1. 定义第二个面板区域的 UI 结构：

   ```xml
   <!-- 第二个面板 -->
   <view class="panel">
     <!-- 面板的标题 -->
     <view class="panel-title">我的订单</view>
     <!-- 面板的主体 -->
     <view class="panel-body">
       <!-- 面板主体中的 item 项 -->
       <view class="panel-item">
         <image src="/static/my-icons/icon1.png" class="icon"></image>
         <text>待付款</text>
       </view>
       <view class="panel-item">
         <image src="/static/my-icons/icon2.png" class="icon"></image>
         <text>待收货</text>
       </view>
       <view class="panel-item">
         <image src="/static/my-icons/icon3.png" class="icon"></image>
         <text>退款/退货</text>
       </view>
       <view class="panel-item">
         <image src="/static/my-icons/icon4.png" class="icon"></image>
         <text>全部订单</text>
       </view>
     </view>
   </view>
   ```
2. 对之前的 SCSS 样式进行改造，从而美化第二个面板的样式：

   ```scss
   .panel-list {
     padding: 0 10px;
     position: relative;
     top: -10px;

     .panel {
       background-color: white;
       border-radius: 3px;
       margin-bottom: 8px;

       .panel-title {
         line-height: 45px;
         padding-left: 10px;
         font-size: 15px;
         border-bottom: 1px solid #f4f4f4;
       }

       .panel-body {
         display: flex;
         justify-content: space-around;

         .panel-item {
           display: flex;
           flex-direction: column;
           align-items: center;
           justify-content: space-around;
           font-size: 13px;
           padding: 10px 0;

           .icon {
             width: 35px;
             height: 35px;
           }
         }
       }
     }
   }
   ```

### [#](https://applet-base-api-t.itheima.net/docs-uni-shop/10.settle.html#_10-3-5-渲染第三个面板区域)10.3.5 渲染第三个面板区域

1. 定义第三个面板区域的 UI 结构：

   ```xml
   <!-- 第三个面板 -->
   <view class="panel">
     <view class="panel-list-item">
       <text>收货地址</text>
       <uni-icons type="arrowright" size="15"></uni-icons>
     </view>
     <view class="panel-list-item">
       <text>联系客服</text>
       <uni-icons type="arrowright" size="15"></uni-icons>
     </view>
     <view class="panel-list-item">
       <text>退出登录</text>
       <uni-icons type="arrowright" size="15"></uni-icons>
     </view>
   </view>
   ```
2. 美化第三个面板区域的样式：

   ```scss
   .panel-list-item {
     height: 45px;
     display: flex;
     justify-content: space-between;
     align-items: center;
     font-size: 15px;
     padding: 0 10px;
   }
   ```

### [#](https://applet-base-api-t.itheima.net/docs-uni-shop/10.settle.html#_10-3-6-实现退出登录的功能)10.3.6 实现退出登录的功能

1. 为第三个面板区域中的 `退出登录` 项绑定 `click` 点击事件处理函数：

   ```xml
   <view class="panel-list-item" @click="logout">
     <text>退出登录</text>
     <uni-icons type="arrowright" size="15"></uni-icons>
   </view>
   ```
2. 在 `my-userinfo` 组件的 `methods` 节点中定义 `logout` 事件处理函数：

   ```js
   // 退出登录
   async logout() {
     // 询问用户是否退出登录
     const [err, succ] = await uni.showModal({
       title: '提示',
       content: '确认退出登录吗？'
     }).catch(err => err)

     if (succ && succ.confirm) {
        // 用户确认了退出登录的操作
        // 需要清空 vuex 中的 userinfo、token 和 address
        this.updateUserInfo({})
        this.updateToken('')
        this.updateAddress({})
     }
   }
   ```
3. 使用 `mapMutations` 辅助方法，将需要用到的 mutations 方法映射到当前组件中：

   ```js
   // 按需导入辅助函数
   import { mapState, mapMutations } from 'vuex'

   export default {
     methods: {
       ...mapMutations('m_user', ['updateUserInfo', 'updateToken', 'updateAddress']),
     },
   }
   ```

## [#](https://applet-base-api-t.itheima.net/docs-uni-shop/10.settle.html#_10-4-三秒后自动跳转)10.4 三秒后自动跳转

### [#](https://applet-base-api-t.itheima.net/docs-uni-shop/10.settle.html#_10-4-1-三秒后自动跳转到登录页面)10.4.1 三秒后自动跳转到登录页面

> 需求描述：在购物车页面，当用户点击 “结算” 按钮时，**如果用户没有登录，则 3 秒后自动跳转到登录页面**

1. 在 `my-settle` 组件的 `methods` 节点中，声明一个叫做 `showTips` 的方法，专门用来展示倒计时的提示消息：

   ```js
   // 展示倒计时的提示消息
   showTips(n) {
     // 调用 uni.showToast() 方法，展示提示消息
     uni.showToast({
       // 不展示任何图标
       icon: 'none',
       // 提示的消息
       title: '请登录后再结算！' + n + ' 秒后自动跳转到登录页',
       // 为页面添加透明遮罩，防止点击穿透
       mask: true,
       // 1.5 秒后自动消失
       duration: 1500
     })
   }
   ```
2. 在 `data` 节点中声明倒计时的秒数：

   ```js
   data() {
     return {
       // 倒计时的秒数
       seconds: 3
     }
   }
   ```
3. 改造 `结算` 按钮的 `click` 事件处理函数，如果用户没有登录，则**预调用**一个叫做 `delayNavigate` 的方法，进行倒计时的导航跳转：

   ```js
   // 点击了结算按钮
   settlement() {
     // 1. 先判断是否勾选了要结算的商品
     if (!this.checkedCount) return uni.$showMsg('请选择要结算的商品！')

     // 2. 再判断用户是否选择了收货地址
     if (!this.addstr) return uni.$showMsg('请选择收货地址！')

     // 3. 最后判断用户是否登录了，如果没有登录，则调用 delayNavigate() 进行倒计时的导航跳转
     // if (!this.token) return uni.$showMsg('请先登录！')
     if (!this.token) return this.delayNavigate()
   },
   ```
4. 定义 `delayNavigate` 方法，初步实现**倒计时的提示功能**：

   ```js
   // 延迟导航到 my 页面
   delayNavigate() {
     // 1. 展示提示消息，此时 seconds 的值等于 3
     this.showTips(this.seconds)

     // 2. 创建定时器，每隔 1 秒执行一次
     setInterval(() => {
       // 2.1 先让秒数自减 1
       this.seconds--
       // 2.2 再根据最新的秒数，进行消息提示
       this.showTips(this.seconds)
     }, 1000)
   },
   ```

   > 上述代码的问题：**定时器不会自动停止**，此时秒数会出现等于 0 或小于 0 的情况！
   >
5. 在 `data` 节点中声明定时器的 Id 如下：

   ```js
   data() {
     return {
       // 倒计时的秒数
       seconds: 3,
       // 定时器的 Id
       timer: null
     }
   }
   ```
6. 改造 `delayNavigate` 方法如下：

   ```js
   // 延迟导航到 my 页面
   delayNavigate() {
     this.showTips(this.seconds)

     // 1. 将定时器的 Id 存储到 timer 中
     this.timer = setInterval(() => {
       this.seconds--

       // 2. 判断秒数是否 <= 0
       if (this.seconds <= 0) {
         // 2.1 清除定时器
         clearInterval(this.timer)

         // 2.2 跳转到 my 页面
         uni.switchTab({
           url: '/pages/my/my'
         })

         // 2.3 终止后续代码的运行（当秒数为 0 时，不再展示 toast 提示消息）
         return
       }

       this.showTips(this.seconds)
     }, 1000)
   },
   ```

   > 上述代码的问题：**seconds 秒数不会被重置**，导致第 2 次，3 次，n 次 的倒计时跳转功能无法正常工作
   >
7. 进一步改造 `delayNavigate` 方法，在执行此方法时，立即将 `seconds` 秒数重置为 `3` 即可：

   ```js
   // 延迟导航到 my 页面
   delayNavigate() {
     // 把 data 中的秒数重置成 3 秒
     this.seconds = 3
     this.showTips(this.seconds)

     this.timer = setInterval(() => {
       this.seconds--

       if (this.seconds <= 0) {
         clearInterval(this.timer)
         uni.switchTab({
           url: '/pages/my/my'
         })
         return
       }

       this.showTips(this.seconds)
     }, 1000)
   }
   ```

### [#](https://applet-base-api-t.itheima.net/docs-uni-shop/10.settle.html#_10-4-2-登录成功之后再返回之前的页面)10.4.2 登录成功之后再返回之前的页面

> 核心实现思路：在自动跳转到登录页面成功之后，把**返回页面的信息存储到 vuex 中**，从而方便登录成功之后，根据返回页面的信息重新跳转回去。

> 返回页面的信息对象，**主要包含 { openType, from } 两个属性**，其中 openType 表示**以哪种方式导航回之前的页面**；from 表示**之前页面的 url 地址**；

1. 在 `store/user.js` 模块的 `state` 节点中，声明一个叫做 `redirectInfo` 的对象如下：

   ```js
   // state 数据
   state: () => ({
     // 收货地址
     address: JSON.parse(uni.getStorageSync('address') || '{}'),
     // 登录成功之后的 token 字符串
     token: uni.getStorageSync('token') || '',
     // 用户的基本信息
     userinfo: JSON.parse(uni.getStorageSync('userinfo') || '{}'),
     // 重定向的 object 对象 { openType, from }
     redirectInfo: null
   }),
   ```
2. 在 `store/user.js` 模块的 `mutations` 节点中，声明一个叫做 `updateRedirectInfo` 的方法：

   ```js
   mutations: {
     // 更新重定向的信息对象
     updateRedirectInfo(state, info) {
       state.redirectInfo = info
     }
   }
   ```
3. 在 `my-settle` 组件中，通过 `mapMutations` 辅助方法，把 `m_user` 模块中的 `updateRedirectInfo` 方法映射到当前页面中使用：

   ```js
   methods: {
     // 把 m_user 模块中的 updateRedirectInfo 方法映射到当前页面中使用
     ...mapMutations('m_user', ['updateRedirectInfo']),
   }
   ```
4. 改造 `my-settle` 组件 methods 节点中的 `delayNavigate` 方法，当成功跳转到 `my 页面` 之后，将重定向的信息对象存储到 vuex 中：

   ```js
   // 延迟导航到 my 页面
   delayNavigate() {
     // 把 data 中的秒数重置成 3 秒
     this.seconds = 3
     this.showTips(this.seconds)

     this.timer = setInterval(() => {
       this.seconds--

       if (this.seconds <= 0) {
         // 清除定时器
         clearInterval(this.timer)
         // 跳转到 my 页面
         uni.switchTab({
           url: '/pages/my/my',
           // 页面跳转成功之后的回调函数
           success: () => {
             // 调用 vuex 的 updateRedirectInfo 方法，把跳转信息存储到 Store 中
             this.updateRedirectInfo({
               // 跳转的方式
               openType: 'switchTab',
               // 从哪个页面跳转过去的
               from: '/pages/cart/cart'
             })
           }
         })

         return
       }

       this.showTips(this.seconds)
     }, 1000)
   }
   ```
5. 在 `my-login` 组件中，通过 `mapState` 和 `mapMutations` 辅助方法，将 vuex 中需要的数据和方法，映射到当前页面中使用：

   ```js
   // 按需导入辅助函数
   import { mapMutations, mapState } from 'vuex'

   export default {
     computed: {
       // 调用 mapState 辅助方法，把 m_user 模块中的数据映射到当前用组件中使用
       ...mapState('m_user', ['redirectInfo']),
     },
     methods: {
       // 调用 mapMutations 辅助方法，把 m_user 模块中的方法映射到当前组件中使用
       ...mapMutations('m_user', ['updateUserInfo', 'updateToken', 'updateRedirectInfo']),
     },
   }
   ```
6. 改造 `my-login` 组件中的 `getToken` 方法，当登录成功之后，预调用 `this.navigateBack()` 方法返回登录之前的页面：

   ```js
   // 调用登录接口，换取永久的 token
   async getToken(info) {
     // 省略其它代码...

     // 判断 vuex 中的 redirectInfo 是否为 null
     // 如果不为 null，则登录成功之后，需要重新导航到对应的页面
     this.navigateBack()
   }
   ```
7. 在 `my-login` 组件中，声明 `navigateBack` 方法如下：

   ```js
   // 返回登录之前的页面
   navigateBack() {
     // redirectInfo 不为 null，并且导航方式为 switchTab
     if (this.redirectInfo && this.redirectInfo.openType === 'switchTab') {
       // 调用小程序提供的 uni.switchTab() API 进行页面的导航
       uni.switchTab({
         // 要导航到的页面地址
         url: this.redirectInfo.from,
         // 导航成功之后，把 vuex 中的 redirectInfo 对象重置为 null
         complete: () => {
           this.updateRedirectInfo(null)
         }
       })
     }
   }
   ```

## [#](https://applet-base-api-t.itheima.net/docs-uni-shop/10.settle.html#_10-5-微信支付)10.5 微信支付

### [#](https://applet-base-api-t.itheima.net/docs-uni-shop/10.settle.html#_10-5-1-在请求头中添加-token-身份认证的字段)10.5.1 在请求头中添加 Token 身份认证的字段

1. 原因说明：**只有在登录之后才允许调用支付相关的接口**，所以必须为有权限的接口添加身份认证的请求头字段
2. 打开项目根目录下的 `main.js`，改造 `$http.beforeRequest` 请求拦截器中的代码如下：

   ```js
   // 请求开始之前做一些事情
   $http.beforeRequest = function(options) {
     uni.showLoading({
       title: '数据加载中...',
     })

     // 判断请求的是否为有权限的 API 接口
     if (options.url.indexOf('/my/') !== -1) {
       // 为请求头添加身份认证字段
       options.header = {
         // 字段的值可以直接从 vuex 中进行获取
         Authorization: store.state.m_user.token,
       }
     }
   }
   ```

### [#](https://applet-base-api-t.itheima.net/docs-uni-shop/10.settle.html#_10-5-2-微信支付的流程)10.5.2 微信支付的流程

1. **创建订单**

   - 请求创建订单的 API 接口：把（订单金额、收货地址、订单中包含的商品信息）发送到服务器
   - 服务器响应的结果：*订单编号*
2. **订单预支付**

   - 请求订单预支付的 API 接口：把（订单编号）发送到服务器
   - 服务器响应的结果：*订单预支付的参数对象*，里面包含了订单支付相关的必要参数
3. **发起微信支付**

   - 调用 `uni.requestPayment()` 这个 API，发起微信支付；把步骤 2 得到的 “订单预支付对象” 作为参数传递给 `uni.requestPayment()` 方法
   - 监听 `uni.requestPayment()` 这个 API 的 `success`，`fail`，`complete` 回调函数

### [#](https://applet-base-api-t.itheima.net/docs-uni-shop/10.settle.html#_10-5-3-创建订单)10.5.3 创建订单

1. 改造 `my-settle` 组件中的 `settlement` 方法，当前三个判断条件通过之后，调用实现微信支付的方法：

   ```js
   // 点击了结算按钮
   settlement() {
     // 1. 先判断是否勾选了要结算的商品
     if (!this.checkedCount) return uni.$showMsg('请选择要结算的商品！')

     // 2. 再判断用户是否选择了收货地址
     if (!this.addstr) return uni.$showMsg('请选择收货地址！')

     // 3. 最后判断用户是否登录了
     // if (!this.token) return uni.$showMsg('请先登录！')
     if (!this.token) return this.delayNavigate()

     // 4. 实现微信支付功能
     this.payOrder()
   },
   ```
2. 在 `my-settle` 组件中定义 `payOrder` 方法如下，先实现创建订单的功能：

   ```js
   // 微信支付
   async payOrder() {
     // 1. 创建订单
     // 1.1 组织订单的信息对象
     const orderInfo = {
       // 开发期间，注释掉真实的订单价格，
       // order_price: this.checkedGoodsAmount,
       // 写死订单总价为 1 分钱
       order_price: 0.01,
       consignee_addr: this.addstr,
       goods: this.cart.filter(x => x.goods_state).map(x => ({ goods_id: x.goods_id, goods_number: x.goods_count, goods_price: x.goods_price }))
     }
     // 1.2 发起请求创建订单
     const { data: res } = await uni.$http.post('/api/public/v1/my/orders/create', orderInfo)
     if (res.meta.status !== 200) return uni.$showMsg('创建订单失败！')
     // 1.3 得到服务器响应的“订单编号”
     const orderNumber = res.message.order_number

      // 2. 订单预支付

      // 3. 发起微信支付
    }
   ```

### [#](https://applet-base-api-t.itheima.net/docs-uni-shop/10.settle.html#_10-5-4-订单预支付)10.5.4 订单预支付

1. 改造 `my-settle` 组件的 `payOrder` 方法，实现订单预支付功能：

   ```js
   // 微信支付
   async payOrder() {
     // 1. 创建订单
     // 1.1 组织订单的信息对象
     const orderInfo = {
       // 开发期间，注释掉真实的订单价格，
       // order_price: this.checkedGoodsAmount,
       // 写死订单总价为 1 分钱
       order_price: 0.01,
       consignee_addr: this.addstr,
       goods: this.cart.filter(x => x.goods_state).map(x => ({ goods_id: x.goods_id, goods_number: x.goods_count, goods_price: x.goods_price }))
     }
     // 1.2 发起请求创建订单
     const { data: res } = await uni.$http.post('/api/public/v1/my/orders/create', orderInfo)
     if (res.meta.status !== 200) return uni.$showMsg('创建订单失败！')
     // 1.3 得到服务器响应的“订单编号”
     const orderNumber = res.message.order_number

     // 2. 订单预支付
     // 2.1 发起请求获取订单的支付信息
     const { data: res2 } = await uni.$http.post('/api/public/v1/my/orders/req_unifiedorder', { order_number: orderNumber })
     // 2.2 预付订单生成失败
     if (res2.meta.status !== 200) return uni.$showError('预付订单生成失败！')
     // 2.3 得到订单支付相关的必要参数
     const payInfo = res2.message.pay

      // 3. 发起微信支付
    }
   ```

### [#](https://applet-base-api-t.itheima.net/docs-uni-shop/10.settle.html#_10-5-5-发起微信支付)10.5.5 发起微信支付

1. 改造 `my-settle` 组件的 `payOrder` 方法，实现微信支付的功能：

   ```js
   // 微信支付
   async payOrder() {
     // 1. 创建订单
     // 1.1 组织订单的信息对象
     const orderInfo = {
       // 开发期间，注释掉真实的订单价格，
       // order_price: this.checkedGoodsAmount,
       // 写死订单总价为 1 分钱
       order_price: 0.01,
       consignee_addr: this.addstr,
       goods: this.cart.filter(x => x.goods_state).map(x => ({ goods_id: x.goods_id, goods_number: x.goods_count, goods_price: x.goods_price }))
     }
     // 1.2 发起请求创建订单
     const { data: res } = await uni.$http.post('/api/public/v1/my/orders/create', orderInfo)
     if (res.meta.status !== 200) return uni.$showMsg('创建订单失败！')
     // 1.3 得到服务器响应的“订单编号”
     const orderNumber = res.message.order_number

      // 2. 订单预支付
      // 2.1 发起请求获取订单的支付信息
      const { data: res2 } = await uni.$http.post('/api/public/v1/my/orders/req_unifiedorder', { order_number: orderNumber })
      // 2.2 预付订单生成失败
      if (res2.meta.status !== 200) return uni.$showError('预付订单生成失败！')
      // 2.3 得到订单支付相关的必要参数
      const payInfo = res2.message.pay

      // 3. 发起微信支付
      // 3.1 调用 uni.requestPayment() 发起微信支付
      const [err, succ] = await uni.requestPayment(payInfo)
      // 3.2 未完成支付
      if (err) return uni.$showMsg('订单未支付！')
      // 3.3 完成了支付，进一步查询支付的结果
      const { data: res3 } = await uni.$http.post('/api/public/v1/my/orders/chkOrder', { order_number: orderNumber })
      // 3.4 检测到订单未支付
      if (res3.meta.status !== 200) return uni.$showMsg('订单未支付！')
      // 3.5 检测到订单支付完成
      uni.showToast({
        title: '支付完成！',
        icon: 'success'
      })
    }
   ```

## [#](https://applet-base-api-t.itheima.net/docs-uni-shop/10.settle.html#_10-6-分支的合并与提交)10.6 分支的合并与提交

1. 将 `settle` 分支进行本地提交：

   ```bash
   git add .
   git commit -m "完成了登录和支付功能的开发"
   ```
2. 将本地的 `settle` 分支推送到码云：

   ```bash
   git push -u origin settle
   ```
3. 将本地 `settle` 分支中的代码合并到 `master` 分支：

   ```bash
   git checkout master
   git merge settle
   git push
   ```
4. 删除本地的 `settle` 分支：

   ```bash
   git branch -d settle
   ```

# 11. 发布

## [#](https://applet-base-api-t.itheima.net/docs-uni-shop/11.publish.html#_11-1-为什么要发布)11.1 为什么要发布

1. 小程序只有发布之后，才能被用户搜索并使用
2. 开发期间的小程序为了便于调试，含有 sourcemap 相关的文件，并且代码没有被压缩，因此体积较大，不适合直接当作线上版本进行发布
3. 通过执行 “小程序发布”，能够优化小程序的体积，提高小程序的运行性能

## [#](https://applet-base-api-t.itheima.net/docs-uni-shop/11.publish.html#_11-2-发布小程序的流程)11.2 发布小程序的流程

1. 点击 `HBuilderX` 菜单栏上的 `发行` -\> `小程序-微信(仅适用于uni-app)`：
   ![](https://applet-base-api-t.itheima.net/docs-uni-shop/11-1.9cdf19c7.png)
2. 在弹出框中填写要发布的**小程序的名称**和**AppId**之后，点击发行按钮：
   ![](assets/image-20250401193133-tvb4y4v.png)
3. 在 `HBuilderX` 的控制台中**查看小程序发布编译的进度**：
   ![](https://applet-base-api-t.itheima.net/docs-uni-shop/11-3.567c1979.png)
4. 发布编译完成之后，会自动打开一个新的**微信开发者工具界面**，此时，点击工具栏上的上传按钮：
   ![](https://applet-base-api-t.itheima.net/docs-uni-shop/11-4.9c24f0ee.png)
5. 填写**版本号**和**项目备注**之后，点击**上传**按钮：
   ![](assets/image-20250401193133-u5ua0gz.png)
6. 上传完成之后，会出现如下的提示消息，直接点击**确定**按钮即可：
   ![](https://applet-base-api-t.itheima.net/docs-uni-shop/11-6.d5c408c3.png)
7. 通过微信开发者工具上传的代码，默认处于**版本管理**的**开发版本**列表中，如图所示：
   ![](https://applet-base-api-t.itheima.net/docs-uni-shop/11-7.ec9045bc.png)
8. 将 `开发版本提交审核` -\> 再将 `审核通过的版本发布上线`，即可实现小程序的发布和上线：
   ![](https://applet-base-api-t.itheima.net/docs-uni-shop/11-8.a251f8b8.png)

## [#](https://applet-base-api-t.itheima.net/docs-uni-shop/11.publish.html#_11-3-发布为-android-app-的流程)11.3 发布为 Android App 的流程

1. 点击 HBuilderX 状态栏左侧的**未登录**按钮，弹出登录的对话框：
   ![](assets/image-20250401193133-uiu2ueo.png)
2. 在弹出的登录对话框中，填写**账号**和**密码**之后，**点击登录**即可：
   ![](https://applet-base-api-t.itheima.net/docs-uni-shop/11-10.438598e0.png)
3. 打开项目根目录中的 `manifest.json` 配置文件，在**基础配置**面板中，获取**uni-app 应用标识**，并填写**应用名称**：
   ![](https://applet-base-api-t.itheima.net/docs-uni-shop/11-11.dc32f303.png)
4. 切换到 **App 图标配置**面板，点击**浏览**按钮，选择合适的图片之后，再点击**自动生成所有图标并替换**即可：
   ![](https://applet-base-api-t.itheima.net/docs-uni-shop/11-12.e3157064.png)
5. 点击菜单栏上的 **发行** -\> **原生 App-云打包**：
   ![](https://applet-base-api-t.itheima.net/docs-uni-shop/11-13.d176ba65.png)
6. **勾选打包配置**如下：
   ![](https://applet-base-api-t.itheima.net/docs-uni-shop/11-14.ddd7bcc3.png)
7. 在**控制台**中**查看打包的进度信息**：
   ![](https://applet-base-api-t.itheima.net/docs-uni-shop/11-15.c8d3b328.png)
8. 点击链接**下载 apk 的安装包**，并**安装到 Android 手机中**查看打包的效果。

> 注意：由于开发期间**没有进行多端适配**，所以有些功能在 App 中无法正常运行，例如：**选择收货地址**、**微信登录**、**微信支付**
