---
layout: post
title: "Log started — how this works"
lang: en
---

This is the first entry. This log documents the road from field engineer to principal-level BESS architect — course work, site lessons, telemetry experiments, and certification progress.

Posts here can be written in any of three languages. The layout adapts automatically: direction, fonts, and alignment follow the post language.

<div lang="ar" dir="rtl" markdown="1">

## مثال بالعربية

هذا نص تجريبي باللغة العربية. الملاحظات الميدانية من مشروع الجوف للتخزين ستُكتب هنا أحياناً بالعربية — المحاذاة من اليمين إلى اليسار تعمل تلقائياً، والخط عربي سليم.

</div>

<div lang="zh" markdown="1">

## 中文示例

这是中文测试文本。关于储能系统、电池管理系统和电网调峰的学习笔记，有时会用中文写在这里。中文字体已正确加载。

</div>

## How to write a new post

1. In the repo, open the `_posts/` folder → **Add file → Create new file**.
2. Name it exactly: `YYYY-MM-DD-my-title.md`
3. Start with the front matter:

```yaml
---
layout: post
title: "Your title"
lang: en    # or: ar  (Arabic, right-to-left)   or: zh  (Chinese)
---
```

4. Write below in plain Markdown. Commit. The post appears on the log within a minute.

Replace or delete this sample post whenever you write your first real one.
