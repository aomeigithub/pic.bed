## 项目所属

该项目所属为“AOMEI Technology”——网站开发部的资料库。

## 如何使用

1. 每个目录大家均可以自由编写任何形式的文章，也可以查看任何目录任何内容。
2. 每篇文章采用`Markdown`格式编写，在本地就可编写，通过github提交到远程仓库。
3. 文章中不能出现任何形式的账号密码明文，一经发现，视情节严重程度处理。
4. 文章支持图片上传，但是仅限将图片上传到github。下面会介绍如何上传图片。
5. 文章开头有个固定格式，须在文章开始前就写在注释中 &lt;!-- 把下面的内容加到这里 --&gt;。
    ```markdown
    # Author: Zell
    # Title: 使用必读
    # Description: 内含文章编写规则与注意事项
    # Email: jzelldincht@gmail.com
    # Created At: 2023/07/27 14:12
    # Category: MySQL/How to/
    # Updated At: 2023/07/28 14:12
    ```

## 如何上传图片

### 在VSCode插件市场安装插件PicGo

（如何安装就省略了。）

使用`VS Code`的`PicGo`插件可实现把图片上传到设置的服务器（它其实支持多种服务器，我们主要实现配置PicGo使其支持上传到github仓库），可以让我们用快捷键即可上传图片到默认的免费服务器，具体的使用方法是，安装完成后。

![20230727174806](https://cdn.jsdelivr.net/gh/jzelldincht/cloud.images/20230727174806.png)

`Windows`下`Ctrl+Alt+U`从剪贴板粘贴图片，`Ctrl+Alt+E`打开资源管理器选择图片，这是最常用的两个快捷键，其他快捷键如图所示。

### PicGo设置

1. 使用`Ctrl+,`调起“设置”。

2. 打开扩展里的`PicGo`

3. 设置github相关

![20230727174633](https://cdn.jsdelivr.net/gh/jzelldincht/cloud.images/20230727174633.png)

主要看红框中的部分，那两部分的地址需要填写公司github账号下的图片仓库名和一个token，这个token是有时效性一般。

如果觉得网速不行的，可以同时设置下代理。

Custom Url这里是设置的自定义图片前缀，可以起到CDN加速的作用。配置如下：

```bash
https://cdn.jsdelivr.net/gh/aomeigithub/pic.bed
```

