# Official Claude Code Plugins

官方Claude Code插件集合

这个仓库包含以下由Anthropic官方提供的Claude Code插件：

- [agent-sdk-dev](./plugins/agent-sdk-dev) - Claude Agent SDK开发工具包
- [commit-commands](./plugins/commit-commands) - Git提交命令插件
- [feature-dev](./plugins/feature-dev) - 功能开发助手
- [pr-review-toolkit](./plugins/pr-review-toolkit) - PR代码审查工具包
- [security-guidance](./plugins/security-guidance) - 安全指导插件

## 安装使用

### 方法一：使用插件市场（推荐）

1. 添加此插件市场：
```bash
/plugin marketplace add DDDDDDDan/official-claude-code-plugins
```

2. 浏览可用的官方插件：
```bash
/plugin
```

3. 安装您需要的插件，例如：
```bash
/plugin install agent-sdk-dev
/plugin install pr-review-toolkit
/plugin install security-guidance
```

### 方法二：直接安装单个插件

如果您知道具体插件名称，可以直接安装：
```bash
/plugin install commit-commands
/plugin install feature-dev
```

### 方法三：从源码安装

开发者也可以从源码安装：

1. 克隆此仓库：
```bash
git clone https://github.com/DDDDDDDDan/official-claude-code-plugins.git
cd official-claude-code-plugins
```

2. 使用本地路径添加插件：
```bash
/plugin install ./plugins/agent-sdk-dev
```

## 插件详情

### agent-sdk-dev
用于开发Claude Agent SDK的工具包，包含验证器和应用模板。

### commit-commands
提供智能的Git提交命令，帮助创建规范的提交信息。

### feature-dev
功能开发助手，帮助开发者从规划到实现完整功能。

### pr-review-toolkit
Pull Request代码审查工具包，包含多个专业审查代理。

### security-guidance
安全指导插件，提供开发过程中的安全建议和最佳实践。

## 贡献

欢迎提交问题和拉取请求来改进这些插件。

## 许可证

本项目使用 MIT 许可证。请参考 [LICENSE](./LICENSE) 文件了解详情。

## 相关链接

- [Claude Code 插件文档](https://docs.claude.com/en/docs/claude-code/plugins)
- [GitHub 仓库](https://github.com/DDDDDDDDan/official-claude-code-plugins)
- [插件问题反馈](https://github.com/DDDDDDDDan/official-claude-code-plugins/issues)
