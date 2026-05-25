# 项目管理认证培训开源工具归档库

本仓库由**中智AI教育数字团队**维护，用于归档与项目管理、PMP认证、Scrum培训、敏捷学习相关的开源工具与学习资源，方便后续评估、部署和使用。

![中智AI教育](https://img.shields.io/badge/中智AI教育-项目管理认证工具归档-blue)
![License](https://img.shields.io/badge/license-Apache%202.0-blue.svg)

---

## 📚 已归档项目

### 1. OpenOLAT - 企业级开源学习管理系统

| 项目信息 | 详情 |
|---------|------|
| **项目名称** | OpenOLAT |
| **项目描述** | Learning Management System - 功能完整的开源LMS平台 |
| **上游地址** | https://github.com/OpenOLAT/OpenOLAT |
| **镜像仓库** | https://github.com/chinawisdom/openolat |
| **项目文档** | https://docs.openolat.org |
| **Star数量** | 422 ⭐ |
| **开源协议** | Apache 2.0 License |
| **主要语言** | Java |
| **默认分支** | master |
| **最后更新** | 2026-05-24 |

#### 🎯 核心功能
- ✅ **课程管理**：模块化课程设计，支持SCORM、ImsCP标准
- ✅ **在线评估**：QTI标准测试系统，支持题库管理
- ✅ **证书颁发**：完成课程后自动颁发证书
- ✅ **学习跟踪**：详细的学习进度和掌握程度分析
- ✅ **沟通协作**：论坛、消息、通知系统
- ✅ **REST API**：完善的API接口，支持系统集成
- ✅ **多语言支持**：国际化界面
- ✅ **响应式设计**：PC、平板、手机多端适配

#### 🎓 与PMP/项目管理培训的适配点

| 培训场景 | 适配功能 | 应用示例 |
|---------|---------|---------|
| **PMP认证培训** | 课程管理 + 测试评估 | 将PMBOK十大知识领域设计为结构化课程 |
| **学习路径规划** | 进度跟踪 + 证书管理 | 为学员规划3-6个月PMP备考路径 |
| **模拟考试** | QTI测试系统 | 创建PMP模拟试题库，支持随机组卷 |
| **继续教育** | PDU积分管理 | 为PMP持证者提供继续教育课程 |
| **Scrum培训** | 协作工具 + 实践演练 | 敏捷角色扮演、冲刺规划实践 |
| **企业内训** | 用户管理 + 报表统计 | 千人级企业项目管理培训 |

#### 🚀 快速部署

```bash
# 1. 克隆镜像仓库
git clone https://github.com/chinawisdom/openolat.git
cd openolat

# 2. 添加上游仓库（可选，用于同步更新）
git remote add upstream https://github.com/OpenOLAT/OpenOLAT.git

# 3. 查看可用分支
git branch -a

# 4. 切换到所需版本（例如 OpenOLAT_12.5）
git checkout OpenOLAT_12.5

# 5. 按照官方文档进行编译部署
# 参考：https://docs.openolat.org/manual_admin/installation/installGuide/
📦 技术栈
后端：Java 17 + Spring Framework
数据库：PostgreSQL（推荐）、MySQL、Oracle
应用服务器：Tomcat 10.0/10.1
构建工具：Maven 3.8+
前端：JavaScript、CSS（支持压缩和聚合）
🔄 同步上游更新
使用提供的同步脚本保持镜像仓库与上游同步：

Bash

# 首次设置
bash setup-openolat-sync.sh

# 完整同步所有分支
bash sync-openolat.sh

# 日常快速更新
bash quick-sync.sh
📖 相关文档
📘 用户手册
🔧 管理员手册
💻 开发者文档
📧 邮件列表
🌐 社区平台
🏢 商业支持
本项目由 frentix GmbH（瑞士）开发和维护，提供专业的企业级支持服务。

🗂️ 仓库用途
集中管理：项目管理培训相关的开源工具
私有部署：为企业/机构私有化部署提供参考与归档
快速评估：记录每个工具的适配场景、部署方案与使用建议
知识沉淀：整理培训课程模板与最佳实践
📋 后续计划
 持续补充更多项目管理、PMP、Scrum相关的开源学习工具
 完善每个工具的部署与使用指南
 整理PMP培训课程模板与试题库资源
 建立工具对比评估矩阵
 开发自动化部署脚本集
🤝 贡献与反馈
本仓库由中智AI教育数字团队 - 有子负责维护。

如有建议或需要补充其他开源工具，请：

提交 Issue
联系维护团队
参与项目管理认证培训开源工具生态建设
📊 统计信息
指标	数值
已归档项目	1
涵盖培训领域	PMP、Scrum、敏捷、企业内训
开源协议	Apache 2.0
最后更新	2026-05-25
归档日期：2026-05-25
维护团队：中智AI教育数字团队
仓库地址：https://github.com/chinawisdom/cwco1
镜像仓库：https://github.com/chinawisdom/openolat

本仓库致力于为项目管理从业者提供高质量的开源培训工具资源，助力企业培训数字化转型。

