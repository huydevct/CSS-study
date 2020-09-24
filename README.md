color: #DDD
text-align: center/right/left/justify;
text-decoration: none/underline/overline/line-through
text-transform: uppercase/lowercase/capitalize
text-indent: 10px
letter-spacing: 5px
word-spacing: 10px
line-height: 1.2
text-shadow: x y color blur

font:
font-family: font1, font2, font3;
font-size: 20px;
font-style: normal | italic;
font-weight: normal | bold: 400 | 600 | 700 | 900;

padding
padding: top left-right bottom;
padding: top-bottom left-right;

margin
margin: top left-right bottom;
margin: top-bottom left-right;

border
Syntax:
    border-width: 1px
    border-style: solid | dotted | dashed | ...
    border-color: red
Shorthand:
    border: 1px solid red;
Note:
    border-width: top right bottom left
    border-width: top left-right bottom
    border-width: top-bottom left-right

    border-top-width: 1px;
    border-right-width: 1px;
    ...
    border-radius: 4px;
background-color:
    background-color: color;
    background-color: transparent; => Cùng màu với màu nền
    background-color: gradient; từ khóa: css gradient generator
    background-image: url(...)
    background-repeat: repeat-x | repeat-y | no-repeat | repeat* | ...
    background-size: % | contain | cover | auto* | ...
    background-position: x y | center
    background-attachment: scroll* | fixed
    abstract pattern 

Using icons
    font awesome => copy link cho vao head
    xem các link trên web r copy vào html


States:
    a:links
    a:visited
    a:hover
    a:active
List and tables: w3school.com
    list: 
        list-style: list-style-type list-style-position list-style-image: url("link");
    table:

inline and block:
    chuyển từ inline => block: display: block;
    chuyển từ block => inline: display: inline;

CSS combinators:
    descendant selector (space)
    child selector (>)
    adjacent sibling selector (+)
    general sibling selector (~)