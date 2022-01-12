# My Own MarkDown Cheat-Sheet

## How to create headings
To create a heading we need to start a line with a # followed by a space. Sub-headings can be created by using two hashes, eg ##. Several levels of headings can be created by adding more hashes.

To start a new paragraph we need to press enter twice.

*Italisized*

To italisize text we add an asterisk on each side of the text, for example, *this text should be italisized*

**Bold**

By adding two asterisks on each side the text will be rendered as bold: **This text should be bold**

***Italisized and Bold***

***By adding three asterisks on each side of the text, the text will be displayed as bold and italisized.***

## Making Lists

### Ordered Lists

1. one
1. two
1. three
1. four


1. item one
2. item two
3. item three
4. item four


1. item one
10. item two
1. item three
1000. item four


23. twenty-three
1. twenty-four
1. twenty-five
1. twenty-six


23. twenty-three
1. twenty-four
1000. twenty-five
1. twenty-six


23. twenty-three
24. twenty-four
25. twenty-five
26. twenty-six

### Unordered Lists

- Item One 
- Item Two 
- Item Three

+ Item One 
+ Item Two 
+ Item Three

* Item One 
* Item Two 
* Item Three

### Tick Boxes 

- [ ] Item One
- [ ] Item Two
- [x] Item Three

### Sublists 

Requires 3 spaces before list to create sublist

1. First Item 
   - Sub Item 
   - Sub Item

2. Second Item
   - Second Sub Item
   - Second Sub Item


### Links 


Add [] around the text to be displayed and () for the link:

[GitHub Website](https://github.com)

### Images 

To add an image add an ! infront:

![alt text](https://carpentries.github.io/lesson-example/assets/img/cp-logo-blue.svg "Carpentries Logo")

If you upload the image to yout local repository you only need to specify the name 

![Double Helix](fig/DNA_double_helix_horizontal.png)

### Code and Syntax Highlighting 

Add three () around your text to print it in a grey box

```
s = "This is a Python string"
print(s)
```
To get syntax highlighting, add the name of the programe language directly after the quote marks

```python
s = "This is a Python string"
print(s)
```

### Tables 

## Block Quotes

Add > infront of every line of the block:
> This is a block quote

> Every line starts with a > symbol followed by a space
>> This line starts with two > symbols follwed by a space. 

## Horizontal Rule 

1. ---
2. ***
3. ___


