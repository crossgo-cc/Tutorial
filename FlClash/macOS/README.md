# ⚔️ FlClash for macOS 详细使用教程

## 📥 第一部分：下载安装

### 下载地址

> **⚠️ 国内用户请注意：**
> GitHub 服务器位于海外，可能出现下载缓慢、无法访问或下载中断的情况。
> 👉 **推荐优先使用镜像加速下载。**

| 设备类型 | 下载方式 | 下载链接 | 适用场景 |
| :--- | :--- | :--- | :--- |
| **M 系列 Mac** | **🚀 镜像加速** | [点击下载](https://gh-proxy.org/https://github.com/chen08209/FlClash/releases/download/v0.8.92/FlClash-0.8.92-macos-arm64.dmg) | 国内网络（推荐） |
| **M 系列 Mac** | **📦 官方 GitHub** | [点击下载](https://github.com/chen08209/FlClash/releases/download/v0.8.92/FlClash-0.8.92-macos-arm64.dmg) | 海外网络 / 已有代理 |
| **Intel Mac** | **🚀 镜像加速** | [点击下载](https://gh-proxy.org/https://github.com/chen08209/FlClash/releases/download/v0.8.92/FlClash-0.8.92-macos-amd64.dmg) | 国内网络（推荐） |
| **Intel Mac** | **📦 官方 GitHub** | [点击下载](https://github.com/chen08209/FlClash/releases/download/v0.8.92/FlClash-0.8.92-macos-amd64.dmg) | 海外网络 / 已有代理 |

---

### 安装步骤

#### 1️⃣ 打开安装包

下载完成后，双击打开对应的 `.dmg` 安装文件。

#### 2️⃣ 拖动到 Applications

将 **FlClash** 图标拖动到 **Applications** 文件夹，完成安装。

#### 3️⃣ 首次打开应用

安装完成后，前往 **应用程序** 中打开 **FlClash**。

如果系统提示应用无法直接打开，可以按以下方式处理：

- 在 **Finder** 中找到 **FlClash**
- 按住 **Control** 键点击应用，选择 **打开**
- 再次点击 **打开**

#### 4️⃣ 如果仍被系统拦截

如果出现“来自未知开发者”或“无法验证开发者”之类提示：

- 打开 **系统设置**
- 进入 **隐私与安全性**
- 在 **安全性** 区域点击 **仍要打开**
- 输入登录密码后再次打开应用

> **⚠️ 注意：** `仍要打开` 按钮通常只会在你首次尝试打开应用后的约一小时内出现。

---

## 🚀 第二部分：操作步骤

> **说明：** FlClash 在 `macOS` 与 `Windows` 的应用内界面基本一致，以下步骤图示复用 `Windows` 版本截图。

## 步骤一：获取订阅链接

1. 登录官网后台，在 **「仪表盘」** 栏点击 **「一键订阅」**
2. 在弹出的菜单中选择 **「复制订阅地址」**

> ⚠️ 请确认系统提示 **复制成功**

![点击一键订阅按钮](https://cdn.jsdmirror.com/gh/crossgo-cc/Tutorial@main/FlClash/Windows/assets/1.png)

![复制订阅地址](https://cdn.jsdmirror.com/gh/crossgo-cc/Tutorial@main/FlClash/Windows/assets/2.png)

---

## 步骤二：导入订阅

1. 打开 **FlClash 客户端**
2. 点击左侧导航栏 **「配置」**
3. 点击右下角 **「+」** 按钮
4. 在弹出的菜单中选择 **「URL」**
5. 在 **「从 URL 导入」** 输入框中粘贴订阅地址
6. 点击 **「提交」** 完成导入

![点击加号按钮](https://cdn.jsdmirror.com/gh/crossgo-cc/Tutorial@main/FlClash/Windows/assets/3.png)

![选择 URL 选项](https://cdn.jsdmirror.com/gh/crossgo-cc/Tutorial@main/FlClash/Windows/assets/4.png)

![粘贴订阅链接并提交](https://cdn.jsdmirror.com/gh/crossgo-cc/Tutorial@main/FlClash/Windows/assets/5.png)

---

## 步骤三：选择节点

1. 点击左侧导航栏 **「代理」**
2. 在节点列表中选择一个可用节点

例如：

- 自动选择
- 香港节点
- 美国节点
- 日本节点

![点击代理图标](https://cdn.jsdmirror.com/gh/crossgo-cc/Tutorial@main/FlClash/Windows/assets/6.png)

![选择节点](https://cdn.jsdmirror.com/gh/crossgo-cc/Tutorial@main/FlClash/Windows/assets/7.png)

---

## 步骤四：启动代理服务

1. 点击左侧导航栏 **「仪表盘」**
2. 打开 **「系统代理」** 开关
3. 点击右下角 **「播放」** 按钮启动服务

![开启系统代理并启动服务](https://cdn.jsdmirror.com/gh/crossgo-cc/Tutorial@main/FlClash/Windows/assets/8.png)

---

## ✅ 第三部分：连接确认与使用建议

## 1️⃣ 如何确认连接成功？

连接成功后，可以观察以下信息：

- **仪表盘页面出现实时流量曲线**
- **网络速度有变化**
- **网络检测 IP 已变为海外地址**

---

## 2️⃣ 模式说明

> 💡 **推荐使用「规则模式」**

| 模式 | 说明 |
| --- | --- |
| **规则 (Rule)** | 智能分流，国内网站直连，国外网站走代理（推荐） |
| **全局 (Global)** | 所有网络流量全部通过代理 |
| **直连 (Direct)** | 不使用代理 |

---

## 3️⃣ 常见问题

### 打不开应用怎么办？

优先按以下顺序处理：

- 在 **Finder** 中对应用执行 **Control + 点击** → **打开**
- 打开 **系统设置** → **隐私与安全性** → **仍要打开**
- 确认下载文件来自正确的官方发布页面

### 无法连接怎么办？

可以尝试以下方法：

- 确认 **已开启「系统代理」**
- 在 **代理页面切换节点**
- 在 **配置页面更新订阅**
- 检查 **Mac 系统时间是否正确**
- 关闭其他可能冲突的代理软件后重试
