## 1.25.0（2026-06-17）
- 【升级】`vk-unicloud-admin-ui` 的 npm 包（执行`npm i vk-unicloud-admin-ui@1.25.0 --registry https://registry.npmjs.org/`）
- 【升级】`vk依赖` [详情](https://ext.dcloud.net.cn/plugin?id=4157&update_log)
- 【重要】新增 `vk 统计` 模块，包含用户统计、支付统计、错误统计三大功能区，可通过菜单管理页「初始化vk统计」按钮一键导入菜单
- 【新增】`用户统计` 页面（概览 + 登录日志），展示新增用户趋势图、登录用户趋势图，支持按时/日/月维度切换
- 【新增】`支付统计` 页面（概览），展示收入趋势图、支付漏斗、支付方式占比饼图、按平台/订单类型收入明细表，支持日期快捷筛选和多维度筛选
- 【新增】`用户价值排行` 页面，支持按净收入/支付金额/支付笔数等多维度排序，支持导出 Excel，点击可跳转查看该用户的订单明细
- 【新增】`vk-stat-result` 统计结果表
- 【新增】定时任务 `statUser`（每小时执行用户统计）、`clearExpiredCache`（每小时清理 vk-global-data 过期缓存）
- 【调整】`支付订单明细` 页面，订单列表和详情弹窗从 `pages_plugs/system_uni/vk-pay-orders` 迁移至 `pages/vk-stats/pay`，详情弹窗 UI 全面重构（顶部概要卡片 + 基础信息/通知回调/退款信息三 Tab + 订单时间轴）
- 【调整】 `云端错误统计` 页面，从 `pages_plugs/system_uni/vk-error-log` 迁移至 `pages/vk-stats/error`，支持按状态筛选和处理操作
- 【调整】`登录日志` 页面，从 `pages_plugs/system_uni/uni-id-log` 迁移至 `pages/vk-stats/user`，支持按应用、IP、设备、用户等多维度筛选
- 【调整】云函数定时任务超时时间从 900 秒（15 分钟）提升至 7200 秒（2 小时）


##### 框架更新步骤 [点击查看](https://vkdoc.fsq.pub/admin/1/update.html)
