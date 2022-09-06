- [Markdown](#markdown)
  - [Titles](#titles)
  - [Paragraphs](#paragraphs)
  - [Line break](#line-break)
  - [Emphasis](#emphasis)
  - [Lists](#lists)
    - [Unordered (`<ul>...</ul>`)](#unordered-ulul)
    - [Ordered (`<ol>...</ol>`)](#ordered-olol)
  - [Links](#links)
  - [Images](#images)
  - [Code blocks](#code-blocks)
  - [Tables](#tables)
  - [Tasks list](#tasks-list)
  - [Github Flavored Markdown](#github-flavored-markdown)

# Markdown

- lightweight **markup language**
- generate formatted text

It is designed to be:
- easy to write using **any generic text editor**
- plain text format is **easy to read**

## Titles

- `# Title One` => `<h1>Title One</h1>`
- ...
- `###### Title Six` => `<h6>Title Six</h6>`

## Paragraphs

<!--
  separate paragraphs using an empty line
  equivalent to wrap each paragraph in a `p` html tag
-->
Paragraph one.

Paragraph two.

## Line break

<!-- 
  using trailing double space
  equivalent to use `</br>` in html, both lines wrapped in a `p` tag
 -->
Line 1. 
Line 2.

## Emphasis

- *foobar* = `<i>foobar</i>`
- **foobar** = `<b>foobar</b>`
- ***foobar*** = `<b><i>foobar</b></i>`
- ~~foobar~~ = `<strike>foobar</strike>`

## Lists

### Unordered (`<ul>...</ul>`)

- item 1
- item 2
  - item 2.1
  - item 2.2
- item 3

### Ordered (`<ol>...</ol>`)

1. item 1
2. item 2
   1. item 2.1
   2. item 2.2
3. item 3

## Links

- https://duckduckgo.com
- [Duck Duck Go](https://duckduckgo.com)

## Images

![Cute panda](./panda.jpg)
- `alt` attribute provides alternative information for an image if a user for some reason cannot view it

## Code blocks

```java
class Main {  
  public static void main(String args[]) { 
    System.out.println("Hello, world!"); 
  } 
}
```

## Tables

- [Markdown table creator](https://www.tablesgenerator.com/markdown_tables)

| Name | Quant |
|------|:------|
| foo  |   3   |
| bar  |   1   |
| baz  |   2   |

## Tasks list

- [] task 1
- [] task 2
- [x] task 3

## Github Flavored Markdown

- **no single standard**, therefore multiple implementations
- Markdown flavors (variants), they differ slightly
- although most of the topics discussed above are universal in all markdown variants, some like tasks list and code blocks may be available only in Github Flavored Markdown
