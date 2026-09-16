# 原则卡（从今天分享抽出的可复用知识）

## P1 搜索一直在变，别慌

【现场·Gary Illyes】

- 搜索每年 >5 万亿查询。三十年架构变化都是为了满足变化的信息需求。
- 年代：2000-2010 目录/pSEO/锚文本；2011-2022 编辑型/语义HTML；2023-2026 生成式/LLM+RAG。
- 2003 Florida 更新让Gary自己的站点收入归零。旧玩法会失效，工作还在。
- AIO链路：Query → Sub-Queries → Live Web Index → Passages → Synthesis → Claim Attribution。
- 金句：Don't panic. Things change. Figure it out.

## P2 Good SEO is Good GEO

【现场·Lily Ray】

- SEO和GEO不是二选一。多数GEO仍建在SEO基本功上。
- SEO可见度掉，AI引用也会掉。案例：5月17日某博客被罚后SEO崩、GEO跟崩。
- 危险手段：自吹Best X、成百上千对比页、规模化AI内容、互惠品牌提及、付费提及、Reddit灌水、寄生SEO、假新鲜、垃圾Schema、知识库投毒。
- Peec数据：listicles 15.77%→7.80%；comparisons 9.08%→6.17%。
- ChatGPT fan-out里 site: 增加，best/top/reviews/comparison/versus 减少。
- 目标不是做一篇被引用的页，是成为模型已经认识的品牌/实体。
- ALL Method：给真实SEO页加LLM层，不要另起垃圾页。
- 金句：Stop chasing shortcuts and play the long game.

## P3 关键内容写在HTML

【现场·Gary + Wasin】

- Google能深渲染；多数搜索引擎和AI爬虫不能。
- 内容只活在JS里 = 对AI隐形。
- Wasin实测：去掉JS依赖后，机器人访问与转化都翻倍以上，转化时间减半。
- 检查robots是否误伤AI爬虫；用语义HTML。

## P4 E-E-A-T是作业

【现场·日本场 + 官方Loki】

- 日本：link building doesn't work；only EEAT works。
- 付费外链在日本会被同行集体嫌弃。
- Loki：把180+页Quality Raters Guidelines拆成Do/Don't。
- 作者页、专家档案、品牌实体、真实权威 > 再多700个模板页。

## P5 出海不能套模板

【现场·Kun / 韩国 / 日本 + 官方Doug/Andrea/Jodie】

- Qwen引用：百度 8.1%，自有域名 0.8%，腾讯 2.4%，字节 1.6%。自己养模型 ≠ 自己被引用。
- 韩国Naver份额仍约40%，结果优先自家媒体。ChatGPT付费用户全球第二。
- 中国LLM引用6信号：新鲜度、长度、阅读量、社交、域名权威、生态接近度。
- 全球网页性能最佳实践在中国常常失效。

## P6 SEO是产品结果

【现场·Jine Wu + 官方Sam/David】

- SEO is a Product Outcome, Not an SEO Outcome。
- 上线前嵌入：潜力风险 → URL/结构/技术 → 设计与开发review → 上线前/后检查。
- 点击是中点不是终点。品牌被选择、被信任才算。
- 给高管讲SEO要用品牌认知与数字分发，不是排名报表。
