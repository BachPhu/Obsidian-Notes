---
tag: list/hobby
---

```dataview
TABLE length as "Length", rating as "Rating", date as "Date Watched"
FROM #movie & #anime
sort rating desc
```
