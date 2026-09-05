# Pixiv Tag 中英文对照表 

![Tag Count](https://count.getloli.com/@ffdkj_tags?name=ffdkj&theme=booru-lewd&padding=6&offset=0&align=center&scale=2&pixelated=1&darkmode=auto&num=169438) 

## ***每日更新 !***

截止09月06日 03:50 已收录并翻译 **169438**+ 条标签。

收录所有 posts >= 100 的 tag，使用**Gemini3.1-flash-lite与Gemini3.5-flash-lite** 翻译 + 能工智人校对。如使用过程中遇到翻译错误可访问https://tagsuggest.zeabur.app 提交纠错或联系 2624696826a@gmail.com。


| 字段名 (Column)  | 类型 (Type) | 约束 (Constraint) | 描述 (Description)                                           |
| ---------------- | ----------- | ----------------- | ------------------------------------------------------------ |
| **`name`**       | `TEXT`      | `PRIMARY KEY`     | **Pixiv 标签名**。日文或英文原始标签。                       |
| **`cn_name`**    | `TEXT`      | `NOT NULL`        | **中文译名**。由 Gemini 3.1 Flash lite翻译 + deepseek falsh评分校对 + 能工智人查缺补漏的结果。  |
| **`en_name`**    | `TEXT`      | -                 | **英文名**。该标签对应的英文名称(如果有),pixiv的日文及其对应英文标签覆盖的post不同,因而一并保留。         |
| **`posts`**      | `INTEGER`   | -                 | **作品数**。该标签在 Pixiv 上的作品总数，反映热门程度。      |
| **`categories`** | `TEXT`      | -                 | **分类**。逗号分隔的 Pixiv 分类标签，如 General、Character、Design 等。 |

## Danbooru也有份!

[danbooru的tag中英文对照表](https://github.com/ffdkj/ffdkj-Danbooru_Tag-Chinese-English-Translation-Table)
---

> **Acknowledgment:** > README 的实时计数展示由 [Moe-Counter](https://github.com/journey-ad/Moe-Counter) 提供支持。感谢作者 [@journey-ad](https://github.com/journey-ad) 开发的猫娘计数器！
