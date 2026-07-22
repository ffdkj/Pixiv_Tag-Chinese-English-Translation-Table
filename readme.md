| 字段名 (Column)  | 类型 (Type) | 约束 (Constraint) | 描述 (Description)                                           |
| ---------------- | ----------- | ----------------- | ------------------------------------------------------------ |
| **`name`**       | `TEXT`      | `PRIMARY KEY`     | **Pixiv 标签名**。日文或英文原始标签。                       |
| **`cn_name`**    | `TEXT`      | `NOT NULL`        | **中文译名**。由 Gemini 3.1 Flash lite翻译 + deepseek falsh评分校对 + 能工智人查缺补漏的结果。  |
| **`en_name`**    | `TEXT`      | -                 | **英文名**。该标签对应的英文名称(如果有),pixiv的日文及其对应英文标签覆盖的post不同,因而一并保留。         |
| **`posts`**      | `INTEGER`   | -                 | **作品数**。该标签在 Pixiv 上的作品总数，反映热门程度。      |
| **`categories`** | `TEXT`      | -                 | **分类**。逗号分隔的 Pixiv 分类标签，如 General、Character、Design 等。 |
