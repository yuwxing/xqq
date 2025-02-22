# MR/VR/AI辅助教学内容 - 《Contents》教材（Units 1-8）

## 概述
本项目开发了混合现实（MR）、虚拟现实（VR）和人工智能（AI）辅助教学工具，以增强《Contents》教材（Units 1-8）的学习体验。教材涵盖了“动物朋友”、“没有规则，没有秩序”、“保持健康”、“吃得好”、“此时此刻”、“雨天还是晴天”、“难忘的一天”和“从前有一次”等有趣主题。我们的MR/VR/AI工具旨在为学生创建沉浸式、互动性和个性化的学习环境，重点培养听、说、读、写、发音和语法技能，如教材中所述。

## 功能
- **MR/VR模拟**：
  - 为Unit 1“动物朋友”创建虚拟动物园访问（例如，与虚拟大象、狮子互动）。
  - 为Unit 2“没有规则，没有秩序”创建虚拟教室，模拟制定规则的场景。
  - 为Unit 3“保持健康”创建虚拟运动场和健身房，练习运动习惯。
  - 为Unit 4“吃得好”创建虚拟餐厅，练习点餐和讨论食物偏好。
  - 为Units 5-6“此时此刻”和“雨天还是晴天”创建虚拟聚会场所和天气场景。
  - 为Units 7-8“难忘的一天”和“从前有一次”创建虚拟记忆之旅和讲故事舞台。

- **AI辅助**：
  - AI驱动的聊天机器人，帮助练习听说（例如，回答Unit 1中的“Why do you like animals?”）。
  - AI驱动的语法纠正和反馈，针对写作任务（例如，Unit 1中的Wh-疑问句、形容词、复数）。
  - 根据学生表现提供个性化的学习路径（例如，Unit 3中的频率副词）。

- **互动活动**：
  - 完成项目，如设计动物园（Unit 1）、制定课堂规则（Unit 2）、比较运动习惯（Unit 3）、创建餐厅菜单（Unit 4）等，在3D沉浸式环境中完成。
  - 使用AI和语音识别提供实时发音反馈练习（例如，Unit 1中的非重读词、Unit 5中的句子重音）。

## 安装
1. **先决条件**：
   - MR/VR硬件：兼容的头显，如Microsoft HoloLens、Oculus Quest或Meta Quest（用于VR）。
   - 软件：Unity 2021或更高版本、Visual Studio和现代网页浏览器（用于AI界面）。
   - AI工具：Python 3.8+、TensorFlow或PyTorch用于AI模型，以及语音识别API（例如，Google Speech-to-Text）。

2. **安装步骤**：
   - 克隆本仓库：
     ```bash
     git clone https://github.com/yourusername/mr-vr-ai-teaching.git
     ```
   - 安装依赖：
     ```bash
     cd mr-vr-ai-teaching
     pip install -r requirements.txt
     ```
   - 在`UnityProject/`中打开Unity项目，并为您的头显配置VR/MR设置。
   - 使用Python运行`ai-scripts/`中的AI脚本，用于聊天机器人和语法反馈。

3. **配置**：
   - 更新`config.json`文件，输入您的语音识别和云服务的API密钥。
   - 在Unity中调整VR/MR场景，以匹配您的硬件规格。

## 使用方法
- **教师**：使用MR/VR应用创建沉浸式课程，分配AI聊天机器人对话，并通过仪表盘跟踪学生进度。
- **学生**：佩戴VR头显探索虚拟环境（例如，动物园、餐厅），与AI互动练习，并完成如设计动物园或写关于最爱动物的帖子等项目。
- **访问内容**：
  - 在您的MR/VR设备上启动Unity构建的应用。
  - 通过网页浏览器或移动应用访问AI界面（例如，`http://localhost:5000`用于聊天机器人）。

## 技术要求
- **硬件**：支持MR/VR的PC或游戏机，8GB+内存，GPU支持VR渲染。
- **软件**：Unity 2021+、Python 3.8+、node.js（用于网页界面）和Git客户端。
- **网络**：稳定的互联网连接，用于AI云服务和GitHub更新。

## 贡献
我们欢迎贡献！请fork本仓库，进行修改后提交拉取请求。请遵循`CONTRIBUTING.md`中的编码指南。

## 许可
本项目采用MIT许可 - 请参阅`LICENSE`文件了解详情。

## 联系方式
如有问题或需要支持，请通过电子邮件联系我们：`24433797@qq.com`，或在GitHub上打开问题。

## 鸣谢
- 灵感来源于《Contents》教材（Units 1-8）。
- 感谢MR/VR和AI社区提供的开源工具和库。
