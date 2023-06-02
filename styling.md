
## CSS Font Styles
There is still no proper solution for coloring the text as far as I know. However, there are still some solution for adding colors.
1. Screenshots *(Personally, I don't prefer this way since it takes quite some time to display the image.)*
2. [Between `$$$$`](https://github.com/NyanKaungSet/Markdown/blob/Updates/CSS.md#between-)
3. [Use dif](https://github.com/NyanKaungSet/Markdown/blob/Updates/CSS.md#using-diff)

### Between `$$$$`

$\textcolor{#3466ef}{\textsf{Colored text.}}$
$${\color{green}Preview\ text}$$
<a href="https://github.com/github/markup/issues/1440#issuecomment-1454732426">See this comment</a>
<hr>

${This\ is\ a\ {\color{red}Big}}\ Title$

<a href="https://stackoverflow.com/questions/11509830/how-to-add-color-to-githubs-readme-md-file">See this discussion</a>
<hr>

### Using Diff
```diff
+ Green
- Red
! Orange
@@ Pink @@
# Gray
```

<a href="https://github.com/github/markup/issues/1440#issuecomment-803889380">See this comment</a> 

---
## Aligning The Text

*markdown*

`<p align=center>This text is centered!</p>`<br>
`<p align=left>This text is aligned to the left!</p>`<br>
`<p align=right>This text is aligned to the right!</p>`

*Output*

<p align=center>This text is aligned center!</p>
<p align=left>This text is aligned to the left!</p>
<p align=right>This text is aligned to the right!</p>

Following HTML tag can be aligned:
1. h1 - h6
2. p
3. img
---
