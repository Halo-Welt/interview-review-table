# 面试复盘总结表

根据面试记录（录音转写、纪要或聊天记录）和岗位 JD，生成七列面试复盘表，并用飞书 CLI 以原生表格追加写入指定飞书文档末尾。

适用于 Cursor 及兼容 Agent Skills 规范的环境。

## 安装

```bash
git clone https://github.com/Halo-Welt/interview-review-table.git ~/.cursor/skills/interview-review-table
```

## 使用

提供三样东西后，让 agent 按本 skill 整理：

1. 面试记录
2. 岗位 JD
3. 目标飞书文档 URL

输出是一张七列表格：序号、面试官问题、考察方向、候选人回答、评分、建议、备注。
