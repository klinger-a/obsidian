```dataview
TABLE WITHOUT ID link AS "Link"
FLATTEN file.outlinks AS link
WHERE link != ""
GROUP BY link SORT link ASC
```
