# Markdown CheatSheet
![markDown](https://camo.githubusercontent.com/a8e78444101b56ee75b4f2752e9616aef78a14a8174aa075d580585346a6b437/687474703a2f2f7061642e6861726f6f70726573732e636f6d2f646f63732f656e2f6d61726b646f776e2d646f632d6c6f676f732f696d616765732f6d61726b646f776e2e706e67)

## Text styling

```markdown
# This is heading 1

## This is heading 2

### This is heading 3

#### This is heading 4
```



`This is normal text.`

This is normal text.



This is  `**bold**`  by wrapping the text with double asterisk.

This is **bold** by wrapping the text with double asterisk.



This is` _italic_` by wrapping the text with single underscores.

This is _italic_ text.



Wrapping the text with double Tilda's would make a strikethrough.
`~~This is my first idea.~~`

~~This is my first idea.~~

This is my new idea.



## Adding Links

`This is a [website](google.com) link`

This is a [website](google.com) link.

## Adding Image

It's similar to adding links, the only difference is that it starts with an exclamatory symbol.
`![NameIfImageCannotBeDisplayed](/Images/GitHub_Logo_White.png)`

![Shubham](/Images/GitHub_Logo_White.png)

## Lists

To create an unordered list use the '-' symbol.

`- List 1`

`- List 2`

- List 1

- List 2

To create an ordered list, just add the list in numbered format.

1. List 1
2. List 2
3. List 3

### Nested List

```
- item 1 
  - item 1a
  - item 1b

- item 2
- item 3
```

- item 1 
  - item 1a
  - item 1b

- item 2
- item 3

### Check List

- [ ] item 1
- [ ] item 2
- [ ] item 3

## Table

```markdown
| heading1       |    heading2    |       heading3 |
| :------------- | :------------: | -------------: |
| row 1 column 1 | row 1 column 2 | row 1 column 3 |
```

| heading1       |    heading2    |       heading3 |
| :------------- | :------------: | -------------: |
| row 1 column 1 | row 1 column 2 | row 1 column 3 |

Note :

- The colon below heading 1 is on the left to ensure the column text is left aligned.
- The colon below heading 3 is on the right to ensure the column text is right aligned.
- You can't have a list inside a table, (but you can use some HTML to figure it out).

## Code

### Inline Code

```markdown
This is inline code `const name = 'Shubham';`, we use Backticks.
```

This is inline code `const name = 'Shubham';`

### Block of code

We make use of three Backtick's to wrap a block of code.
For syntax highlighting add the name of programming language you are using right after the first three Backtick's.

````
```js
function sayHello(name){
      console.log("Hello", ${name});
}
const name= 'Shubham';
sayHello(name);
```
````

```js
function sayHello(name){
      console.log("Hello", ${name});
}
const name= 'Shubham';
sayHello(name);
```

### Before and After in Code

Let's say you change a line in the block of code and you want to display it accordingly, to do that you can simply use the 'diff' after the first three Backticks.
Add '-' before the line of code that you want to change.
Add '+' before the new line of code you want to add.

````
```diff
- const firstName = 'Shubham';
+ const firstName = 'Divyanshi';
const lastName = 'Kadam';
```
````

```diff
- const firstName = 'Shubham';
+ const firstName = 'Divyanshi';
const lastName = 'Kadam';

```

### Quotes

Use '>' to create a quote, the quote is more like a question and the answer can be in a simple text as shown below.

```markdown
> I think we should go with option 1 of create a website
```

> I think we should go with option 1 of create a website

Great Idea, this discussion was really useful. I will go ahead and do it.

### Comments

<!-- This is a comment -->

### Collapsible content

```markdown
<details>
      <summary>Click for for information</summary>
      This is more description...
</details>
```

<details>
      <summary>Click for for information</summary>
      This is more description...
</details>
