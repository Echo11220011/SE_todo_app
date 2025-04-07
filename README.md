# Todo任务管理器

一个简单的Todo任务管理应用，使用Python和Tkinter开发。

## 功能特点

1. **添加任务**：输入标题和描述，快速添加新任务
2. **编辑任务**：双击任务修改内容或状态
3. **删除任务**：支持单选或多选删除
4. **任务筛选**：可切换显示/隐藏已完成任务

## 运行截图

(此处插入应用运行截图)

## 运行要求

- Python 3.6+
- 无需额外安装库

## 安装运行

1. 克隆仓库或下载代码
2. 运行命令：`python main.py`

## 开发过程

1. 使用AI辅助设计了数据库结构和基本CRUD操作
2. 基于AI生成的Tkinter框架代码扩展功能
3. 个人实现了任务筛选和双击编辑等交互功能
4. 优化了UI布局和用户体验

## 四项功能实现

1. **增**：通过`add_task`方法和数据库`add_task`函数实现
2. **删**：通过`delete_selected`方法和数据库`delete_task`函数实现
3. **改**：通过`edit_task`/`mark_completed`方法和数据库`update_task`函数实现
4. **查**：通过`load_tasks`方法和数据库`get_all_tasks`函数实现
