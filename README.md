# Easy Tools · 一些简单的小工具

用 AI 辅助制作自己用得到的小工具，随缘更新，也分享给有需要的人。

## 工具目录

| 工具 | 功能 | 使用方式 |
| --- | --- | --- |
| [封面工坊](docs/cover-studio/) | 四种比例封面、四图预览、描边与标红、随机背景、PNG 导出 | 下载后打开 `docs/cover-studio/index.html` |

网站启用 GitHub Pages 后，入口为 https://baieyi.github.io/Easy_Tools/ 。刚上传时若尚未部署，请使用本地打开方式。

## 本地使用

点击仓库 **Code → Download ZIP**，解压后打开 `docs/index.html`，即可从导航进入工具。无需安装依赖或配置 API 密钥。保留文件夹内 HTML 与 JS 文件的相对位置。

封面工坊在浏览器本地处理标题和项目；可保存 JSON 项目跨电脑继续编辑。浏览器可能要求允许批量下载。支持的浏览器可以选择导出文件夹，否则使用浏览器默认下载位置。

## 部署 GitHub Pages（仓库维护者）

进入 **Settings → Pages**，Source 选择 **Deploy from a branch**，Branch 选择 **main**，目录选择 **/docs**，点击 Save。以 Pages 设置页面显示的发布结果和网址为准。

## 添加工具

每个网页工具放在 `docs/<工具名>/`，以 `index.html` 为入口，资源使用相对路径，然后更新导航首页与本目录。不要提交个人配置、API 密钥、临时文件或导出成品。

## 版本与验证

首个公开版本：封面工坊 2.3。包含可复现的随机背景、四比例独立排版和项目保存。已进行 JavaScript 语法检查与模拟绘图测试；尚未完成真实浏览器端到端验证。问题反馈请附浏览器版本、复现步骤及不含隐私的示例。

## 贡献与许可

欢迎通过 Issues 反馈问题，或 Fork 后提交 Pull Request。修改建议经维护者合并后才会进入本仓库。

代码采用 [MIT License](LICENSE)，可使用、修改、分享和商用，须保留许可声明。素材来源见 [ASSETS.md](ASSETS.md)。
