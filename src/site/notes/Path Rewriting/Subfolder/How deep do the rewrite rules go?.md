---
{"dg-publish":true,"dg-path":"Subfolder/How deep do the rewrite rules go?.md","permalink":"/subfolder/how-deep-do-the-rewrite-rules-go/","dgPassFrontmatter":true,"noteIcon":""}
---

With the rewrite rules: 

```
Path Rewriting:
Subfolder:subfolder-rewritten
Path Rewriting/Subfolder:this-will-never-hit
```

Will this file be in folder `subfolder-rewritten` or in `Subfolder`?

It should be in Subfolder as "matching exits on first hit"