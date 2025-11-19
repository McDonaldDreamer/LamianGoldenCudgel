# 桌面小易 - 快捷方式管理工具

一个现代化的桌面快捷方式管理工具，支持文件、文件夹和网站快捷方式的添加、编辑和管理。

## 项目结构

```
├── .desktop_yi/            # 桌面快捷方式数据
├── .private_space_data     # 私有空间数据
├── .shortcut_manager/      # 快捷方式管理器数据
├── __pycache__/            # Python缓存文件
├── image/                  # 图片资源
├── customtkinter_example.py # 主界面实现
├── file_transfer.py        # 文件传输功能
├── main.py                 # 程序入口
├── shortcuts.py            # 快捷方式管理
├── socket_client.py        # Socket客户端
├── socket_server.py        # Socket服务器
├── requirements.txt        # 项目依赖
└── README.md               # 项目说明文档
```

## 功能特性

- 支持文件、文件夹和网站快捷方式管理
- 多种视图模式（列表视图、图标视图）
- 主题切换（深色/浅色模式）
- 快捷方式分组和分类
- 搜索功能
- 文件传输功能
- Socket通信支持

## 安装说明

```bash
pip install -r requirements.txt
```

## 运行程序

```bash
python main.py
```

## 注意事项

- 程序在Windows平台上运行，依赖pywin32库
- 日志级别设置为INFO，可在main.py中调整
- 部分功能尚未完善，欢迎反馈和贡献
