****
如果帮助到你，star一下，谢谢你
武汉加油，中国加油
****
本代码使用方式 https://blog.csdn.net/cyz52/article/details/104177981
或者下载后阅读帮助md或txt文件
## 版本
- [x] python3 V4
- [x] 基于https://github.com/cycz/jdBuyMask]github V2版本制作 不支持V3的方糖推送

## 使用方法
- [x]修改的地方（config.ini）：
-  邮箱、地区id

- [x] 商品skuid修改方法（config.ini）：
-  谷歌（内核）浏览器要监控的商品url
-  一、按F12 ，点开Nework
-  二、点击需要的商品 和所在的地区
-  三、ctrl+f搜索 stock并点击
-  四、复制skuid
-  五、修改或者添加在config.ini内的skuids

- [x] 地区id修改方法（config.ini）：
-  一、用谷歌（内核）浏览器随意打开一个京东的网页
-  二、右键你的收货地址并点击审查元素
-  三、复制那串数字，并把-修改成_
-  四、修改在config.ini内的areaid

## 运行图片
[attachimg]1788153[/attachimg]
[attachimg]1788154[/attachimg]
## 功能
- [x] 确认是否有货
- [x] 有货自动下单
- [x] 邮件通知
- [x] 扫码登陆
- [x] 无限个商品支持

## 更新记录
- 【2020.02.07】增加扫码登陆，自动保存cookie
- 【2020.02.07】V4版本，解决商品个数限制
-   Code By Rlacat
------

- 【2020.02.06】V2版本，刷新更快更频繁，通过配置文件添加商品和地区id。
- 【2020.02.06】提交失败之后会继续不会暂停。
- 【2020.02.06】购物车有套装商品导致解析skuid错误。
- 【2020.02.05】商品有货，但是该商品已下柜，提交会报错，对部分代码进行了优化。
-   Code By cycz
## 反馈问题

- 如果有红包先花掉再开脚本，不然可能需要支付密码
- 其他问题Github提issues