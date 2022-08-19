# Markdown + Mermaid tutorial
        
**Table of Contents**
1. [Basic Syntax](#1-basic-syntax)
2. [Extended Syntax](#2-extended-syntax)
3. [Mermaid](#3-mermaid)

## 1. Basic Syntax
1. Headings: #, ##, ###
2. Text formatting
    - Bold: **bold** (double *)
    - Italic: *italic* (single *)
    - Bold & italic: ***bold and italic*** (triple *)
    - Strikethrough: ~~strikethrough~~ (double ~)
3. Block quote: >
> The Difference Between Stupidity and Genius Is That Genius Has Its Limits. <br> &mdash; ***Albert Einstein***
4. Lists
    - Ordered list: 1. 2. 3. 
    - Unordered list: -
5. Code: \` (backtick) <br>
    `const app = require('express')`
6. Link:
    - Internal link to a heading: \[`link text`\]\(\#`transformed heading`\) <br>
    💩💩💩 heading transformation rules: <br>
        - one or more whitespaces are replaced with a single hyphen -
        - uppercase letters are converted to lowercase
        - special characters are removed
    - External link/email link: \[`link text`\]\(`external URL`\)
        - My favorite search engine is [Google](https://google.com).
        - Contact me [Rui Wang](mailto:%20rui.wang.624@gmail.com)<br>
        Use %20 after `mailto:`, as blanks are not allowed in URL.
    - URL and email: \< \> <br>
    <https://google.com> <br>
    <rui.wang.624@gmail.com>

7. Embeded image: html <br>
    <img src="./asset/tiger.jpg" width="50" />
8. Horizontal rule: --- (triple -)
---



## 2. Extended Syntax
- 
- Fenced code block (with syntax highlighting): \`\`\` [language]
    ```typescript
    let x = 5;
    console.log(x ** 2);
    ```


## 3. Mermaid

1. Install 'Markdown Preview Mermaid Support' VSC extension
2. Format text
    - headings: #, ##, ### (multiple #)
    - italic: *italic* (single *)
    - bold: **bold** (double *)
    - strike-through: ~~strikethrough~~ (double ~)
    - bold and italic: ***bold and italic*** (triple *)
3. Blockquote
    > We shall not flag or fail. We shall go on to the end. We shall fight in France, we shall fight on the seas and oceans, we shall fight with 
    growing confidence and growing strength in the air. We shall defend our island, whatever the cost may be. We shall fight on the beaches, we 
    shall fight on the landing-grounds, we shall fight in the fields and in the streets, we shall fight in the hills. We shall never surrender!
    <br> &mdash; ***Winston Churchill***

    > Two things are infinite: the universe and human stupidity; and I'm not sure about the universe.
    <br> &mdash; ***Albert Einstein***
4. Lists
    - ordered list: 1. 2. 3. 4. (number .)
    - unordered list: - (hyphen)

```mermaid
graph TD;
    A-->B
    A-->C;
    B-->D;
    C-->D;
```
