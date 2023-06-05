## Adding Colors
There is still no proper solution for coloring the text as far as I know. However, there are still some solution for adding colors.
1. Screenshots *(Personally, I don't prefer this way since it takes quite some time to display the image.)*
2. [Between `$$`](https://github.com/NyanKaungSet/Markdown/blob/main/styling.md#between-)
3. [Use dif](https://github.com/NyanKaungSet/Markdown/blob/main/styling.md#using-diff)

### Between `$$`
**Syntax**<br>
`$\textcolor{HEX code}{\textsf{Colored text.}}$` or <br>
`$\textcolor{color name}{\textsf{Colored text.}}$` 

**Output**

$\textcolor{#3466ef}{\textsf{Colored text.}}$ <br>
$\textcolor{cyan}{\textsf{Colored text.}}$

$${\color{green}Preview\ text}$$
<a href="https://github.com/github/markup/issues/1440#issuecomment-1479512319">See this comment for further information.</a>
<hr>

### Another Way
**Syntax** <br>
`${This\ is\ a\ {\color{red}Big}}\ Title$`

**Output** <br>
${This\ is\ a\ {\color{red}Big}}\ Title$

[See this discussion for further information.](https://stackoverflow.com/questions/11509830/how-to-add-color-to-githubs-readme-md-file)

> **Note** 
> They create images of text, so you will not be able to copy the texts. 

*One more way is creating badge with shields.io. You will also be able to add background colors. However, you will not be able to copy the text, since they are also images of text.*

<hr>

### Using Diff
```diff
+ Green
- Red
! Orange
@@ Pink @@
# Gray
```

<a href="https://github.com/github/markup/issues/1440#issuecomment-803889380">See this comment for further information.</a> 

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

---

Following HTML tag can be aligned:
1. h1 - h6
2. p
3. img
---
