# Be-A-Pro-ReadMe
In this repoistory, we will learn how to write and/or format different things as required to increase the readability of the file.

# Heading 1
This is the largest heading. To make text as heading, add '#' infront of it. In this file to create 'Heading 1', I have used '# Heading 1'

## Heading 2
This is the second largest heading. To create 'Heading 2', I have used '## Heading 1'. Similarly, by adding additional '#'s, size of the heading can be reduced as shown below.
### This is heading 3
###### This is the smallest possible heading

# Formating the text
## Quoting the text
## Quoting the code

## Line breaks:
In most of the text editors, inserting/pressing an enter will result in a line break. However, that is not the case here as shown in the below example.
```
After this start a new line.
This is a new line.
```
After this start a new line.
This is a new line.

As expected, both the sentances are in the same line instead of in different lines. <br/> Now the question is, how to insert line breaks? 
In this section, I will walk you through multiple ways to include the line breaks. Plese keep in mind that some of the options are not good to practice <br/>

- By using `<br/>`:
```
After this start a new line.<br/>This is a new line.
```
After this start a new line.<br/>This is a new line.

- By inserting double space:
```
After this start a new line.  (<--two spaces inserted here)This is a new line.
```
After this start a new line.  
This is a new line. <br/><br/>
This is not a good option because some of the editors may strip the extra spaces.
- By using backslash `\` at the end:
```
After this start a new line.\
This is a new line.
```
After this start a new line.\
This is a new line. <br/>
This is not actually defined in the specification. Hence, some of the parsers may ignore it.

- By using `&nbsp`:
```
After this start a new line.&nbspThis is a new line.
```
After this start a new line.&nbspThis is a new line.
## Styling the text
To stress the imporatance of a sentence or a word, we generally format it as either bold or underline or italic.  
To bold the text, either use `__Text to bold goes here__ , where __ is double underscore` or `**Text to bold goes here** `  
Examples: __Bold this text__, **Bold this text too**  

To change the font to italic, either use `_Text to italicize goes here_` or `*Text to italicize goes here*`  
Examples: *Italicize the text*, _Italicize the text_  

To strikethrough the text, use `~~Text to strikesthrough goes here~~`.  
Examples: ~~This was wrong~~
