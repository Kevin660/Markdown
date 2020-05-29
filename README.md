# Syntax guide

Here’s an overview of Markdown syntax that you can use anywhere on GitHub.com or in your own text files.

# Table of Contents
1. [Headers](#headers)
1. [Emphasis](#emphasis)
1. [Lists](#lists)
1. [Blockquotes](#blockquotes)
1. [Code](#code)
1. [Links](#links)
1. [Task Lists](#task-lists)
1. [Tables](#tables)


## 1. Headers

# This is an \<h1> tag
## This is an \<h2> tag
###### This is an \<h6> tag

## 2. Emphasis

*This text will be italic*

_This will also be italic_

**This text will be bold**

__This will also be bold__

_You **can** combine them_

## 3. Lists

#### Unordered

* Item 1
* Item 2
  * Item 2a
  * Item 2b
  
#### Ordered

1. Item 1
1. Item 2
1. Item 3
   1. Item 3a
   1. Item 3b
   
## 4. Blockquotes

> We're living the

## 5. code

#### inline

`inline code here`

#### syntax highlighting for language

```javascript
function fa(arg) {
  console.log('javascript');
}
```

```python
def foo():
    if not bar:
        return True
```

#### quick indent four space

    function fa(arg) {
      console.log('javascript');
    }

## 6. Images

![GitHub Logo](/images/logo.png)
Format: ![Alt Text](url)

## 7. Links

http://github.com

[GitHub](http://github.com)

[Go](#go-to-here)

#### Go to Here

## 8. Task Lists

- [x] @mentions, #refs, [links](), **formatting**, and <del>tags</del> supported
- [x] list syntax required (any unordered or ordered list supported)
- [x] this is a complete item
- [ ] this is an incomplete item

## 9. Tables

First Header | Second Header
------------ | -------------
Content from cell 1 | Content from cell 2
Content in the first column | Content in the second column

