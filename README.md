# MediatR 知识库

MediatR 从基础到源码级别的系统化学习指南，涵盖理论、实践与架构设计。

## 📖 内容概览

本知识库按照以下维度组织内容：

- **基础篇**: MediatR 核心概念、请求/响应模式、通知机制
- **进阶篇**: 管道行为（Pipeline Behaviors）、异常处理、验证流程
- **集成篇**: ASP.NET Core 集成、依赖注入、Entity Framework Core 配合使用
- **测试与调试**: 单元测试策略、集成测试、日志与诊断
- **性能与最佳实践**: 性能优化、内存管理、并发控制
- **原理与源码分析**: 架构设计、内部实现机制、扩展点解析
- **替代方案与生态对比**: MassTransit、Rebus 等消息队列框架对比
- **实战案例**: CQRS 架构、微服务应用、事件驱动系统
- **附录**: API 参考、常见问题、学习资源

## 🚀 在线访问

**[👉 立即访问知识库](https://jarodchen.github.io/mediatr-kb/)**

## 📂 项目结构

```
mediatr-kb/
├── html/              # 构建后的静态资源（部署到 GitHub Pages）
│   ├── 01-基础篇/
│   ├── 02-进阶篇/
│   ├── 03-集成篇/
│   ├── 04-测试与调试/
│   ├── 05-性能与最佳实践/
│   ├── 06-原理与源码分析/
│   ├── 07-替代方案与生态对比/
│   ├── 08-实战案例/
│   └── 09-附录/
└── .github/
    └── workflows/
        └── deploy.yml # GitHub Actions 自动部署配置
```

## 🔄 自动化部署

本项目使用 GitHub Actions 自动部署到 GitHub Pages：

- **触发条件**: 推送代码到 `main` 分支或手动触发工作流
- **部署目标**: `html/` 目录下的所有静态资源
- **访问地址**: `https://jarodchen.github.io/mediatr-kb/`

## 📝 更新内容

1. 修改或添加 Markdown 源文件（在源项目中）
2. 重新构建生成静态 HTML
3. 将生成的 HTML 文件提交到此仓库的 `html/` 目录
4. 推送到 GitHub，自动触发部署

## 💡 技术栈

- **静态站点生成器**: VitePress
- **部署平台**: GitHub Pages
- **自动化**: GitHub Actions
- **核心技术**: MediatR, .NET, C#, CQRS

## 📄 许可证

本项目采用 MIT 许可证 - 详见 [LICENSE](LICENSE) 文件

---

*欢迎提出建议和贡献！*
