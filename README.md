# Markdown Cheat Sheet

This is a simple markdown cheat sheet for Github users. Hope you find it helpful. 🙂

||<div align="center">Result</div>|<div align="center">Markdown</div>|
|:---:|:---|:---|
|Headings|<h1>Heading L1</h1> <h2>Heading L2</h2> <h3>Heading L3</h3> <h4>Heading L4</h4> <h5>Heading L5</h5> <h6>Heading L6</h6>|`# Heading L1`<br> `## Heading L2`<br> `### Heading L3`<br> `#### Heading L4`<br> `##### Heading L5`<br> `###### Heading L6`<hr> Note: There is a space between the number signs (&num;) and the heading name.|
|Font weights and styles|Normal text<br><br>  **Bold text 1**<br> __Bold text 2__<br><br> *Italic text 1*<br> _Italic text 2_<br><br> _combine **bold** and Italic text_<br><br> ~~strikethrough text~~|`Normal text`<br><br>  `**Bold text 1**`<br> `__Bold text 2__`<br><br> `*Italic text 1*`<br> `_Italic text 2_`<br><br> `_combine **bold** and Italic text_`<br><br> `~~strikethrough text~~`|
|Paragraphs|<p>This is paragraph one.</p><p>This is paragraph two and I am longer than paragraph one.</p>|<p>This is paragraph one.</p><p>This is paragraph two and I am longer than paragraph one.</p><hr> Note: Use `a blank line` to separate paragraphs.|
|Line Breaks|<p>This is line one.<br>This is line two and I am longer than line one.<p/>|<p>This is line one.<br>This is line two and I am longer than line one.<p/><hr> Note: Add `two or more spaces` after a line to create line breaks.|
|Unordered Lists|<h4>Unordered List</h4><ul><li>Item a</li><li>Item b</li><li>Item c</li></ul><h4>Unordered List with Sub-list</h4><ul><li>Item a</li><li>Item b<ul><li>Item b1</li><li>Item b2</li></ul></li><li>Item c</li></ul>|<h4>Unordered List</h4> `* Item a`<br> `* Item b`<br> `* Item c`<br> <h4>Unordered List with Sub-list</h4> `* Item a`<br> `* Item b`<br> <small>&ensp;&ensp;`* Item b1`</small><br> <small>&ensp;&ensp;`* Item b2`</small><br> `* Item c`<hr> Note:<br> 1. You can use dashes (&minus;) or plus signs (&plus;) to replace asterisks (&ast;) to create the same result.<br> 2. Add `two or more spaces` before an item to create sub-list items.|
|Ordered Lists|<h4>Ordered List</h4><ol><li>First item</li><li>Second item</li><li>Third item</li></ol> <h4>Ordered List with Sub-list</h4> <ol><li>First item</li><li>Second item<ol><li>Item 2a</li><li>Item 2b</li></ol></li><li>Third item</li></ol>|<h4>Ordered List</h4> `1. First item`<br> `2. Second item`<br> `3. Third item`<br> <h4>Unordered List with Sub-list</h4> `1. First item`<br> `1. Second item`<br> <small>&ensp;&ensp;&ensp;`1. Item 2a`</small><br> <small>&ensp;&ensp;&ensp;`1. Item 2a`</small><br> `1. Third item`<hr> Note:<br> 1. The numbers should start with the number one, but the rest of them don’t have to be in numerical order.<br> 2. Add `three or more spaces` before an item to create sub-list items.|
|Checkboxes|![screenshot](https://user-images.githubusercontent.com/13745974/102015478-c6186700-3d53-11eb-9e74-eb1e8f38e0c3.png "checkboxes")<br> ✍️	|`- [ ] Item 1`<br>  `- [x] Item 2`<br>|
|Links|I love [GitHub](http://www.github.com/ "This is an optional title.").<br> <https://www.google.com><br> <name@email.com>|I love `[Alt Text](http://www.github.com/ "This is an optional title.")`.<br> `<https://www.google.com>`<br> `<name@email.com>`|
|Tables|<table><tr><th>column 1</th><th>column 2</th><th>column 3</th></tr><tr><td align="left">row 1a</td><td align="center">row 1b</td><td align="right">row 1c</td></table>|<code>&#124;column 1&#124;column 2&#124;column 3&#124;</code><br> <code>&#124;:---&#124;:---:&#124;---:&#124;</code><br> <code>&#124;row 1a&#124;row 1b&#124;row 1c&#124;</code><hr> Note: Use `:---` to align table contents to the left; Use `:---:` to align table contents to the centre; Use `---:` to align table contents to the right.|
|Images|Inline-style:<br> <img src="https://user-images.githubusercontent.com/13745974/101995882-4348cb00-3cc5-11eb-8d87-8384a9b0f940.png" alt="This is an optional title."><br> <br> Reference-style:<br> <img src="https://user-images.githubusercontent.com/13745974/102792437-6c8de900-43a0-11eb-8945-b1f172aff7d0.png" alt="This is an optional title.">|Inline-style:<br> `![Alt Text](/path-to/your-image.png "This is an optional title.")`<br><br> Reference-style:<br> `![octocat][logo]`<br><br> `[logo]: /path-to/your-image.png "This is an optional title."`|
|Code Blocks|<h4>Code Block</h4> ![screenshot](https://user-images.githubusercontent.com/13745974/102013712-c449a600-3d49-11eb-8bc4-564867fa4da4.png "code block")<br> <h4>Code Block with Highlight</h4> ![screenshot](https://user-images.githubusercontent.com/13745974/102013716-c6ac0000-3d49-11eb-9620-d58f93d61d7f.png "code block with highlight")<br> <h4>Code Block with Diff</h4> ![screenshot](https://user-images.githubusercontent.com/13745974/102013719-c90e5a00-3d49-11eb-9252-dc6ea1a9d8c3.png "code block with diff")<br> ✍️|<h4>Code Block</h4> <code>&#96;&#96;&#96;</code><br> `const greeting = "Hello World!";`<br> `console.log(greeting);`<br> <code>&#96;&#96;&#96;</code><br> <h4>Code Block with Highlight</h4> <code>&#96;&#96;&#96;JavaScript</code><br> `const greeting = "Hello World!";`<br> `console.log(greeting);`<br> <code>&#96;&#96;&#96;</code><br> <h4>Code Block with Diff</h4> <code>&#96;&#96;&#96;diff</code><br> `- const data = [];`<br> `+ const data = {};`<br> <code>&#96;&#96;&#96;</code><hr> Note:<br> 1. Alternatively, you can put `4 spaces` in front of every line of code to create a code block.<br> 2. You can swap `JavaScript` to other programme language names to highlight different languages in the code block.|
|Inline Codes| `console.log("Hello World!");`|<code>&#96;console.log("Hello World!);&#96;</code>|
|Blockquotes|<blockquote>This is a quote.</blockquote>|`> This is a quote.`|
|Mention issues|#523|`#523`|
|Mention users|@username|`@username`|
|Emojis|🙂 👋 |🙂 👋 <hr> Note: There are lots of emojis you can use, please have a look at this [emoji cheat sheet](https://github.com/ikatyang/emoji-cheat-sheet "emoji cheat sheet").|
|Horizontal Rules|<hr>|`---`<hr> Note: Alternatively, you can use `***` (three asterisks) or `___` (three underscores) to replace `---` (three Hyphens).|
|HTML Tags|10 Downing Street<br> London<br> United Kingdom|10 Downing Street`<br>` London`<br>` United Kingdom<hr> Note: You can use any HTML tags.|

✍️&nbsp;&nbsp;&nbsp;Because of some limitations in markdown, I use `images` to represent the render results.