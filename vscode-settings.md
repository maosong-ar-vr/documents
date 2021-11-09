# VSCode 配置说明

实现 VSCode 中 C#、Unity、Vuforia 等的代码完成。

## 安装 SDK

- [Windows: .NET Framework 4.7.1 Developer Pack](https://dotnet.microsoft.com/download/dotnet-framework/net471)
- [macOS: Download .NET SDK](https://dotnet.microsoft.com/download)
- [macOS: Mono](https://www.mono-project.com/download/stable/)
- [Microsoft.Unity.Analyzers](https://www.nuget.org/packages/Microsoft.Unity.Analyzers/)，下载稍后使用

## Unity 设置

- 菜单 > Unity > 首选项
- 外部工具 > 外部脚本编辑器 > 选中 Visual Studio Code

![nuget](./files/vscode-settings/unity.png)

## VSCode 插件

- C#
  - 配置项 omnisharp.useGlobalMono: always
- (可选) Debugger for Unity
- (可选) Unity Code Snippets
- (可选) Unity Tools

## 项目配置

1. 项目根目录创建 .editorconfig 文件

```conf
root=true

[*.cs]
dotnet_diagnostic.IDE0051.severity = none
```

2. 在根目录创建 `NuGet` 文件夹，将之前下载的 microsoft.unity.analyzers.XXX.nupkg 解压缩到该文件夹。`XXX 是你下载的版本号`

![nuget](./files/vscode-settings/nuget.png)

3. 项目根目录创建 omnisharp.json 文件

```json
{
  "RoslynExtensionsOptions": {
    "EnableAnalyzersSupport": true,
    "LocationPaths": ["./NuGet/microsoft.unity.analyzers.XXX"]
  }
}
```

## 完成

关闭 VSCode 和 Unity 并重新启动
