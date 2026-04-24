# Repository Guidelines

## Project Structure & Module Organization
本仓库用于维护 `FlClash` 图文教程，核心内容位于 `"FlClash/"` 目录：

- `"FlClash/Windows/README.md"`：Windows 教程正文
- `"FlClash/Android/README.md"`：Android 教程正文
- `"FlClash/macOS/README.md"`：macOS 教程正文
- `"FlClash/Windows/assets/"`、`"FlClash/Android/assets/"`：步骤配图
- `"README.md"`：仓库入口说明

新增内容时，优先沿用 `"平台名/README.md + assets/"` 结构。图片按步骤顺序命名，例如 `"1.png"`、`"2.png"`，避免无意义文件名。

## Build, Test, and Development Commands
本仓库没有构建脚本，也没有应用运行入口，日常工作以 Markdown 编辑和校对为主。

- `rg --files "."`：快速查看仓库文件
- `sed -n '1,160p' "FlClash/Windows/README.md"`：分段检查文档内容
- `git diff -- "FlClash/Windows/README.md"`：复核本次改动
- `git status --short`：确认待提交文件范围
- `markdownlint "**/*.md"`：可选的 Markdown 格式检查（仓库未内置）

## Coding Style & Naming Conventions
文档使用中文简体，技术术语、产品名和链接保持原文。保持现有 Markdown 层级：`#` 用于标题，`##` 用于章节，`###` 用于步骤分组。步骤使用有序列表，提示信息优先使用引用块，例如 `> ⚠️ 国内用户请注意：`。不要无关重排目录、批量重命名资源或改写既有表达风格。

## Testing Guidelines
本仓库没有自动化测试。提交前至少手动检查以下内容：

- 标题层级是否连续
- 图片链接和本地资源路径是否正确
- 下载链接、CDN 链接是否完整可读
- 平台内容与配图是否一致，避免错放到其他平台目录

## Commit & Pull Request Guidelines
提交信息遵循现有历史风格：简短、中文、以动词开头，聚焦单一改动，例如 `优化 Windows 教程图片资源`、`统一 FlClash 教程排版和描述规范`。Pull Request 需说明改动范围、影响平台和验证方式；若调整下载地址或图片资源，补充来源，并在描述中说明已核对相关截图和链接。
