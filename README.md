# IT-English-Study

> 🎯 **IT 技术英语与自然拼读学习环境** — 帮助 JavaWeb 开发者精通技术英语，彻底摆脱机翻依赖

---

## 📖 项目简介

这是一个高度结构化的技术英语学习环境，专为 JavaWeb 后端开发者设计。采用**引导式学习法**和**语音优先策略**，聚焦于：

- **SpringBoot** 官方文档
- **MySQL** 文档与错误信息
- **Redis** 文档与命令说明
- **Java** 官方文档与报错日志

---

## 🎯 核心教学理念

### 1. 语法 = 代码逻辑
将英语句子结构映射为编程概念：
```
主谓宾 → instance.method(argument)
定语从句 → filter function (过滤函数)
介词短语 → 作用域边界
```

### 2. 语音优先
每个新词必须先学发音：
- **音标 (IPA)** = 字节码（底层规则）
- **自然拼读 (Phonics)** = 编译器（字母→读音）

### 3. 苏格拉底法
绝不直接倾倒翻译，而是：
1. 让你识别已知关键字
2. 引导你基于开发经验"盲猜"含义
3. 拆解句子结构
4. 通过"理解测试"后才给出翻译

---

## 📁 项目结构

```
IT-English-Study/
│
├── CLAUDE.md                    # AI 导师指导准则
├── README.md                    # 项目说明（本文件）
│
├── progress/                    # 学习进度追踪
│   └── it-english-tracker.md   # 全局进度追踪器
│
├── vocabulary/                  # 词汇库
│   ├── error-log-vocabulary.md # 报错日志词汇
│   ├── documentation-vocabulary.md  # 文档词汇
│   └── core-it-vocabulary.md   # 核心 IT 词汇
│
├── phonics/                     # 音标与拼读
│   └── phonics-guide.md        # 美式音标与自然拼读指南
│
├── sessions/                    # 学习会话记录
│   └── YYYY-MM-DD/             # 按日期组织的会话
│       └── session-notes.md    # 会话笔记
│
└── examples/                    # 学习示例
    ├── error-logs/             # 报错日志示例
    └── docs/                   # 官方文档示例
```

---

## 🚀 如何开始学习

### 步骤 1：提供学习材料
向 AI 导师提供以下任一内容：
- 一段 Java/SpringBoot/MySQL/Redis 报错日志
- 一段官方技术文档

### 步骤 2：互动学习
AI 将引导你完成以下流程：

```
变量检查 → 语音拆解 → 逻辑映射 → 理解测试
```

### 步骤 3：记录进度
学习成果将自动记录到：
- `/progress/it-english-tracker.md` — 全局进度
- `/sessions/YYYY-MM-DD/session-notes.md` — 当日笔记

---

## 📊 学习领域权重

| 领域 | 权重 | 说明 |
|------|------|------|
| 📛 报错日志与异常解析 | **30%** | 最高优先级 |
| 📚 官方文档阅读 | **25%** | 配置与架构表达 |
| 💻 核心 IT 词汇与词根 | **20%** | 数据库、缓存、前缀后缀 |
| 🔤 音标与拼读体系 | **15%** | 48音标、音节划分 |
| 🧠 基础语法逻辑映射 | **10%** | 语法→编程类比 |

---

## ⚠️ 核心准则

✅ **必须做**：
- 使用编程类比解释语言现象
- 为每个新词提供音标和音节拆解
- 鼓励基于 IT 逻辑的合理猜测

❌ **绝不做**：
- 直接倾倒大段中文翻译
- 使用晦涩的传统语法术语
- 跳过语音解析步骤

---

## 🔗 相关资源

- [Spring Boot 官方文档](https://docs.spring.io/spring-boot/docs/current/reference/html/)
- [MySQL 官方文档](https://dev.mysql.com/doc/)
- [Redis 官方文档](https://redis.io/documentation)
- [Java 官方文档](https://docs.oracle.com/javase/)

---

## 📝 版本信息

- **创建日期**：2026-03-27
- **当前版本**：1.0.0
- **适用对象**：JavaWeb 后端开发者

---

> **这里是技能训练场，不是 Google 翻译。**
> 让我们一起用程序员的思维，征服技术英语！ 💪
