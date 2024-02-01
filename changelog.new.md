* 【升级】`vk-unicloud-admin-ui` 包升级至 `1.18.0`
* 【重要】`万能表格` 的分页策略调整（提升查询性能）[传送门](https://vkdoc.fsq.pub/admin/2/table.html#%E5%88%86%E9%A1%B5)
* 【调整】`vk.baseDao.getTableData` 的参数 `getCount` 的默认值为 `true`，但若含有 `lastWhereJson` 或 `lastSortArr` 则默认值为 `false`（兼顾性能和实用性）
* 【调整】`vk.baseDao.selects` 、 `vk.baseDao.getTableData` 将 `addFields` 的执行顺序调整到 `fieldJson` 之前
* 【调整】`万能表格` 搜索组件当有2个字段以上时默认显示重置按钮
* 【优化】`vk.baseDao.select`、`vk.baseDao.selects`、`vk.baseDao.getTableData` 新增返回值 `getCount`，表示是否同时执行了 `count` 请求 [传送门](https://vkdoc.fsq.pub/client/uniCloud/db/selects.html#getcount)
* 【优化】`vk.baseDao.select`、`vk.baseDao.selects`、`vk.baseDao.getTableData` 新增参数 `debug`，传 `true` 会返回执行rows和count的数据库语句执行耗时，单位毫秒，方便优化数据库语句

##### 框架更新步骤 [点击查看](https://vkdoc.fsq.pub/admin/1/update.html)
##### 框架学习Q群：`22466457` 欢迎萌新和大佬来使用和共同改进框架
##### 如果你觉得框架对你有用，可以在下方进行评论或赞赏。
