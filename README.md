<p align="center">
  <img alt="logo" src="https://yourdomain.com/assets/logo.png" height="100">
</p>
<h1 align="center">懂了 admin</h1>
<h4 align="center">基于 RuoYi 框架的热点投票与积分竞猜娱乐系统后台</h4>

<p align="center">
  <img src="https://img.shields.io/badge/version-1.0.0-blue.svg">
  <img src="https://img.shields.io/badge/license-MIT-green.svg">
  <img src="https://img.shields.io/badge/springboot-2.7+-brightgreen.svg">
  <img src="https://img.shields.io/badge/vue-2.x-lightgrey.svg">
</p>

---

## 🧠 平台简介

**懂了 admin** 是一款基于 RuoYi v3.8.9 框架开发的后台管理系统，服务于 “懂了” 热点投票与积分竞猜娱乐软件。前台用户可以围绕社会热点（如娱乐八卦、国际局势、明星动态等）进行投票或押注，后台用于管理全局配置、用户行为、内容发布与积分结算。

项目基于 RuoYi 提供的 RBAC 权限控制、菜单系统、代码生成器等能力，进行业务扩展，适合快速构建娱乐类 Web 应用的管理后台。

---

## ✨ 核心功能

| 模块        | 功能说明 |
|-------------|----------|
| 用户管理     | 用户信息、实名认证、封禁状态、积分余额 |
| 投票话题     | 创建/编辑话题、设置投票截止时间、话题状态控制 |
| 投注系统     | 投注项配置、赔率调整、下注记录、结算逻辑 |
| 竞猜结算     | 设置正确选项、一键开奖、积分派发、异常处理 |
| 公告管理     | 系统公告推送、维护通知、运营活动展示 |
| 商城兑换     | 积分商城配置、实物/虚拟商品管理、兑换记录 |
| 报表分析     | 用户活跃度、投注分布、盈亏报表、风控告警 |
| 权限系统     | 多角色支持、自定义菜单、接口权限粒度控制 |
| 日志审计     | 登录日志、操作日志、系统异常、在线用户监控 |
| 自动生成     | 基于数据库表结构，生成前后端增删改查代码 |

---

## ⚙️ 技术架构

- **前端框架**：Vue + Element UI + Axios + Vue Router
- **后端框架**：Spring Boot + MyBatis + Redis + Spring Security + JWT
- **数据库**：MySQL + Redis
- **开发基础**：基于 RuoYi v3.8.9 二次开发

---


