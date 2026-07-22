| 字段名 (Column) | 类型 (Type) | 约束 (Constraint) | 描述 (Description) |
| :--- | :--- | :--- | :--- |
| **`name`** | `TEXT` | `PRIMARY KEY` | **英文标签名**。Danbooru 原始标签（单词间以下划线 `_` 分隔）。 |
| **`category`** | `INTEGER` | - | **标签分类 ID**。例如：0-常规, 1-艺术家, 3-版权/作品, 4-角色, 5-元数据。 |
| **`cn_name`** | `TEXT` | - | **中文翻译**。由 Gemini 3 Flash 翻译 + 能工智人校对的结果。 |
| **`post_count`** | `INTEGER` | - | **引用数量**。该标签在 Danbooru 上的帖子总数，反映标签的热门程度。 |
