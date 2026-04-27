# aluminum-window-door-industry-research-skill

铝合金系统门窗行业动态调研 Skill for OpenClaw / QClaw

## 功能

自动化调研铝合金系统门窗行业动态，输出结构化报告到腾讯文档智能文档。

## 触发词

- /行业动态
- 帮我整理行业动态
- 铝合金门窗行业动态

## 工作流程

1. 多源搜索行业动态（multi-search-engine + online-search）
2. 抓取竞品网站（xbrowser）
3. 整理结构化报告（MDX 格式）
4. 输出到腾讯文档智能文档

## 文件结构

`
aluminum-window-door-industry-research/
├── SKILL.md                          # 技能主文件
├── references/
│   ├── competitor-sites.md           # 竞品网站列表
│   └── report-template.md           # 报告模板
└── scripts/                          # 脚本目录
`

## 依赖

- OpenClaw / QClaw
- multi-search-engine
- online-search
- xbrowser
- tencent-docs (腾讯文档 MCP)

## 使用方式

在 QClaw 中发送触发词即可自动执行完整调研流程。

## License

MIT