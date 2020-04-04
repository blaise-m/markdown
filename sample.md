<!--
Headings: 
 - Use the pound sign for headings
 - One pound sign represents the highest heading level
 - Increment the pound signs to go to the lower heading level
-->

Add headings using the # signs as below:
# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6

<!-- Horizontal rule: Use tripple hyphens or underscores -->
___
<!--
Emphasis:
 - Italics use a single asterisk or an underscore.
 - Put at the beginning and at the end of the phrase to italicise
 - More like the html open and close tags
-->

Format a phrase in italics using the _ or * as below:

*My first italicised phrase*

_My second italicised phrase_

<!-- Strong text: Use double asterisks or double underscores -->

Format text as strong text using __ or ** as below:

**This is the first strong text**

__This is the second strong text__

<!-- Strike through: Use double tildes -->

~~This text is strike through~~

<!-- Horizontal rule -->
___

<!-- Blockquote: Use a greater than sign -->

> This is a block quote
> 
>   by Blaise Mubangizi
>
> Remember to review how to add tab spaces before a sentence!

<!-- Links: Use square brackets for text & parentheses for link -->
For further information, visit 
[FALX Technologies](http://falxtechnologies.com) or go to 
[www.falxtechnologies.com](www.falxtechnologies.com "Falx Technologies")

___
<!-- Unordered Lists: Use a single asterisk -->
This is a list of the pending tasks:

* Writing README.md files
* Learning java
  * Data structures
  * Control flow
  * Spring Boot
* Completing my Data Science courses

<!-- Ordered Lists: Use 1. -->
I intend to use the following tools:

1. Pycharm
1. IntelliJ
1. Sublime Text
1. Git Bash

___
<!-- Inline Codeblock: Use backticks-->

`<p>This is an html paragraph tag!</p>`

`<img>Below is the FALX Tech logo!</img>`

<!-- Images are same as links but with an exclamation mark -->
![FALX Tech logo](/favicon.ico)
FALX Technologies

___
<!-- Github Markdown -->

<!-- 
Code blocks: 
 - Use tripple backticks
 - You can specify the language, etc after the opening backticks
-->

First, install the dependencies
```bash
npm install
npm start
```

Then, implement the add function
```javascript
const add = (num1, num2) => {
  return num1*num2
}
```

<!-- Tables: Use pipes and hyphens -->
| Name             | Email                     |
| ---------------- | ------------------------- |
| Blaise Mubangizi | mubangiziblaise@gmail.com |
| Joackim Ainamani | joackimainamani@gmail.com |

<!-- Task lists: [x] for complete, [ ] for pending in a ul -->

Taks List
* [x] Task 1
* [x] Taks 2
* [ ] Task 3

