<div align="center">

## addBr


</div>

### Description

This code takes input from a textarea and replaces carriage returns with the HTML line break BR...
 
### More Info
 
This code accepts a text string.

You need to take a string variable Ex. myString and set it equal to addBr( myString ). Ex. myString = addBr( myString ) and ta da well formatted HTML text!

This code returns the initial string with the chr(10) relpaced by <BR>. It is really handy to keep the formatting the user enters.

Switches chr(10) with <BR> for HTML formatting.


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Robert Somers](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/robert-somers.md)
**Level**          |Beginner
**User Rating**    |3.5 (28 globes from 8 users)
**Compatibility**  |ASP \(Active Server Pages\)
**Category**       |[Strings](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/strings__4-26.md)
**World**          |[ASP / VbScript](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/asp-vbscript.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/robert-somers-addbr__4-6107/archive/master.zip)

### API Declarations

Please rank my code! And vote for me!


### Source Code

```
<%
FUNCTION addBr( myString )
 addBr = Replace(myString, CHR(10), "<BR>")
END FUNCTION
%>
```

