### If

Return `value1` if `condition` is true, otherwise return `value2`<br/><br/>
`if(condition, value1, value2)`

### Ifempty

Return `value1` if not empty, otherwise return `value2` <br/><br/>
`ifempty(value1, value2)`

### Not

Return true if `value` is falsy, otherwise return false <br/><br/>
`not(value)`

### Switch

Compare `expression` to `value1`, `value2`, ... and return `result1` if `expression` is equal to `value1`, `result2` if `expression` is equal to `value2`, ... <br/><br/>
`switch(expression, value1, result1, value2, result2, ...)`

### Average

Return the average value of the values inside `array` OR the average of `value1`, `value2`, ... <br/><br/>
`average(array)` OR `average(value1, value2, [...])`

### Sum

Return the sum of the values inside `array` OR the sum of `value1`, `value2`, ...<br/><br/>
`sum(array) OR sum(value1, value2, [...])`

### Round

Round `value` to a precision of `precision`<br/>
Default value of `precision` is 0<br/><br/>
`round(value, precision)`

### RollupSum

Return the sum of each `key` values of `array`<br/><br/>
`rollupSum(array, key)`

### ToNumber

Convert `value` to a number if possible<br/><br/>
`toNumber(value)`

### Length

Return the number of items in `array`<br/><br/>
`length(array)`

### Slice

Trucate `array` from `startIndex` to the end or to `endIndex` if provided<br/><br/>
`slice(array, startIndex, [endIndex])`

### Merge

Merge two or more arrays into one<br/><br/>
`merge(array1, array2, [...])`

### Contains

Checks if `array` contains `value`<br/><br/>
`contains(array, value)`

### Map

Return a new array containing only `key` from `array` objects OR return a new array containing `array` objects with only `key1`, `key2`, ...<br/><br/>
`map(array, key) OR map(array, key1, key2, ...)`

### Reverse

Return `array` in reverse order<br/><br/>
`reverse(array)`

### Distinct

Remove duplicates from `array`<br/><br/>
`distinct(array)`

### groupBy

Return a new object that group `array` objects by `key` value<br/><br/>
`groupBy(array, key)`

### Sort

Order `array` by asc or desc (depending of `order` value).<br/>
Use `key` argument to access properties inside complex objects<br/><br/>
`sort(array) OR sort(array, order) OR sort(array, order, key)`

### Add

Return a new array with values added at the end of `array`<br/><br/>
`add(array, value1, [value2, value3, ...])`

### Prepend

Return a new array with values added at the start of `array`<br/><br/>
`prepend(array, value1, [value2, value3, ...])`

### Remove

Remove `value` from `array`<br/><br/>
`remove(array, value)`

### RemoveByKey

Remove objects in wich `key` is equal to `value` from `array`<br/><br/>
`removeByKey(array, key, value)`

### RemoveByIndex

Remove value at position `index` from `array`<br/><br/>
`removeByIndex(array, index)`

### FilterByKey

Return a new array with only object where `key` is true (or equal to `value` if provided)<br/><br/>
`filterByKey(array, key, [value])`

### CreateArray

Create a new array<br/><br/>
`createArray(value1, [value2, value3, ...])`

### Join

Concatenate all texts in `array` to a new text, separated by `separator`<br/>
Default value for `separator` is , (comma)<br/><br/>
`join(array, [separator])`

### GetByIndex

Return the item at position `index` in `array`<br/><br/>
`getByIndex(array, index)`

### Contains

Checks if `array` contains `value`<br/><br/>
`contains(array, value)`

### Concatenate

Concatenate all texts<br/><br/>
`concatenate(text1, text2, [text3, ...])`

### Split

Split `text` by `separator` into an array of subtexts<br/><br/>
`split(text, separator)`

### Lower

Return `text` in lowercase<br/><br/>
`lower(text)`

### Capitalize

Return `text` capitalized<br/><br/>
`capitalize(text)`

### Uppercase

Return `text` in uppercase<br/><br/>
`uppercase(text)`

### IndexOf

Return the position of the first occurence of `substext` inside `text`<br/>
Return -1 if not found<br/><br/>
`indexOf(text, subtext)`

### ToText

Convert anything to a text<br/><br/>
`toText(value)`

### Keys

Return an array of all keys present in `object`<br/><br/>
`keys(object)`

### Values

Return an array of all values present in `object`<br/><br/>
`values(object)`

### GetKeyValue

Return the value of the `key` in `object`<br/><br/>
`getKeyValue(object, key)`

### SetKeyValue

Return `object` with `key` set to `value`<br/><br/>
`setKeyValue(object, key, value)`

### CreateObject

Convert a list of key/value to an object<br/><br/>
`createObject(key1, value1, [key2, value2, ...])`

### Pick

Return an object that contains only `key1`, `key2`, ... from `object`<br/><br/>
`pick(object, key1, [key2, ...])`

### Omit

Return an object that contains all keys from `object` except `key1`, `key2`, ...<br/><br/>
`omit(object, key1, [key2, ...])`

### Now

Return the current date in ISO 8601 format<br/><br/>
`now()`

### Timestamp

Return a timestamp for the current date<br/><br/>
`timestamp()`

### FileToUrl

Return an url you can use on an image object to preview a file. If `file` is empty, use `placeholder` instead<br/><br/>
`fileToUrl(file, [placeholder])`

### ToBool

Return a boolean (true or false) based on `value`<br/><br/>
`toBool(value)`

### Lookup

Return the first object in `array` in wich `key` is equal to `value`<br/>
Default value for `key` is 'id'<br/><br/>
`lookup(value, array, [key])`

### LookupArray

Return all objects in `array` in wich `key` value is present in `arrayValues`<br/>
Default value for `key` is 'id'<br/><br/>
`lookupArray(arrayValues, array, [key])`

### Rollup

Return all values of `key` for objects in `array`<br/>
Default value for `distinct` is false<br/><br/>
`rollup(array, key, [distinct])`

### FindIndex

Return the index of the first value equal to `value` in `array`<br/>
Return -1 if not found<br/><br/>
`findIndex(array, value)`

### FindIndexByKey

Return the index of the first object in wich `key` value is equal to `value` in `array`<br/>
Return -1 if not found<br/><br/>
`findIndexByKey(array, key, value)`

### TextLength

Return the number of characters in `text`<br/><br/>
`textLength(text)`
