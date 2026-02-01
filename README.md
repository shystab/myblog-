# 🎯 Flask博客系统 - 学习项目

**项目状态**：开发中 | **最后更新**：2024年X月X日

## 📖 项目概述
这是我的第一个Flask全栈项目，一个具备完整用户系统的博客平台。通过这个项目，我学习了前后端开发的基本流程。

> **重要声明**：本项目在开发过程中使用了DeepSeek等AI工具进行代码辅助和问题解决，部分代码由AI生成。我已对代码进行理解、测试和修改，确保其正确运行。

## ✨ 功能特性
- ✅ **用户系统**：注册、登录、退出（使用Flask-Login）
- ✅ **博客功能**：文章发布、编辑、删除、查看
- ✅ **数据库**：SQLite + SQLAlchemy ORM
- ✅ **前端界面**：响应式设计，使用Jinja2模板
- ✅ **部署就绪**：支持云服务器部署

## 🛠 技术栈
| 技术 | 用途 | 熟练程度 |
|------|------|----------|
| Flask | Web框架 | 学习使用中 |
| SQLAlchemy | ORM数据库 | 学习使用中|
| HTML/CSS | 前端页面 | 学习使用中|
| Jinja2 | 模板引擎 | 学习使用中 |
| Git | 版本控制 | 学习使用中 |

## 🚀 快速开始

### 环境要求
- Python 3.8+
- pip（Python包管理器）

### 安装步骤
```bash
# 1. 克隆仓库
git clone https://github.com/你的用户名/my-flask-blog.git
cd my-flask-blog

# 2. 创建虚拟环境（推荐）
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate

# 3. 安装依赖
pip install -r requirements.txt

# 4. 初始化数据库
python init_db.py

# 5. 运行应用
python app.py
