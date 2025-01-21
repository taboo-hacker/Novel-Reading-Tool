# 小说阅读器

## 版本号：0.5

## 功能简介
本小说阅读器是一款便捷的本地阅读工具，可将从飞卢小说下载的小说文件（`.zip` 格式）转换为本地小网站，方便用户随时随地享受流畅的阅读体验。

---

## 使用方法
1. **准备小说文件**  
   将下载的小说文件（`.zip` 格式）放置于程序根目录下的 `xs` 文件夹内。如果文件夹不存在，请手动创建，或双击运行 `run.bat` 文件以自动创建。
2. **启动程序**  
   双击运行 `run.bat` 文件，程序将自动处理小说文件并生成本地阅读网站。处理完成后，链接会自动打开，您可以通过浏览器访问指定的本地地址（如 [http://127.0.0.1:8080](http://127.0.0.1:8080)）开始阅读。

**注意**：如果链接无法访问，可能是由于网络问题或链接不完整导致的。请检查链接的合法性，并确保本地服务已正确启动。如果问题仍未解决，建议适当重试或联系技术支持。

---

## 更新说明
- **版本 0.1**  
  初始版本，完成了程序的基本源代码开发，实现了将 `.zip` 格式的小说文件转换为本地小网站的核心功能。
- **版本 0.2**  
  对代码结构进行了优化，将原本冗长的代码拆分为多个自定义函数，便于后续维护和扩展。
- **版本 0.3**  
  进一步优化文件管理，将小说原文件从根目录转移到专门的 `xs` 文件夹中，使目录结构更加清晰，便于用户管理和查找文件。
- **版本 0.4**  
  为提升用户体验，专门设计了美观的样式表（CSS），并将其放置于 `css` 目录中。用户可以通过修改样式表来自定义阅读界面的外观，使阅读更加舒适和个性化。
- **版本 0.5**  
  添加了自动打开网站的功能，用户无需手动输入或点击地址即可直接开启网站。新增自动创建存放小说的文件夹和创建日志文件功能。拓展了 `settings.py` 的规范化，并新增了日志设置。

---

## 更新预告
- **版本 0.6**  
  将新增“上一章”和“下一章”按钮，方便用户在阅读过程中快速切换章节，进一步提升阅读体验。

---

## 注意事项
1. 请确保小说文件为 `.zip` 格式，否则程序可能无法正确处理。
2. 如果在运行过程中遇到问题，请检查文件路径是否正确，或联系技术支持获取帮助。
3. 如果放入 `xs` 后任无法显示，请刷新网页或检查设置 在 `settings.py` 文件中的一下内容是否被更改。如被更改，请改回来或放入新目录下。
    ```python
    xs_dir = "./xs"
    ```

---

## 致用户
感谢您选择使用本小说阅读器！我们将持续优化功能，为您带来更好的阅读体验。如果您有任何建议或反馈，请随时与我们联系。

### 联系方式
- **邮箱**：
  - [leo43991314520@163.com](mailto:leo43991314520@163.com)  
  - [leo43991314520@outlook.com](mailto:leo43991314520@outlook.com)