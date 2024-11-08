# QQ空间历史内容获取工具

欢迎使用 **QQ空间历史内容获取工具**，一个强大且易用的应用，旨在帮助你轻松获取和管理你的QQ空间历史内容！无论你是想查看过去的动态，还是想整理好友的留言，这个工具都能满足你的需求。
[B站有详细食用教程](https://space.bilibili.com/1117414477)

<details><summary><font color="#FF0000" size="5">免责声明【必读】</font></summary>

本工具仅供学习和技术研究使用，不得用于任何商业或非法行为，否则后果自负。

本工具的作者不对本工具的安全性、完整性、可靠性、有效性、正确性或适用性做任何明示或暗示的保证，也不对本工具的使用或滥用造成的任何直接或间接的损失、责任、索赔、要求或诉讼承担任何责任。

本工具的作者保留随时修改、更新、删除或终止本工具的权利，无需事先通知或承担任何义务。

本工具的使用者应遵守相关法律法规，尊重QQ的版权和隐私，不得侵犯QQ或其他第三方的合法权益，不得从事任何违法或不道德的行为。

本工具的使用者在下载、安装、运行或使用本工具时，即表示已阅读并同意本免责声明。如有异议，请立即停止使用本工具，并删除所有相关文件。

</details>

---
> 当前最新版本为 **1.0.2** 最后更新时间为 **2024年10月9日 19:40**
- 修复昵称包含特殊字符时无法登录的问题

点击此处可跳转到 [Releases](https://github.com/LibraHp/GetQzonehistory/releases/tag/gui-v1.0.2) 页面进行更新
## 1.0.2 版本修复内容：
- 1.修复了Mac用户无法创建导出文件夹的问题
- 2.优化代码逻辑，出错概率大大降低
- 3.适配深色模式
- 4.优化显示逻辑
- 5.修复list index out of range报错的问题
- 6.修复时间格式化失败导致爬取失败的问题
---
## ✨ 功能亮点

- **二维码登录**：只需扫描二维码，即可快速登录你的QQ空间，安全便捷！
- **历史内容查看**：轻松浏览你和好友的历史动态，记录那些美好的瞬间。
- **用户信息展示**：显示你的QQ头像、昵称等信息，让你在使用时拥有更好的体验。
- **多种列表选项**：查看说说、留言、好友、转发、图片等多种内容，一应俱全。
- **获取内容**：提取并查看QQ空间中的所有历史内容，包括发布的说说、图片等。
- **说说列表**：查看你从最早到最新发布的所有说说内容及时间。
- **留言列表**：查看好友给你QQ空间留下的所有留言。
- **好友列表**：获取并查看QQ空间中的好友信息。
- **转发列表**：查看你曾经转发的所有内容。
- **互动分析**：基于好友互动的频率，展示与你互动最多的好友排行榜。
- **开放源代码**：完全免费且开源，欢迎大家参与贡献和讨论！
---

## 🚀 使用指南

1. 打开程序后，使用手机QQ扫描二维码登录。
2. 登录成功后，你将进入主界面，可以选择查看不同的内容。
3. 在左侧标签页中选择想要查看的内容列表，享受你的QQ空间回忆之旅！

---

## 📦 参与开发

1. 确保你的环境中已安装 [Python](https://www.python.org/downloads/)和[Flutter](https://flutter.cn/)环境,并且安装了[Flet](https://flet.dev/)。
2. 克隆这个仓库：
   ```bash
   git clone https://github.com/LibraHp/GetQzonehistory.git -b gui
   ```
3. 安装所需依赖：
   ```bash
   pip install -r requirements.txt
   ```
4. 运行程序：
   ```bash
   flet run
   ```
5. fork仓库
6. 提交代码
---


## 🛠️ 技术栈

- **Flet**：用于构建现代化的图形用户界面。
- **Requests**：轻松进行HTTP请求，获取QQ空间的数据。
- **JSON**：处理和解析数据格式，使内容呈现更加灵活。

---

## 🙌 特别感谢

感谢 [Flet](https://flet.dev) 和 [Requests](https://docs.python-requests.org/en/latest/) 的开发者们，你们的工具让开发变得如此简单与高效！

---

## 📬 联系我们

如有任何问题或建议，请随时通过 [GitHub Issues](https://github.com/LibraHp/GetQzonehistory/issues) 联系我们。期待你的反馈与支持！

---

让我们一起重温QQ空间的美好回忆吧！🌟
