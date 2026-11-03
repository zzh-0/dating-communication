# dating-communication

本仓库维护综合恋爱沟通 Skill。`SKILL.md` 为能力入口，版本号以其 frontmatter 中的 `metadata.version` 为准；当前为 `0.1.0`。

## 维护

- 保持 Skill 自包含，按任务读取 `references/`；`assets/relationship-context.md` 是输出模板，`agents/openai.yaml` 是界面元数据。
- 可发送的消息使用普通日常口语；分析与候选台词分开。默认多条候选及推荐值，用户明确要求的格式优先。
- 历史判断保留时间、证据与未知项，允许新消息更正旧判断；双方表达习惯分开整理。
- 示例自行撰写。真实聊天和保存的简报不进入仓库；`private/` 已忽略。保留正常自动发现，不因维护或测试而安装 Skill。
- README 面向使用者说明最终功能和使用方式，保持包内链接有效。

## 验证

使用可用的 `skill-creator/scripts/quick_validate.py` 检查仓库根目录，并核对相对链接。纯文档和打包改动检查文件、链接和元数据即可；行为变更再检查直接受影响的聊天场景。此仓库没有应用构建或自动化测试套件。
