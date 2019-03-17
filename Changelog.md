### 2019/3/15

- 重新设计基本完成，特别感谢 @zhugaoqi 同学的设计指导；
- 将所有第三方库、图片替换为 CDN 引用，极大精简仓库大小；
- 重新设计 archive 渲染逻辑；
- 统一文章页布局，新增文章版权声明；
- 精简页面，配置项;
- 老版本逐渐放弃维护，代码归档在 `v0.9` 分支；

### 2019/1/28

更新内容：

1. _config.yml结构大改，图片路径统一为相对于根目录
2. 可自定义index、archive、post、about页面的顶部图像高度(0 - 100)
3. 文章页顶部图像可统一设置，也可文章内单独设置。优先级：文章内banner_img属性 > 主题配置
4. 新增一种文章页布局，在配置文件中可选(post.layout)
5. 新增默认摘要功能，可配置是否开启、默认字数。优先级：文章内<!-- more -->设置 > 主题配置
6. 可自定义首页文章date、tags是否显示 (@喜欢首页只罗列文章标题的同学)
7. 优化toc、字体尺寸，修复断行错误、图片超宽等问题
8. 优化渲染逻辑，去除冗余js
9. 新增多个bug