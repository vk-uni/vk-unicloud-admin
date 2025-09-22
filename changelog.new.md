* 【升级】`vk-unicloud-admin-ui` 的npm包（执行`npm i vk-unicloud-admin-ui@1.20.42 --registry https://registry.npmjs.org/`）
* 【升级】`vk依赖` [详情](https://ext.dcloud.net.cn/plugin?id=4157&update_log)
* 【重要】万能表单 text、textarea 新增属性 trimMode，可以设置过滤空格的模式，默认为 trim（过滤前后空格）[传送门](https://vkdoc.fsq.pub/admin/components/1%E3%80%81text.html#trim-mode)
* 【优化】素材库管理页面新增幻灯片播放模式 [传送门](https://vkdoc.fsq.pub/admin/6/uni-id-files.html#slideshow)
* 【优化】素材库支持并发上传文件，提升上传速度 [传送门](https://vkdoc.fsq.pub/admin/6/uni-id-files.html#concurrency)
* 【优化】素材库支持上传远程图片和视频 [传送门](https://vkdoc.fsq.pub/admin/6/uni-id-files.html#remotefile)
* 【优化】素材库支持显示私有权限的图片和视频
* 【优化】万能表单 columns 属性内支持直接写 rules（表单验证规则） 
* 【优化】万能表单 select 新增属性 showDesc [传送门](https://vkdoc.fsq.pub/admin/components/9%E3%80%81select.html#show-desc)
* 【优化】万能表单 remote-select 新增属性 showDesc 和 group [传送门](https://vkdoc.fsq.pub/admin/components/10%E3%80%81remote-select.html#demo7)
* 【优化】万能表单 remote-select 的刷新按钮显示在右侧，而非显示在待选项中
* 【优化】万能表单 file-select 新增 returnType 属性，可控制返回值是 url 或 id [传送门](https://vkdoc.fsq.pub/admin/components/25%E3%80%81file-select.html#fileid)
* 【优化】万能表单 `array-object` 新增属性 beforeRemove，支持删除前拦截

**特别注意：本次更新需要替换框架内置文件**

- `/router/service/admin/system_uni/uni-id-files/` 整个目录

##### 框架更新步骤 [点击查看](https://vkdoc.fsq.pub/admin/1/update.html)