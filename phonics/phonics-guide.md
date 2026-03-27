# 美式音标与自然拼读指南

> 基于认知科学"语音环路"理论，建立发音基础

---

## 🎵 美式音标总表 (American English IPA - 48 Sounds)

### 元音 (Vowels - 20个)

#### 单元音 (Monophthongs - 14个)

| 音标 | 例词 | 类比记忆 |
|------|------|----------|
| /i/ | see, bean | "衣"的长音，像 `int` 里的 i |
| /ɪ/ | sit, bit | 短促的"衣"，介于衣和ei之间 |
| /e/ | bed, head | 像梅花音的短版 |
| /ɛ/ | red, said | 类似"诶"的短音 |
| /æ/ | cat, bad | "梅花音"，嘴巴张大 |
| /ɑ/ | father, car | 类似"啊" |
| /ɔ/ | dog, thought | 类似"奥" |
| /ʊ/ | book, put | 类似"呜"的短音 |
| /u/ | food, blue | "呜"的长音 |
| /ʌ/ | cup, luck | 类似"厄"的短音，重读时出现 |
| /ə/ | about, banana | "中央元音"，弱读音节 |
| /ɜr/ | bird, word | 卷舌的"厄" |
| /aɪ/ | time, my | "爱"的双元音 |
| /aʊ/ | out, now | "傲"的双元音 |

#### 双元音 (Diphthongs - 6个)

| 音标 | 例词 | 拼音类比 |
|------|------|----------|
| /eɪ/ | say, day | ei → "A"的发音 |
| /oʊ/ | go, know | ou → "O"的发音 |
| /aɪ/ | time, my | ai → "爱" |
| /aʊ/ | out, now | au → "傲" |
| /ɔɪ/ | boy, toy | oi → "奥伊" |
| /ju/ | use, cute | iu → "优" |

### 辅音 (Consonants - 28个)

| 音标 | 例词 | 类比记忆 |
|------|------|----------|
| /p/ | pen, map | 清辅音，送气 |
| /b/ | bed, lab | 浊辅音，不送气 |
| /t/ | tea, sit | 清辅音 |
| /d/ | dog, bad | 浊辅音 |
| /k/ | cat, back | 清辅音 |
| /g/ | go, bag | 浊辅音 |
| /f/ | five, life | 咬唇音 |
| /v/ | very, have | 咬唇震动 |
| /θ/ | think, three | 咬舌音，清 |
| /ð/ | this, that | 咬舌音，浊 |
| /s/ | see, class | 舌尖音 |
| /z/ | zoo, is | 舌尖震动 |
| /ʃ/ | she, fish | "嘘"的音 |
| /ʒ/ | vision, measure | 浊化的"嘘" |
| /h/ | he, have | 气声 |
| /tʃ/ | chair, teach | "吃"的音 |
| /dʒ/ | job, page | "知"的音 |
| /m/ | me, time | 闭嘴音 |
| /n/ | no, ten | 鼻音 |
| /ŋ/ | sing, thing | 后鼻音 |
| /l/ | like, all | 舌尖音 |
| /r/ | red, car | 卷舌音 |
| /w/ | we, how | 唇音 |
| /j/ | yes, you | 半元音 |
| /hw/ | what, white | 浊化的w |
| /j/ | use, cute | y音 |

---

## 📚 自然拼读规则 (Phonics Rules)

### 规则 1：Magic E (哑巴E规则)

当单词以 `e` 结尾且前面有元音时，前面的元音发长音（字母本音）。

| 短音 | 长音 (Magic E) |
|------|----------------|
| cap /æ/ → cape /eɪ/ | 配置 (configuration) |
| hop /ɑ/ → hope /oʊ/ | |
| kit /ɪ/ → kite /aɪ/ | |
| cut /ʌ/ → cute /ju/ | |

**编程类比**：结尾的 `e` 就像是一个类型转换器，把短元音"强转"成长元音。

### 规则 2：R 控制元音 (R-Controlled Vowels)

当元音后面跟着 `r` 时，元音发音会被改变：

| 组合 | 发音 | 示例 |
|------|------|------|
| ar | /ɑr/ | car, start, `parse` |
| or | /ɔr/ | for, port, `import` |
| er | /ɜr/ | her, server, `transfer` |
| ir | /ɜr/ | bird, first, `virtual` |
| ur | /ɜr/ | turn, burn, `return` |

**编程类比**：`r` 就像是一个"拦截器"(Interceptor)，改变了前面元音的行为。

### 规则 3：常见元音组合

| 组合 | 发音 | 示例 | IT词汇 |
|------|------|------|--------|
| ai/ay | /eɪ/ | day, say | `await`, `layout` |
| ee/ea | /i/ | see, sea | `thread`, `stream` |
| ie | /i/ | field | `field`, `yield` |
| oa | /oʊ/ | boat | `load`, `upload` |
| oo | /u/ 或 /ʊ/ | food, book | `pool`, `lookup` |
| ou/ow | /aʊ/ | out, now | `timeout`, `output` |
| oi/oy | /ɔɪ/ | boy, toy | `deploy` |

### 规则 4：常见辅音组合

| 组合 | 发音 | 示例 | IT词汇 |
|------|------|------|--------|
| ch | /tʃ/ | chair | `catch`, `patch` |
| sh | /ʃ/ | she | `push`, `flush` |
| th | /θ/ 或 /ð/ | think, this | `thread`, `throughput` |
| ph | /f/ | phone | `phrase`, `physical` |
| gh | 静音或 /f/ | night, enough | `weight`, `though` |

### 规则 5：常见后缀发音

| 后缀 | 发音 | 示例 | IT词汇 |
|------|------|------|--------|
| -tion | /ʃən/ | action | `configuration`, `connection` |
| -sion | /ʒən/ | vision | `decision`, `expansion` |
| -ture | /tʃər/ | future | `architecture`, `structure` |
| -ous | /əs/ | famous | `synchronous`, `anonymous` |
| -able | /əbəl/ | able | `serializable`, `configurable` |
| -ible | /əbəl/ | possible | `accessible`, `visible` |
| -ful | /fəl/ | beautiful | `helpful`, `successful` |
| -less | /ləs/ | careless | `stateless`, `connectionless` |

**编程类比**：后缀就像"接口"或"注解"，给单词添加特定的语义标签。

---

## 🔢 音节划分规则

### 基本原则

1. **每个音节必须包含一个元音音素**
2. **两个元音之间通常有一个音节分界**
3. **辅音组合通常不拆分**（如 `th`, `ch`, `sh`）

### 划分方法 (VCV / VCCV)

| 模式 | 划分位置 | 示例 |
|------|----------|------|
| VCV | V-CV 或 VC-V | `o-pen`, `con-fig` |
| VCCV | VC-CV | `ap-ple`, `but-ton` |
| VCCCVC | VCC-CV | `con-struct`, `in-stall` |

**编程类比**：音节划分就像代码的"模块化"，把长单词拆分成可管理的小单元。

---

## 📖 已掌握规则追踪

| 规则名称 | 掌握日期 | 练习次数 |
|----------|----------|----------|
| - | - | - |

---

> 本指南将随学习进度持续更新
