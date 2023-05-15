<!--
---
title: override title
emoji: 💥
---
-->
# Test-Markdown
Testing markdown fences


```mermaid
 graph LR;
  A-->B;
  click A exampleCallback "Tooltip for a callback"
  click B "http://www.github.com" "This is a tooltip for a link"
```

```js
const exampleNumber = 12;
console.log(exampleNumber);
```

```mermaid
mindmap
  root((mindmap))
    Origins
      Long history
      ::icon(fa fa-book)
      Popularisation
        British popular psychology author Tony Buzan
    Research
      On effectiveness<br/>and features
      On Automatic creation
        Uses
            Creative techniques
            Strategic planning
            Argument mapping
    Tools
      Pen and paper
      Mermaid
```

<details>
  <summary>Testing supported HTML</summary>
  I think details are supported in gfm
</details>


```objectives
- [ ] Write a fenced block
- [ ] Parse it through the base64 blob
```

<!--
```objectives
- [ ] Write a fenced block
- [ ] Hide this one in comments
```
-->
