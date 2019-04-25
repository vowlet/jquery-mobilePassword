jquery.mobilePassword.js
========================

####Description
This is a jQuery plugin that make your password input field like mobile client interaction.
We can see the last letter.


- require jQuery1.4+
- support IE6+

#### How to use
```
$(document).ready(function() {
  $("input[type=password]").mobilePassword();
});
```
#####The following are the possible options:
```
$(document).ready(function() {
  $("input[type=password]").mobilePassword{
    checkInterval: 200, //set timeout to check whether all the characters are the same
    transDelay: 500,    //delay to transform last letter
    character: '%u25CF' //instead of the character
  };
});
```
**Tip:** Unicode for the symbol that will be displayed,You can find a good overview here:
http://www.fileformat.info/format/w3c/entitytest.htm?sort=Unicode+Character

#####Licensed under the MIT and GPL licenses.


  [1]: http://marvelousowl.github.io/jquery-mobilePassword/example.jpg
