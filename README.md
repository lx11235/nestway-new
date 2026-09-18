# NestWay 女性安全陪伴 App — 个人核心模块代码摘录

## 说明
这是一个 10 人团队项目。我们按功能模块分工，我独立负责以下 Flutter 页面。
为尊重团队协作与队友劳动成果，此处仅摘录我个人编写的核心代码，不包含项目全局配置（main.dart、路由、依赖管理），无法独立运行。

## 我负责的模块
- `home_page.dart`：首页守护入口、定位服务、护送状态检测与恢复
- `destination_safety_page.dart`：目的地安全预警，集成 DeepSeek API + RAG + 结构化输出治理
- `profile_page.dart`：个人中心、联系人管理、Provider 状态联动
- `safety_page.dart`：安全预警页面基础结构

## 核心贡献
- 对接 DeepSeek API，设计 System Prompt + Few-shot + 正则兜底，保障 JSON 结构化输出稳定
- 实现安全评分星级映射、风险等级 UI 配色、多栏位信息展示
- 基于 Provider 完成跨页面状态管理与联系人 CRUD

## 技术栈
Flutter / Dart / Provider / REST API / Git

## 备注
本仓库仅展示个人贡献，代码摘录自团队项目的个人开发分支，可能与最终整合版本存在少量差异，无法独立运行。
