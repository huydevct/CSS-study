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

First: Create components
flexbox-1:

    display: flex;
    flex-direction: column;
flexbox-2:

    justify-content: flex-start | flex-end | center | space-between | space-around | space-evenly
    align-items: flex-start | flex-end | center | baseline | stretchs

    flex-basis: <length>

    flex-grow: <number>

    flex-shrink: 1* | <number>

    order: 0* | <number>

position

    position: static | relative | fixed | absolute | sticky
    top bottom left right
    
CSS Specificity

2D transform + transition

    translate
    rotate
    scale
    skew
    matrix

    transition: all 0.5s;(time = 0.5s or sth)

Media query

    @media (min-width)//(max-width){
    }

Grid

    display: grid;
    grid-template-columns: 2fr 1fr;
    grid-column: 1/3;
    
px vs em vs rem
    


