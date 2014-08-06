# Working with strings

## startsWith

## endsWith
Test if a string ends with a string pattern.

    String.prototype.endsWith = function(suffix) {
        return this.indexOf(suffix, this.length - suffix.length) !== -1;
    };
