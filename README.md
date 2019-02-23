# CSS Tutorial

- What CSS is
- CSS syntax
- Element, class and ID selectors
- Formatting text
- The box model
- Put it all together

### 1. What the heck is CSS?

##### CSS is Presentation

- CSS controls presentation of HTML
- Constantly changing standards
- Varying Support Across browsers

### 2. Default Browser Styles

##### Browsers Have Style!

- All browsers apply basic styling to HTML: 
    - Margin, Padding, Font size, Underlining links etc
- Browsers apply their own default styles

### 3. CSS Syntax

##### CSS is a colleciton of Rules

- Each rule targets a specific tag or element on a HTML document
    - Rule which targets all 'p' tags on a page
    - Rule which targets all tags with an #id
    - Rule which targets all 'a' tags in the #nav

###### Rules Come in 2 Parts

All CSS rules are made of two components:

SELECTOR        DECLARATION
`#page-header`  `{font-size: 10px;}`

###### Selectors

Selectors can target tag names, ID's, classes and many other things

```css
#header p {declaration}
.comment div  {declaration}
li  {declaration}
```

###### Declaration

Declarations contain properties and values

```css
#selector {font-size: 10px;}
#selector {
    font-size: 10px;
    color: red;
}
```
