# 沌沌 · 炉配置（config.md）
> 使用者装完skill后，第一件事：复制本文件为 config.local.md 并填写。
> 本文件=示例+字段说明。所有路径/维度名/语言风格都在这里配置——SKILL.md和模板永远不硬编码。

## 必填

### paths — 你的四库位置（沌沌备料从哪里取元素）
- elements_projects: ./projects/          # 案例/项目记录目录
- elements_knowledge: ./knowledge/        # 知识沉淀目录
- elements_input: ./inbox/                # 日常输入流（笔记/录音转写）
- crystals_out: ./crystals/               # 晶体卡HTML产出目录
- crystals_md: ./crystals/records/        # 晶体md存档目录

### dims — 你的进化维度（3-6个，默认五维可改）
维度名 + 说明 + 初始值(0-100)。雷达图自动按维度数重绘（3-6边）。
示例（王老师版）：讲授/方法论/交付/经营/枢纽
示例（学生版）：学习/实践/复盘/分享/专注
示例（团队版）：交付/协作/创新/质量/成长

### identity — 炉的名字与人格
- brand: 沌沌                    # 炉的名字（可改名：如"我的炼金屋"）
- motto: 沌沌兮如婴儿之未孩      # 卡片底部铭文
- grade_names: 晶体,晶核,纯晶    # 进化等级名（可自定义：如 铁剑/银剑/圣剑）

## 选填

### language — 卡片语言（zh/en，模板文字替换）
### style — 视觉主题（默认mystic-violet；可覆盖CSS变量）
### confidence — 置信度策略（conservative: 初产≤60 | standard: ≤70 | bold: ≤80）
### review — 回炉纪律（使用几次升晶核、几次未用降库存）
