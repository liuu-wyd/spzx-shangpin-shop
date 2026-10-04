尚品甄选 SPZX商城
基于Spring Cloud Alibaba微服务架构的B2C电商平台，前后端分离项目。

📖项目简介
针对电商高并发业务场景，将业务拆分为用户、商品、购物车、订单、支付多个微服务模块。
集成Nacos注册中心、Gateway网关、OpenFeign服务调用；前端Vue3+Vite开发，实现商品浏览、购物车、下单、支付宝支付、后台权限管理完整电商业务。

🛠技术栈
后端：Java、SpringBoot、SpringCloud‑Alibaba、Nacos、Gateway、OpenFeign、Redis、MySQL、MinIO
前端：Vue3 + Vite
接口文档：Knife4j

✨核心功能
- 用户模块：注册登录、Token认证、个人中心
- 商品模块：商品展示、分类检索、SKU管理、上下架
- 购物车模块：Redis实现购物车，未登录本地缓存、登录后数据合并
- 订单&支付：订单生成、状态流转、集成支付宝回调
- 后台管理：RBAC权限控制、商品订单管理、文件上传MinIO

🧑‍💻我的职责
参与微服务业务开发，实现用户登录认证、Redis购物车业务逻辑；对接Gateway网关处理跨域问题；参与接口调试，解决Token过期、购物车数据一致性等实际问题。

📁项目文档
[尚品甄选.pdf](./尚品甄选.pdf) 完整项目报告（架构图、流程图、核心代码、部署说明）
