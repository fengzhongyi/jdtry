# 京东试用 Chrome 拓展
本拓展自动获取所有可申请的商品，并可一键申请指定的试用商品。

## 界面截图
![界面](./img/interface.png)

## 主要功能
* 获取关注商铺数量
* 清空关注商铺
* 搜索京东试用所有商品
* 检索是否有成功申请试用的商品
* 一键申请试用商品

## 安装
```js
# 安装依赖
yarn
# 生成拓展文件
yarn build
# chrome 打开开发者模式加载拓展（位于build文件）
# 或者直接下载 release 里已编译好的 crx 进行解压安装
```

## 使用方法
1. 打开网页登录京东账号
2. 点击 **搜索商品** 搜索并导入试用商品（可在任务设置里设置搜索范围）
3. 点击 **一键申请** 即可申请所有试用商品

## 说明
* 每人每天可申请的试用商品上限为300个
* 每人可关注的店铺上限为500个
>没几天就满了，所以需要及时清理
* 定时启动以及自动登录还未完成，**TODO**
* 使用者多的时候再考虑加入谷歌商店
