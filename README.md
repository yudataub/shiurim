# קטלוג השיעורים וההרצאות

https://yudataub.github.io/shiurim/

קטלוג אודיו לפי נושאים עם נגן מובנה. הקבצים עצמם יושבים בריפואי מדיה נפרדים
(`yudataub/shiurim-a01` ... `shiurim-a33`, עד ~900MB כל אחד — מגבלות GitHub Pages),
ומתנגנים ישירות מ-GitHub Pages.

- `index.html` — הקטלוג והנגן
- `data.js` — נוצר אוטומטית, אל תערכו ידנית
- `tools/publish.py` — מעתיק מ-G:, מעלה לריפואי המדיה ובונה את `data.js`
  (`python tools/publish.py status` / `all`). המצב נשמר ב-`tools/manifest.json`.

בשלב הזה: שיעורי אודיו בלבד, בלי מוזיקה ובלי וידאו. קבצים מעל 95MB לא עולים.
