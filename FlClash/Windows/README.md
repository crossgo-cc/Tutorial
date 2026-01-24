# ⚔️ FlClash for Windows 详细图文教程

## 📥 第一部分：下载安装

### 下载安装程序

**重要提示：** 由于 GitHub 服务器位于海外，国内用户可能会遇到以下问题：
- ⚠️ 下载速度极慢（几 KB/s 甚至无法连接）
- ⚠️ 部分地区网络完全无法访问 GitHub
- ⚠️ 下载过程中频繁中断或失败

**解决方案：** 我们提供了两个下载源，请根据您的网络情况选择：

#### 方式一：官方 GitHub 下载（海外网络推荐）

- **下载链接：** [FlClash-0.8.91-windows-amd64-setup.exe](https://github.com/chen08209/FlClash/releases/download/v0.8.91/FlClash-0.8.91-windows-amd64-setup.exe)
- **适用场景：** 网络可以正常访问 GitHub，或已使用其他代理工具
- **优点：** 官方发布，版本最新最安全

#### 方式二：CDN 镜像加速下载（国内网络推荐）

- **下载链接：** [FlClash-0.8.91-windows-amd64-setup.exe](https://cdn.jsdmirror.com/gh/crossgo-cc/Tutorial@main/FlClash/Windows/assets/FlClash-0.8.91-windows-amd64-setup.exe)
- **适用场景：** 国内网络环境，GitHub 下载困难
- **优点：** 国内 CDN 加速，下载速度快且稳定

### 安装步骤

1. **下载完成后**，双击运行 `.exe` 安装程序
2. **Windows SmartScreen 提示**：如果出现"Windows 已保护你的电脑"提示，点击"更多信息"，然后点击"仍要运行"
3. **用户账户控制**：如果弹出 UAC 权限请求，点击"是"允许安装
4. **安装向导**：按照安装向导提示完成安装，建议使用默认安装路径
5. **完成安装**：安装完成后勾选"启动 FlClash"，点击"完成"即可运行程序

---

## 🚀 第二部分：操作步骤

### 步骤一：获取订阅链接

1. 登录官网后台，在"捷径"栏点击 **「一键订阅」**。

   ![点击一键订阅按钮](https://cdn.jsdmirror.com/gh/crossgo-cc/Tutorial@main/FlClash/Windows/assets/1.png)

2. 在弹出的菜单中选择 **「复制订阅地址」**（务必确保提示复制成功）。

   ![复制订阅地址](https://cdn.jsdmirror.com/gh/crossgo-cc/Tutorial@main/FlClash/Windows/assets/2.png)

### 步骤二：导入订阅

1. 打开 FlClash 客户端，点击左侧导航栏的 **「配置」** (文件夹图标)。
2. 点击右下角的 **「+」** 号按钮。

   ![点击加号按钮](https://cdn.jsdmirror.com/gh/crossgo-cc/Tutorial@main/FlClash/Windows/assets/3.png)

3. 在弹出的"添加配置"菜单中，选择 **「URL」**。

   ![选择 URL 选项](https://cdn.jsdmirror.com/gh/crossgo-cc/Tutorial@main/FlClash/Windows/assets/4.png)

4. 在"从 URL 导入"框中，**粘贴** 刚才复制的订阅地址，然后点击 **「提交」**。

   ![粘贴订阅链接并提交](https://cdn.jsdmirror.com/gh/crossgo-cc/Tutorial@main/FlClash/Windows/assets/5.png)

### 步骤三：选择节点

1. 导入成功后，点击左侧导航栏的 **「代理」** (文档图标)。

   ![点击代理图标](https://cdn.jsdmirror.com/gh/crossgo-cc/Tutorial@main/FlClash/Windows/assets/6.png)

2. 在展开的节点列表中，**点击选择** 一个您想使用的节点（如：自动选择、香港、美国等）。

   ![选择节点](https://cdn.jsdmirror.com/gh/crossgo-cc/Tutorial@main/FlClash/Windows/assets/7.png)

### 步骤四：启动代理服务

1. 点击左侧导航栏最上方的 **「仪表盘」** (方格图标)。
2. **关键步骤：** 将 **「系统代理」** 的开关打开（变为蓝色状态）。
3. 点击右下角的 **「播放」** 按钮，正式启动服务。

   ![开启系统代理并启动服务](https://cdn.jsdmirror.com/gh/crossgo-cc/Tutorial@main/FlClash/Windows/assets/8.png)

---

## ✅ 第三部分：连接确认与使用建议

### 1. 如何确认连接成功？

- 在 **「仪表盘」** 页面，观察左上角的 **“网络速度”** 是否有流量曲线波动。
- 查看 **“网络检测”** 处的 IP 是否已变为海外地址。

### 2. 模式说明

> **💡 建议选择「规则」模式：**
>
> - **规则 (Rule)：** 智能分流，海外网站走加速，国内网站（如百度、淘宝）走直连，省流量且速度快。
> - **全局 (Global)：** 所有网络访问都经过代理。
> - **直连 (Direct)：** 不使用代理。

### 3. 常见问题

**无法连接怎么办？**
- 检查是否开启了 **「系统代理」** 开关。
- 尝试在"代理"页面切换不同的节点。
- 检查电脑系统时间是否准确（时间不同步会导致连接失败）。
