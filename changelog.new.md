## 1.24.1（2026-05-28）
- 【升级】`vk-unicloud-admin-ui` 的 npm 包（执行`npm i vk-unicloud-admin-ui@1.24.1 --registry https://registry.npmjs.org/`）
- 【升级】`vk依赖` [详情](https://ext.dcloud.net.cn/plugin?id=4157&update_log)
- 【重要】支持国际化（i18n），涉及所有内置组件以及素材库、顶栏、登录页、菜单、错误日志、修改密码、富文本编辑器、二维码等组件（暂未包含用户管理等业务页面）
- 【重要】素材库页面UI全面重构，支持父子分组管理、独立音频类型、多种视图模式（列表/缩略图/幻灯片）
- 【重要】素材库选择组件由内置调整为自定义组件，源码在 `/components/vk-data-input-file-select/vk-data-input-file-select.vue`
- 【重要】左侧菜单组件由内置组件调整为自定义组件，源码在 `/windows/components/menu-nav.vue`、`/windows/components/menu-sub.vue`
- 【重要】新增页面权限拦截功能（没有该菜单访问权限的用户将自动跳转到403页面）
- 【重要】万能表格 新增属性 `fullscreen`，为 true 时表格高度撑满到屏幕底部（全屏模式）自 1.24.1 起，表格不再默认全屏，需要手动设置 `:fullscreen="true"` 才会全屏。
- 【重要】万能表格 默认的详情表格重构为 24 栅格布局，支持 span 属性控制每行格子数（默认为24）
- 【重要】万能表格 搜索组件重构为 24 栅格布局，支持 span 属性控制每行格子数（默认为0）为0时代表不开启栅格布局，保持原布局 [传送门](https://vkdoc.fsq.pub/admin/2/table.html#query-columns)
- 【新增】万能表格 搜索组件 `vk-data-table-query` 支持搜索区域折叠/展开 [传送门](https://vkdoc.fsq.pub/admin/2/table.html#query)
- 【新增】万能表格 导出 Excel 支持字段选择器和字段排序
- 【新增】万能表格 新增属性 `pagination-placement` 分页器位置（当 batchBtns 有值时固定为 right）自 1.24.1 起，分页器位置默认在右下角
- 【新增】万能表单 `vk-data-input-numeric` 统一数字输入组件，替代原 money/number/percentage/discount 四个独立组件，支持输入负数，支持范围输入 [传送门](https://vkdoc.fsq.pub/admin/components/4%E3%80%81number.html#range)
- 【新增】万能表格 底部新增批量操作按钮组件能力 [传送门](https://vkdoc.fsq.pub/admin/2/table.html#batch-btns)
- 【新增】万能表单 地图选择器支持手动输入经纬度和地址，新增 `requireMapKey` 配置项 [传送门](https://vkdoc.fsq.pub/admin/components/28%E3%80%81map.html)
- 【新增】用户管理新增自定义详情弹窗，支持头像编辑、标签选择、邮箱字段展示和编辑
- 【优化】菜单标签页支持右键上下文菜单操作
- 【优化】万能表单 上传组件的拖拽排序交互体验
- 【优化】所有表格页面统一使用 `vk-page-card` 卡片化布局，排版符合当前主流admin风格
- 【优化】省市区数据更新

##### 框架更新步骤 [点击查看](https://vkdoc.fsq.pub/admin/1/update.html)
