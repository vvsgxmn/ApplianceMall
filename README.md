## 接毕业设计和论文

### 作者微信：vvsgxmn  (支持修改、 部署调试、 支持代做毕设)

### 接网站建设、小程序

### 选题+开题报告+任务书+程序定制+安装调试+论文+答辩ppt 都可以做

### 购买地址：[https://www.vvxx.love](https://www.vvxx.love)（vv毕设网）

### 支持 **一键生成 UML 图**：上传项目压缩包即可自动产出功能模块图、用例图、流程图、E-R 图、时序图等全套毕设图表。

### 提供 **免费配套软件下载 + 安装说明 + 部署教程**

![vv毕设网 - 一键画图](https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/uml-draw.png)

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/image-20260825133349317.png" alt="image-20260825133349317" />

⚠️ Bug添加微信**免费修复**，免费修复。其他平台的私信一律不管（微信方便发送文件）

---

# 基于SpringBoot+Vue的电器商城系统

![Spring Boot](https://img.shields.io/badge/-Spring%20Boot-6DB33F?style=flat-square&logo=spring-boot&logoColor=white) ![Vue3](https://img.shields.io/badge/-Vue3-grey?style=flat-square) ![MySQL](https://img.shields.io/badge/-MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white) ![MyBatis](https://img.shields.io/badge/-MyBatis-000000?style=flat-square&logo=mybatis&logoColor=white) 

## 项目介绍

本系统是一款面向全屋智能家电电商场景的综合商城，针对传统家电零售中参数难比对、送装脱节、优惠活动分散、以旧换新流程不透明等问题，把多级分类选购、多规格 SKU 库存售价联动、购物车结算、满减优惠券核销、钱包余额支付、大件物流与上门安装派工、以旧换新评估工单，以及通义千问 AI 智电导购整合到同一平台。

系统采用 Spring Boot + Vue 3 前后端分离架构，区分普通用户与管理员双角色：用户端完成浏览选购、下单支付与履约跟踪；运营中台提供 ECharts 经营看板、商品/分类/品牌维护、订单发货与安装派工、优惠券与轮播运营、评价资讯与用户管理。业务状态从待支付、已支付、已发货、安装中到已完成可全程追踪，取消未支付订单时回滚库存与优惠券，适合作为毕设、课设与家电商城学习参考。

## 主要功能模块

- **用户认证与权限**：支持普通用户与管理员统一登录注册，JWT 无状态鉴权；登录后按角色自动跳转商城首页或数据看板，中台路由与接口双重隔离，防止越权访问
- **首页与家电选购**：首页展示轮播海报、分类入口与热销推荐；家电列表支持分类、品牌、关键词检索及销量/价格排序，卡片呈现能效等级、售价与销量，降低比价成本
- **商品详情与 SKU**：采用 SPU + SKU 双层设计，切换规格时实时刷新售价与库存；支持加购、收藏、浏览足迹写入与买家评价查看，保证规格级下单准确
- **购物车与结算支付**：购物车可改数量、勾选结算；确认订单时选择收货/安装地址、可用优惠券，勾选上门安装并预约时段，使用钱包余额支付；未支付可取消并回滚库存与券权益
- **订单跟踪与送装一体**：用户按状态筛选我的订单（待支付/已支付/已发货/安装中/已完成）；中台录入物流发货、指派安装师傅与电话并更新进度，用户端可见履约信息
- **以旧换新服务**：用户提交旧机品类、成色与说明工单，管理员评估确认；形成旧机回收评估与换新抵扣说明闭环，响应绿色家电换新场景
- **AI 智电导购**：集成通义千问，围绕户型面积、预算与能效偏好给出选型建议；未配置密钥或接口异常时自动降级为本地规则推荐，保障演示与日常可用
- **个人中心与会员运营**：维护资料与钱包、收货地址、优惠券包、收藏夹与浏览足迹；支持保养科普与公告阅读，形成选购后的持续服务触点
- **运营数据看板**：管理员查看累计销售、今日成交、订单量、在售商品、会员数、待派工安装与库存预警等 KPI，以及近七日销售/订单趋势、商品排行与履约质量看板
- **商品与履约中台**：商品上下架与多规格 SKU 维护，分类/品牌档案管理；订单发货与安装派工，以旧换新审核，优惠券活动、轮播海报、评价监管与资讯公告发布，以及用户启停与余额核验

## 技术架构

- **后端**：Spring Boot + MyBatis-Plus + JWT + Lombok
- **前端**：Vue 3 + TypeScript + Vue Router + Pinia + Element Plus + Vite + ECharts
- **数据库**：MySQL

<!-- screenshots-start -->
## 系统截图

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/appliancemall/%E7%99%BB%E5%BD%95%E9%A1%B5%E9%9D%A2.png" alt="登录页面" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/appliancemall/%E7%94%A8%E6%88%B7%E9%A6%96%E9%A1%B5.png" alt="用户首页" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/appliancemall/%E5%AE%B6%E7%94%B5%E9%80%89%E8%B4%AD.png" alt="家电选购" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/appliancemall/%E7%94%B5%E5%99%A8%E8%AF%A6%E6%83%85.png" alt="电器详情" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/appliancemall/%E6%88%91%E7%9A%84%E8%AE%A2%E5%8D%95.png" alt="我的订单" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/appliancemall/%E6%95%B0%E6%8D%AE%E7%9C%8B%E6%9D%BF.png" alt="数据看板" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/appliancemall/%E5%95%86%E5%93%81%E7%AE%A1%E7%90%86.png" alt="商品管理" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/appliancemall/%E8%AE%A2%E5%8D%95%E7%AE%A1%E7%90%86.png" alt="订单管理" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/appliancemall/%E8%AE%BA%E6%96%87%E5%9B%BE1.png" alt="论文图1" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/appliancemall/%E8%AE%BA%E6%96%87%E5%9B%BE2.png" alt="论文图2" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/appliancemall/UML%E5%9B%BE%E5%88%97%E8%A1%A8.png" alt="UML图列表" width="600" />

<!-- screenshots-end -->
