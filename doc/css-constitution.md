# CSS Constitution

## Comment Format
- 大枠（ Fonts, Global, Blog ） ... `/* { Name } -- start */` & `/* { Name } -- end */` の形式で書く
- 中枠（ Base, Layout, Widget ） ... 頭文字を大文字で書く
- 小枠（ header, footer, keyword, author .. ） ... すべて小文字で書く

Example:

```css
/* Global -- start */
/* Base */
html { ... }
...

/* Layout */
/* header */
header { ... }
...
/* Global -- end */
```

## Order of page
各枠の中でのページ固有スタイルの指定順序。

1. page-index
2. page-archive
3. page-category
4. page-about

## Constitution
```
// CHROMA Blog Style

Fonts
 |
 |-- Logo
 |
 |__ Code

Global
 |
 |-- Base
 |
 |-- Layout
 | |
 | |-- header(#globalheader-container)
 | |
 | |-- container
 | |
 | |__ footer
 |
 |__ Widget
   |
   |-- services
   |
   |__ footer link

Blog
 |
 |-- Layout
 | |
 | |-- page container
 | |
 | |-- header(#blog-title)
 | |
 | |-- content
 | |
 | |-- main(#wrapper, #main)
 | |
 | |__ footer(#box2)
 |
 |__ Widget
   |
   |-- top box
   |
   |-- breadcrumb
   |
   |-- blog logo(#blog-title h1)
   |
   |-- blog description(#blog-title h2)
   |
   |-- pager
   |
   |-- search form
   |
   |-- search result
   |
   |-- hatena module
   |
   |-- follow button
   |
   |-- profile icon
   |
   |-- category list
   |
   |-- about information
   |
   |-- entries
   |
   |-- entry
   |
   |-- entry header 
   |
   |-- entry content
   |
   |-- entry footer
   |
   |-- entry title
   |
   |-- entry categories
   |
   |-- entry date
   |
   |-- entry content components(.entry-content [element | class])
   |
   |-- entry author(.entry-footer-section .author)
   |
   |-- entry time(.entry-footer-time)
   |
   |-- entry hatena star
   |
   |-- entry social buttons
   |
   |-- entry comment
   |
   |__ entry edit menu
```
