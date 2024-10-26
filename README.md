
### `.github/workflows/BuildKernel.yml`

这个 GitHub Actions 工作流文件定义了一个名为 "Build Kernel" 的工作流。它包含以下几个作业（jobs）：

1. **set_up**: 设置环境变量。
2. **Get_ready**: 获取编译工具。
3. **build**: 构建内核，显示构建作者。

### `config.json`

这个文件包含了项目的配置参数。

## feature
一键并行运行多个工具链同时开始编译同一个内核源码
详细的编译错误警告
精简重复输出的编译日志

## 使用方法

### 触发工作流

你可以通过 GitHub Actions 的 `workflow_dispatch` 事件手动触发这个工作流


## 贡献

欢迎提交问题和贡献代码！

## 许可证

此项目使用 MIT 许可证。