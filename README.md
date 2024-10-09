
### `.github/workflows/BuildKernel.yml`

这个 GitHub Actions 工作流文件定义了一个名为 "Build Kernel" 的工作流。它包含以下几个作业（jobs）：

1. **set_up**: 设置环境变量。
2. **Get_ready**: 获取编译工具。
3. **build**: 构建内核，显示构建作者。

### `config.json`

这个文件包含了项目的配置参数。

## 使用方法

### 触发工作流

你可以通过 GitHub Actions 的 `workflow_dispatch` 事件手动触发这个工作流。

### 环境变量

工作流中使用了以下环境变量：

- `CONFIG`: 配置文件路径，默认为 `config.json`。
- `OUTPUT_DIR`: 输出文件位置，默认为 `out`。

## 贡献

欢迎提交问题和贡献代码！

## 许可证

此项目使用 MIT 许可证。