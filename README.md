# 河声静态版：GitHub Pages上传说明

本包已经构建完成，解压上传后即可由GitHub Pages展示，不需要安装软件、运行命令或填写AI密钥。

## 上传

1. 建议新建一个仓库存放这个静态版，保留之前的完整服务版仓库。
2. 解压“河声_GitHubPages静态上传包.zip”，进入解压文件夹。
3. 在GitHub仓库打开Add file → Upload files，把里面的index.html、404.html、assets、data、.nojekyll和README.md一起拖入。
4. 点击Commit changes。仓库首页必须直接看到index.html和assets文件夹。
5. 不要上传ZIP本身，也不要把最外层解压文件夹套在仓库里。

## 开启网页

1. 打开仓库的Settings → Pages。
2. Source选择Deploy from a branch。
3. Branch选择main，文件夹选择/(root)，点击Save。
4. 等待GitHub显示部署完成，打开Pages页面提供的网址。

如果你使用原来的RIVER-VOICES仓库，请用本包覆盖根目录的index.html并上传新的assets和data。
旧的src、public、server文件夹不参与此静态版运行，但不要再把该仓库作为完整版的构建源码使用。
推荐给静态版单独建仓库，避免与完整版混淆。

本包支持用户名.github.io/仓库名/这样的路径，也支持域名根目录。
探索和参与采用#/explore、#/participate地址，刷新不会请求服务器上的不存在页面。
404.html也处理原来的/explore、/participate链接。
页面更新后如仍显示旧版，可用Ctrl+F5强制刷新。

## 可用功能

- 首页五幕滚动、真实画面、原声音频。
- 六地真实地图、地图/列表切换、人物与议题筛选。
- 42段采访的浏览器内原文检索、来源阅读、故事详情。
- 经历/问题/线索输入、附件和录音预览、文字草稿保存在当前浏览器。

## 静态版的范围

AI整理、语音转写及正式投稿需要连接在线服务，本包没有假装接通这些功能。
文字草稿不会发送给项目团队。照片、录音和选填信息仅供本次预览，刷新后不保留。
本包不含API密钥、.env、本机投稿记录、内部画册PDF、完整视频或Node服务器。
画册和视频位置保留“资料在内部，官网更新后同步更新”等既定说明。

GitHub Pages说明：https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site
