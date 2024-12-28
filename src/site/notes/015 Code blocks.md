---
{"dg-publish":true,"permalink":"/015-code-blocks/","dgPassFrontmatter":true,"noteIcon":""}
---

These codeblocks should not be modified upon publish.

Sample 1
```jinja2
{{ highlight_text }}{% if highlight_location and highlight_location_url %} ([via]({{highlight_location_url}})){% elif highlight_location %} ({{highlight_location}}){% endif %} ^rwhi{{highlight_id}}
{% if highlight_note %}
{{ highlight_note }} ^rwhi{{highlight_id}}-note
{% endif %}
```

Sample 2
```md
In medieval Latin a florilegium (plural florilegia) was a compilation of excerpts from other writings.
 The word is from the Latin flos (flower) and legere (to gather): literally a gathering of flowers, or collection of fine extracts from the body of a larger work. ([via](https://en.wikipedia.org/wiki/Florilegium)) ^rwhi724352030
```

Sample 3
```
This codeblock has a transclusion syntax in it.
Check it out: 
<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/001-links/" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">




[[002 Hidden page]]

[[003 Non published page]]

[[000 Home| Aliased link to home]]

[[000 Home | Link containing whitespace which works in obsidian but doesn't in garden :) - yes, this could be a ticket but lo and behold]]



</div></div>

```

And for sanity, here's some block references outside of code blocks: foobar
{ #test-123}
