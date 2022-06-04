# 资源文件仓库

## jsdeliver CDN 加速

1. URL 前缀为：`https://fastly.jsdelivr.net/gh/HATTER-LONG/Resource@main/`。
   - 例如访问图片：`https://fastly.jsdelivr.net/gh/HATTER-LONG/Resource@main/images/xxx.png`。

## images 图床资源管理

### [picgo 使用](https://picgo.github.io/PicGo-Core-Doc/zh/guide/)

1. 自动生成配置文件：`picgo set uploader`。
   - 配置文件路径：`~/.picgo/config.json`。
2. 切换当前使用图床：`picgo use uploader`。
3. 图片上传命令：`picgo u target.png remoteName.png`。
4. 插件管理：
   - 安装：`picgo install plugin`。
   - 卸载：`picgo uninstall plugin`.

### 图片裁剪命令

1. 自适应裁剪：`sips -Z 600 xx.png`，600 表示高度，宽带按比例缩放。
2. 指定裁剪宽度：`sips -z 100 200 xx.png`，100 表示高度，200 表示宽度。
3. 旋转：`sips -r 90 xx.png`，向右旋转 90 度。
4. 翻转：`sips -f horizontal xx.png`，水平方向翻转，vertical 为垂直方向。
