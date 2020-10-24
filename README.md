# TEXT USER INTERFACE EXAMPLES

### Colors in Java

ANSI CODE|COLOR|CODE EXAMPLE
|---|---|---|
`\033[30m`|Black|**System.out.println("\033[30m [BLACK]");**
`\033[31m`|Red|**System.out.println("\033[31m [RED]");**
`\033[32m`|Green|**System.out.println("\033[32m [GREEN]");**
`\033[33m`|Yellow|**System.out.println("\033[33m [YELLOW]");**
`\033[34m`|Blue|**System.out.println("\033[34m [BLUE]");**
`\033[35m`|Purple|**System.out.println("\033[35m [PURPLE]");**
`\033[36m`|Light Blue|**System.out.println("\033[36m [LIGHT BLUE]");**
`\033[37m`|White|**System.out.println("\033[37m [WHITE]");**

<img src="Images/ANSI-test.png">

### DIFFS Colors

* Used in Markdown, put the symbol before write something

```diff
- Red text
+ Green Text
! text in orange
# Text in gray
@@ Text in Purple and Bold @@
```

### Colors in Javascript using Node.js

* When using Node.js, you can install the Module **cli-colors**
* Inside the Node.js project, write on Terminal:

```shell
> npm install cli-color
```
* Call the Module on your .js file:

```javascript
var colors = require("cli-color");
```
* Examples:

```javascript
var color = require('cli-color');

console.log(color.green("[GREEN]"));
console.log(color.red("[RED]"))
console.log(color.blue("[BLUE]"));
console.log(color.yellow("[YELLOW]"));
console.log(color.cyan("[CYAN]"));
console.log(color.magenta("[MAGENTA]"));
console.log(color.white("[WHITE]"));
```

