# 贡献指南

感谢您考虑为音频元数据编辑器项目做出贡献！以下是一些指导方针，帮助您参与到项目中来。

## 如何贡献

1. **报告Bug**：
   - 使用GitHub Issues报告Bug
   - 描述问题的复现步骤
   - 提供操作系统和.NET版本信息
   - 如果可能，提供截图或错误日志

2. **提出新功能**：
   - 使用GitHub Issues提出新功能建议
   - 描述该功能的用途和预期行为
   - 如果可能，提供功能的设计草图或流程图

3. **提交代码**：
   - Fork项目仓库
   - 创建您的功能分支 (`git checkout -b feature/amazing-feature`)
   - 提交您的更改 (`git commit -m 'Add some amazing feature'`)
   - 推送到分支 (`git push origin feature/amazing-feature`)
   - 开启一个Pull Request

## 开发环境设置

1. 确保已安装 [.NET 6.0 SDK](https://dotnet.microsoft.com/download/dotnet/6.0)
2. 克隆仓库：`git clone https://github.com/yourusername/AudioMetadataEditor.git`
3. 进入项目目录：`cd AudioMetadataEditor`
4. 使用Visual Studio 2022或Visual Studio Code打开项目
5. 运行项目：`dotnet run`

## 代码风格指南

- 遵循C#的标准命名约定
- 使用有意义的变量和函数名
- 为公共方法和类添加XML文档注释
- 保持代码简洁，避免不必要的复杂性
- 编写单元测试验证新功能或修复

## Pull Request流程

1. 确保您的PR描述清楚地说明了更改内容和原因
2. 确保所有自动化测试通过
3. 如果添加了新功能，请添加相应的测试
4. 如果修复了Bug，请添加测试以防止回归
5. 更新文档以反映您的更改

## 发布流程

项目维护者将负责版本发布。如果您的贡献被合并，它将在下一个版本中发布。

## 行为准则

请尊重所有项目参与者，保持友好和建设性的交流。

## 问题和讨论

如有任何问题或需要讨论，请使用GitHub Issues或Discussions功能。

感谢您的贡献！
