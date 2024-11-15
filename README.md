# Sidecar-iPadAsMacDisplay 安装与使用指南

## 🌟 准备工作

1. **启用远程登录**  
   - 进入 `系统设置` > `通用` > `共享`，开启 **远程登录**。

2. **修改本地主机名**（如果希望使用 iPad 一键随航）  
   - 进入 `系统设置` > `通用` > `共享`，记住或修改 **本地主机名**。

---

## 📥 下载适合的版本

根据你的需求选择合适的版本：

- **个人推荐：名字版**  
  下载 [名字版](https://github.com/Jason6111/Sidecar-iPadAsMacDisplay/releases/download/1.0/device.ID.dmg)

- **序列版**  
  下载 [序列版](https://github.com/Jason6111/Sidecar-iPadAsMacDisplay/releases/download/1.0/Sequence.ID.dmg)

---

### 安装步骤：

1. **安装应用程序**  
   - 将下载的 `开启随航` 文件拖动到 `Applications` 文件夹进行安装。

2. **修复软件打不开问题**  
   - 如果应用程序无法打开，请使用 **修复工具** 进行修复。

3. **开启随航**  
   - 在应用程序找到`开启随航`，右键点击应用程序，选择 **显示包内容**，进入 `Contents` 文件夹，找到并编辑 `document.wflow` 文件（使用文本编辑器打开）。

4. **修改配置文件**  
   - **名字版**：在 `document.wflow` 文件中，找到 `艾派德` 并替换为你 iPad 的名称。
   - **序列版**：在 `document.wflow` 文件中，找到 `#ipad亮屏` 和 `熄屏` 部分，修改 `menu item 4` 的数字。  
     - 你需要手动进入 `系统设置` > `显示器`，在右侧加号下方找到你的设备，并确认该设备在列表中的位置。修改该数字使其与 `menu item 4` 后面的数字相匹配。

5. **手动运行并授权**  
   - 打开 `系统设置` > `隐私与安全性` > `辅助功能`，开启 **随航** 选项。

---

## 🚀 想用 iPad 直接连接 Mac 启用？

### 一键随航操作：

- 你可以使用 **一键随航** 快捷指令，通过以下链接一键启用：
  
  [点击这里获取一键随航](https://www.icloud.com/shortcuts/1d97d20723cc408fae09f5af07441433)

- 在快捷指令中找到 `一键随航`，编辑并填写你的 **IP 地址**、**用户名** 和 **密码**，即可快速连接。

---

### 额外提示

- 请确保你的 iPad 和 Mac 在同一 Wi-Fi 网络下，以确保连接稳定。
- 如果遇到任何问题，可以查看 [常见问题解答](https://github.com/Jason6111/Sidecar-iPadAsMacDisplay/issues) 或在 GitHub 上提交问题。

---

🎉 祝你享受更便捷的 iPad 作为 Mac 显示器的使用体验！
