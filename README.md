# 王森的简历

男 25岁 本科 工作年限2年 
18511403370 [hitbear518@gmail.com](mailto:hitbear518@gmail.com)
已离职，可随时到岗

##职业意向
互联网行业 iOS工程师 北京
___

## 工作经历
北京掌上先机网络科技有限公司
移动研发工程师 2013.04 — 2015.09

公司简介：公司的业务是为电商平台的卖家提供 ERP 产品 SaaS 服务，主要的产品是旺店通 ERP，帮助客户处理订单和商品	的进销存业务。

工作职责：主要开发与 ERP 产品相关的 Android PDA 程序和其他 Android 程序，帮助客户进行移动办公，完成仓储、订单等相关业务；另外还有与此相关的测试、文档编写、需求沟通、用户反馈、硬件采购等。

## 项目经历
### [iOS 记账 app](https://github.com/hitbear518/SwiftAccountBook)
独立完成的第一个 iOS app，统计每月的收入支出；
> * 可自定义每月开始记账的日期（比如发工资的日期）
> * 支持多标签（比如 固定支出＋房租）
> * 可选择按照日期或标签排序（可以快速了解当天的支出，或者本月食品总支出等）
> * 使用 CoreData 存储数据，使用 NSUserDefaults 存储设置
> * 滑动切换月份，UI层级 UITabBarController -> UINavigationController -> UIPageViewController -> 收入支出界面。
> * 自动切换主题（支出红色、收入绿色、统计与设置蓝色）
> * 列表界面点击 UITableView的 Cell 切换展开与收拢
> * 添加记录时，标签多选按钮与标签输入框同步，使用逗号分割（点击按钮自动添加或删除文字，输入文字自动选中或反选按钮）
> * 设置界面点击设置开始记账日期，自动添加或删除日期选择 Cell
> * 添加纪录界面，点击选择日期模拟 ActionSheet 效果。（自定义 UIPresentatioinController）

[*部分截图与说明*](https://docs.google.com/document/d/1rSvodjM1kegTqUO5qTRR7bT5UaxRzmLjSx037bIxBqM/edit?usp=sharing)


### 旺店通 PDA app
在多种硬件规格、系统版本的 Android PDA 上开发 ERP app，早期使用 NDK 调用与 PC 端相同的 C++ 接口以及条码扫描接口，后期切换至 PHP 后端与广播条码扫描接口。与客户、销售、实施人员确定需求，完成客户要求的下单、盘点、出入库、验货等业务。根据条码扫描广播，使用 Retrofit 获取后端数据、Gson 解析成不同的类，并按照不同的数据类自动触发 EventBus 事件处理业务。使用依赖注入（Butter Kinfe, IDE 自动生成代码）加速开发。
使用BugHD SDK 上传分析 Crash。
[*具体功能可见说明文档*](https://docs.google.com/document/d/1gICC6U-cLZVtTWrIJgedQl-biNbvvsLatf25GvCiDgA/edit?usp=sharing)

### 店通 ERP 查询 app
与之前的 PDA app 采用相同的项目结构，除此之外，使用 Dagger2 加速开发。为企业主开发的业绩查询软件，满足客户在移动端查询销售、采购、顾客、账单等统计信息的需求
使用BugHD SDK 上传分析 Crash。
___

## 教育经历
郑州大学升达经贸管理学院
本科 · 软件工程

## 自我描述
> * 语言基础：熟悉 Swift, Objective - C，C，iOS 半年开发经验；Java（Android）两年开发经验。
> * iOS相关：了解 KVC，KVO，Assoicated Object, Method Swizzling，Core Animation，熟悉 AutoLayout。
> * 英语：能很好地阅读英文文档和 Blog ，CET－6。
> * 工具：熟悉 Linux 命令行，Vim，会使用 Git／SVN。
> * 设计：阅读过 Human Interface Guide Line， Material Design 手册，使用Sketch 画过图标。
> * 算法：参加过 ACM 相关比赛并获奖。

