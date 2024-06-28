# TSLA Grid Trading System

## 项目概述
本项目旨在开发一个自动化网格交易策略，专注于特斯拉（TSLA）股票，通过设定的买卖规则实现盈利。使用PyAlgoTrade进行策略开发和回测，部署至基于Ubuntu 22的VPS，前端开发环境为Windows 11下的Visual Studio Code。

## 技术栈
- **开发环境**: Windows 11, Visual Studio Code
- **版本控制**: Git
- **回测和交易算法**: PyAlgoTrade (Basana扩展)
- **交易API**: Moomoo's OpenD
- **服务器**: VPS运行Ubuntu 22

## 开发计划

### 第一阶段：环境搭建与需求确认
**持续时间**: 1周
- 确认项目需求和目标。
- 设置开发环境和版本控制系统。

先在github中进行相关设置
一、Projects设置:
issue #1 在github中创建新仓库，创建新项目关联仓库
在github中创建新仓库“GridTradeSystem”，公开，增加README.MD，使用Apache 2.0协议；
在仓库中创建新项目“TSLA Grid Trading System”，使用Kanban模板，增加相关issue。
issue #2 本地开发环境安装Visual Studio Code
issue #3 安装Git并配置本地和远程仓库
方法一：
VS Code中登录github（右下角人像图标）；
在VS Code中打开一个新的终端窗口（Terminal -> New Terminal）；
使用cd命令来定位到你希望存放项目的目录，我这里是d盘中...\program\GridTradeSystem>；
git clone https://github.com/zhurong2020/GridTradeSystem.git；
使用VS Code的“File” -> “Open Folder”功能选择克隆后的项目文件夹。
方法二：
如果从零开始在本地建立项目目录，然后将其与GitHub仓库连接，你可以按以下步骤操作：
在VS Code中新建目录；
在VS Code的“File” -> “Open Folder”对话框中，新建一个目录，例如命名为“GridTradeSystem”；
初始化Git仓库：在VS Code终端中，使用cd命令进入新建的目录。执行git init来初始化一个新的Git仓库；
添加远程仓库关联：git remote add origin https://github.com/yourusername/GridTradeSystem.git；
将远程仓库的内容拉到本地（如果远程仓库非空）：git pull origin master；
开始开发，现在可以开始在这个目录中开发，并使用Git来管理版本和更改。
issue #4 安装Python 3.8.1或以上版本。
issue #5 编写需求规格说明书
issue #6 编写项目计划文档
issue #7 开始第二阶段准备

二、另在项目仓库的issue中设置各阶段milestone

### 第二阶段：策略开发与本地回测
**持续时间**: 2周
- 开发初步的交易策略。
- 在本地进行策略的回测。

### 第三阶段：策略优化与再回测
**持续时间**: 2周
- 完善和优化交易策略。
- 进行更全面的回测。

### 第四阶段：VPS部署与测试
**持续时间**: 1周
- 在VPS上部署策略。
- 测试策略在VPS上的表现。

### 第五阶段：监控与维护
**持续时间**: 持续进行
- 监控策略表现。
- 对策略进行必要的调整和优化。

## 注意事项
- 本项目中的示例和策略仅供教育用途。
- 实际操作需谨慎，风险自负。

## 下一步
- 定期回顾项目进度，并根据反馈调整开发计划。
