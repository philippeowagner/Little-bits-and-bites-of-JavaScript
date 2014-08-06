# Working with arrays

## Remove an empty string from an array of strings.

    var newArray = oldArray.filter(function(v){return v!==''});

The [MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/filter) has a workaround for IE8 compatibility. You might also use a good old loop if you're not going to use filter anywhere else, there's no problem with looping...

Source: [Stackoverflow](http://stackoverflow.com/questions/14453670/remove-an-empty-string-from-array-of-strings-jquery)
