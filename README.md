# 音频元数据编辑器 (Audio Metadata Editor)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Platform](https://img.shields.io/badge/platform-Windows-blue.svg)](https://github.com/yourusername/AudioMetadataEditor)
[![.NET](https://img.shields.io/badge/.NET-6.0-purple.svg)](https://dotnet.microsoft.com/download/dotnet/6.0)

这是一个使用C#和WPF开发的音频元数据编辑器，可以编辑MP3、FLAC、WAV等多种音频格式的元数据，包括标题、艺术家、专辑、年份、音轨号、流派和专辑封面等信息。


## 功能特点

- 支持多种音频格式：MP3、FLAC、WAV、OGG、M4A、WMA、AAC
- 批量处理功能，可以同时编辑多个文件的元数据
- 拖放支持，可以直接拖放文件到应用程序中
- 从文件名自动提取艺术家和标题信息
- 添加、查看和修改专辑封面
- 可选择是否覆盖已有的专辑封面
- 筛选功能，可以快速找出缺失元数据或封面的文件

## 系统要求

- Windows 7/8/10/11
- .NET 6.0 运行时 (独立版本无需安装运行时)

## 安装方法

### 方法一：使用独立可执行文件（推荐）

1. 从[Releases](https://github.com/yourusername/AudioMetadataEditor/releases)页面下载最新的发布版本
2. 解压缩下载的文件
3. 双击 `AudioMetadataEditor.exe` 或 `启动音频元数据编辑器.bat` 运行程序

### 方法二：从源代码编译

1. 确保已安装 [.NET 6.0 SDK](https://dotnet.microsoft.com/download/dotnet/6.0)
2. 克隆或下载此仓库
   ```bash
   git clone https://github.com/yourusername/AudioMetadataEditor.git
   ```
3. 进入项目目录
   ```bash
   cd AudioMetadataEditor
   ```
4. 编译项目
   ```bash
   dotnet build
   ```
5. 运行项目
   ```bash
   dotnet run
   ```

## 使用方法

### 添加文件

1. 点击"添加文件"按钮选择音频文件
2. 点击"添加文件夹"按钮选择包含音频文件的文件夹
3. 直接将文件拖放到应用程序的拖放区域

### 编辑元数据

1. 从左侧文件列表中选择一个文件
2. 在右侧表单中编辑元数据（标题、艺术家、专辑等）
3. 点击"从文件名提取信息"按钮可以自动从文件名中提取艺术家和标题信息

### 管理封面图片

1. 点击封面预览区域或"浏览封面"按钮选择封面图片
2. 也可以直接将图片拖放到封面预览区域
3. 勾选"强制覆盖已有封面"选项可以替换已有的封面图片

### 保存更改

1. 点击"保存当前文件"按钮保存对当前文件的更改
2. 点击"批量保存所有文件"按钮将当前设置的元数据应用到所有文件

### 筛选文件

1. 点击"筛选缺失属性/封面的文件"按钮
2. 选择要筛选的文件夹和筛选条件
3. 程序会自动找出符合条件的文件并添加到列表中

## 技术实现

- 使用C# WPF框架开发用户界面
- 使用TagLib#库处理音频元数据
- 支持多线程处理，提高批量操作效率
- 实现了拖放功能，提升用户体验

## 注意事项

- 默认情况下，程序不会覆盖已有的封面图片，除非勾选"强制覆盖已有封面"选项
- 支持的音频格式包括MP3、FLAC、WAV、OGG、M4A、WMA和AAC
- 支持的图片格式包括JPG、JPEG、PNG和GIF


（注：本项目系AI生成代码编程完成）
