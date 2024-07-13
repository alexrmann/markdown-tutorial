# etch-a-sketch
The Odin Project Foundations course Etch-a-Sketch challenge

## Text decoration

This is a basic paragraph.

*italic*

**bold**

***strong emphasis***

# Heading 1

## Heading 2

### Heading 3

#### Heading 4

##### Heading 5

###### Heading 6

###### This heading has a custom id {#custom-heading}

## Links

<http://theodinproject.com>

[Link to the Odin Project](http://theodinproject.com)

[A tagged link][1]

[A different tagged link][tag]

[1]: http://theodinproject.com

[tag]: http://theodinproject.com

[This is a link to the custom heading](#custom-heading) but I'm not sure if it is working and I don't presently know how to check. Perhaps you need enough content to have the tagged heading exist off-screen before the link will snap to the heading.

## Images

Basic image format:

![Image alt text](https://picsum.photos/200 "Tooltip goes here")

Tagged image link:

![Tagged image][tagimg]

[tagimg]: https://picsum.photos/id/25/367/267

Image with an external link:

[![Externally linked image](https://picsum.photos/id/24/367/267)](https://fastly.picsum.photos/id/24/4855/1803.jpg?hmac=ICVhP1pUXDLXaTkgwDJinSUS59UWalMxf4SOIWb9Ui4)

## Lists and Nesting

### Unordered Lists

+ milk
+ eggs
+ bread

### Ordered Lists

You don't need to number the list, just use the number "1." to mark an item in an ordered list.

1. Item A
1. Item B
1. Item C

### Sub Items

1. Step One
    * This is a sub bullet
    + This is also a sub bullet
        * And so is this. The style is not controlled by the syntax.
1. Step Two
    1. This is a sub ordered item
    1. This is another
1. Step Three
    
    Here is a nested paragraph. You can also nest images.

    ![Nested image](https://picsum.photos/200 "This is a nested image")

## Line Breaks

Just use an HTML <br>
tag to create a line break.

## Horizontal Rules

Here is a horizontal rule:

---

## Block Quotes

> This is a block quote.
>
> With two paragraphs.


## Code Blocks

Markdown accepts HTML and CSS (when placed in an HTML ```<style></style>``` tag.)

You can fence your code with ```triple tilde```.

You can also define the language you are using:

```html
<body>
    <h1>Hello World.</h1>
</body>
```

```js
let x = true;
const dog = `Great Dane`;
```

You can also show diff in code...

```diff
var x = 100;
- var y = 200;
+ var y = 300;
```

## Tables

Tables are created by piping cells and positioning headings and data above or below defined column syntax, respectively.

|Heading 1|Heading 2|Heading 3|
|---------|---------|---------|
|Item 1|Item 2|Item 3|
|Item A|Item B|Item C|

You can define the alignment of elements with colons:

### Right Aligned

|Heading 1|Heading 2|
|---------:|---------:|
|Item 1|Item 2|

### Left Aligned

|Heading 1|Heading 2|
|:---------|:---------|
|Item 1|Item 2|

### Centered

|Heading 1|Heading 2|
|:---------:|:---------:|
|Item 1|Item 2|

### Mixed

|Heading 1|Heading 2|
|:---------:|---------:|
|Item 1|Item 2|

## GitHub Syntax

### Check boxes

* [X] Milk
* [ ] Eggs
* [ ] Bacon

### Issue and user linking

Adding an issue number like #1 and @user tags will provide GitHub specific links that are not part of the standard Markdown syntax.