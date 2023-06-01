# 开发计划

## 总计划

为hugo博客写一个在线管理服务

## 已实现功能

- 登陆 / 登出 / 手动刷新缓存
- 获取用户仓库列表以及各种数据，仅限文章数据
- 编辑/发布旧文章
- 修改旧文章的标题，时间，标签，分类等元数据
- 发布新文章
- 完成后台设置功能

## 计划功能

- 删除文章功能
- 自定义配置，如 博客名称, 域名, 昵称 等


建立一个配置文件，将设置存到 GitHub 仓库中，定时读取，弥补本地缓存的一些不足，其实也就是将 GitHub 仓库作为数据库。问题是要处理频率过高引起的报错，所以还是要搭配缓存一起处理。