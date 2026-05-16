# 🏯 龙川文化推广 Skill

龙川县文化推广 Claude Code Skill，提供 24 镇 IP 形象、非物质文化遗产、乡镇特色文化、节日习俗及旅游路线查询。

## 功能

- **24 镇文化介绍**：每个镇的发展定位、特色产业、文化地标
- **IP 形象查询**：24 镇专属 IP 名称、设计原型、形象寓意
- **非遗项目详解**：省级/市级/县级非物质文化遗产
- **节日民俗查询**：岁时节令、传统民俗、红色纪念活动
- **旅游路线推荐**：6 条主题文旅路线（秦汉文化、红色记忆、山水生态等）

## 安装

```bash
git clone https://github.com/Foxelf-Studio/longchuan-culture.git ~/.claude/skills/longchuan-culture
```

安装后重启 Claude Code，之后在任意项目提到"龙川""佗城""客家""非遗"等关键词即自动触发。

## 使用示例

> "龙川县有多少个镇？"

> "什么是霍龙传说？"

> "推荐一条龙川的文化旅游路线"

> "铁场镇的 IP 形象是什么？"

## 目录结构

```
longchuan-culture/
├── SKILL.md                      # 主文件：触发规则 + 24镇索引
└── references/
    ├── overview.md               # 龙川概况
    ├── towns.md                  # 24镇文化特色
    ├── ip-images.md              # 24镇IP形象
    ├── intangible-heritage.md    # 非遗项目
    ├── festivals.md              # 节日民俗
    └── travel-routes.md          # 文旅路线
```
