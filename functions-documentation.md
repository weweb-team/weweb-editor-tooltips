### If

Return value1 if cond is true, otherwise it returns value2 <br/><br/>
`not(value)`

### Ifempty

Return value1 if not empty, else return value2 <br/><br/>
`ifempty(value1, value2)`

### Not

Return true if value is falsy, else return false <br/><br/>
`not(value)`

### Switch

Compare expr to value1, value2, ... and return result1 if expr === value1, expr if expression === value2 <br/><br/>
`switch(expr, value1, result1, value2, result2, ...)`

### Average

Return the average value of the values inside arr OR the average of value1, value2, ... <br/><br/>
`average(arr)` OR `average(value1, value2, [...])`

### Sum

Return the sum of the values inside arr OR the sum of value1, value2, ...<br/><br/>
`sum(arr) OR sum(value1, value2, [...])`

### Round

Return the sum of the values inside arr OR the sum of value1, value2, ...<br/><br/>
`round(value, precision)`

### RollupCount

Return the sum of each field of arr<br/><br/>
`rollupCount(arr, field)`

### ToNumber

Convert value to a Number. Stop is use for decimal separator. Comma are not supported <br/><br/>
`toNumber(value)`

### Length

Return the number of items in arr<br/><br/>
`length(arr)`

### Slice

Return a new array containing value of arr starting at start index until end index (if provided) or the end of the array<br/><br/>
`slice(arr, start, [end])`

### Merge

Merge two or more arrays into one array<br/><br/>
`merge(arr1, arr2, [...])`

### Contains

Checks if arr contains value<br/><br/>
`contains(arr, value)`

### Map

Return a new array containing only key from arr objects OR return a new array containing arr objects with only key1, key2, key3<br/><br/>
`map(arr, key) OR map(arr, key1, key2, ...)`

### Reverse

Return arr in reverse order<br/><br/>
`reverse(arr)`

### Distinct

Remove duplicates from arr<br/><br/>
`distinct(arr)`

### groupBy

`groupBy(arr, field)`

### Sort

Order arr by asc or desc (depending of order value). Use `field` argument to access properties inside complex objects<br/><br/>
`sort(arr) OR sort(arr, order) OR sort(arr, order, field)`

### Add

Return a new array with values added at the end of arr<br/><br/>
`add(arr, value1, [value2, value3, ...])`

### Prepend

Return a new array with values added at the start of arr<br/><br/>
`prepend(arr, value1, [value2, value3, ...])`

### Remove

Return a new array with value removed from arr<br/><br/>
`remove(arr, value)`

### FilterByKey

Return a new array with only object where key is true (or equal to value if provided)<br/><br/>
`filterByKey(arr, key, [value])`

### ToList

Return a new array<br/><br/>
`toList(value1, [value2, value3, ...])`

### Join

Return a string containing all elements from an array using the given separator (comma by default)<br/><br/>
`join(arr, [separator])`

### GetByIndex

Return an element from an array for a given index<br/><br/>
`getByIndex(arr, index)`

### Contains

Checks if text contains value<br/><br/>
`contains(text, value)`

### Concatenate

Concatenate all textes<br/><br/>
`concatenate(text1, text2, [text3, ...])`

### Split

Splits a text into an array of subtexts<br/><br/>
`split(text, separator)`

### Lower

Return text with lowercase<br/><br/>
`lower(text)`

### Capitalize

Return text capitalize<br/><br/>
`capitalize(text)`

### Uppercase

Return text with uppercase<br/><br/>
`uppercase(text)`

### Uppercase

Return the position of the first occurence of substext inside text. Returns -1 if not found<br/><br/>
`indexOf(text, subtext)`

### ToText

Convert anything to a text<br/><br/>
`toText(value)`

### Keys

Return an array of obj properties name<br/><br/>
`keys(obj)`

### Values

Return an array of obj properties value<br/><br/>
`values(obj)`

### GetByKey

Return the value of the key property of obj<br/><br/>
`getByKey(obj, key)`

### SetByKey

Return a new object, with all properties of obj, but property key is replaced by value<br/><br/>
`setByKey(obj, key, value)`

### ToObject

Convert a list of key/value to an object<br/><br/>
`toObject(key1, value1, [key2, value2, ...])`

### Pick

Return an object that contains only the picked properties using keys<br/><br/>
`pick(obj, key1, [key2, ...])`

### Omit

Return an object that not contains the omited properties using keys<br/><br/>
`omit(obj, key1, [key2, ...])`

### Now

Return the current date in ISO 8601 format<br/><br/>
`now()`

### Timestamp

Return a timestamp for the current date<br/><br/>
`timestamp()`

### FileToUrl

Return an url you can use on an image object to preview a file upload field. If file is empty, use placeholder instead<br/><br/>
`fileToUrl(file, [placeholder])`

### ToBool

Return a boolean (true or false) based on the value passed. Examples for falsy values : Empty string, wrong calcul, null, 0<br/><br/>
`toBool(value)`
