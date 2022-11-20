# Suri

Suri is your own link shortener that's easily deployed as a static site. No
server-side hosting, serverless cloud functions, or database necessary. 

## Manage Links

Links are managed through [`src/links.json`](src/links.json), which is seeded
with a few examples to start:

```json
{
  "/": "https://github.com/raisilhamn",
  "yeah": "https://techlore.tech/",
  "rick": "https://www.youtube.com/watch?v=dQw4w9WgXcQ"
}
```
_Pro tip_: Bookmark the page to
[edit `src/links.json` directly in GitHub](https://github.com/jstayton/suri/edit/master/src/links.json)
(or wherever), and use the default commit message that's populated. Now show me
a link shortener that's easier than that!

![piratepx](https://app.piratepx.com/ship?p=e91ddd1b-31ad-4c36-b03e-be4a1e9a7678&i=suri)
