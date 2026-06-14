# VS Code Configuration and C++ Upload Practice

这是我的第一个 C++ 练习项目。

这个项目主要用于学习：

* 在 VS Code 中编写 C++ 程序
* 使用 g++ 编译并运行程序
* 使用 Git 管理代码版本
* 将本地项目上传到 GitHub

## 文件说明

| 文件名          | 说明                          |
| ------------ | --------------------------- |
| `main.cpp`   | C++ 源代码文件                   |
| `.gitignore` | Git 忽略规则文件，用于避免上传 `.exe` 文件 |

## 程序功能

当前程序会在终端输出两行文字：

```text
Hello, GitHub!
This is my first C++ program.
```

## 如何运行

在 VS Code 终端中输入：

```bash
g++ main.cpp -o main
./main
```

在 Windows PowerShell 中也可以运行：

```powershell
g++ main.cpp -o main
.\main.exe
```

## 学习记录

这是我第一次使用 VS Code 编写 C++ 程序，并将代码上传到 GitHub。
我想让VS Code 也能做到像 Code::Blocks 一样“一键运行，于是安装了Code Runner 插件
