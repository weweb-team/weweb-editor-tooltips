### if

Return `value1` if `condition` is true, otherwise return `value2`<br/><br/>
`if(condition, value1, value2)`

### ifEmpty

Return `value1` if not empty, otherwise return `value2` <br/><br/>
`ifempty(value1, value2)`

### not

Return true if `value` is falsy, otherwise return false <br/><br/>
`not(value)`

### switch

Compare `expression` to `value1`, `value2`, ... and return `result1` if `expression` is equal to `value1`, `result2` if `expression` is equal to `value2`, ... If no value match, and a `defaultValue` is provided, return `defaultValue` else return `undefined` <br/><br/>
`switch(expression, value1, result1, value2, result2, ..., [defaultValue])`

### average

Return the average value of the values inside `array` OR the average of `value1`, `value2`, ... <br/><br/>
`average(array)` OR `average(value1, value2, [...])`

### sum

Return the sum of the values inside `array` OR the sum of `value1`, `value2`, ...<br/><br/>
`sum(array) OR sum(value1, value2, [...])`

### round

Round `value` to a precision of `precision`<br/>
Default value of `precision` is 0<br/><br/>
`round(value, precision)`

### rollupSum

Return the sum of each `key` values of `array`<br/><br/>
`rollupSum(array, key)`

### toNumber

Convert `value` to a number if possible<br/><br/>
`toNumber(value)`

### length

Return the number of items in `array`<br/><br/>
`length(array)`

### slice

Trucate `array` from `startIndex` to the end or to `endIndex` if provided<br/><br/>
`slice(array, startIndex, [endIndex])`

### merge

Merge two or more arrays into one<br/><br/>
`merge(array1, array2, [...])`

### contains

Checks if `array` contains `value`<br/><br/>
`contains(array, value)`

### map

Return a new array containing only `key` from `array` objects OR return a new array containing `array` objects with only `key1`, `key2`, ...<br/><br/>
`map(array, key) OR map(array, key1, key2, ...)`

### reverse

Return `array` in reverse order<br/><br/>
`reverse(array)`

### distinct

Remove duplicates from `array`<br/><br/>
`distinct(array)`

### groupBy

Return a new object that group `array` objects by `key` value<br/><br/>
`groupBy(array, key)`

### sort

Order `array` by asc or desc (depending of `order` value).<br/>
Use `key` argument to access properties inside complex objects<br/><br/>
`sort(array) OR sort(array, order) OR sort(array, order, key)`

### add

Return a new array with values added at the end of `array`<br/><br/>
`add(array, value1, [value2, value3, ...])`

### prepend

Return a new array with values added at the start of `array`<br/><br/>
`prepend(array, value1, [value2, value3, ...])`

### remove

Remove `value` from `array`<br/><br/>
`remove(array, value)`

### removeByKey

Remove objects in wich `key` is equal to `value` from `array`<br/><br/>
`removeByKey(array, key, value)`

### removeByIndex

Remove value at position `index` from `array`<br/><br/>
`removeByIndex(array, index)`

### filterByKey

Return a new array with only object where `key` is true (or equal to `value` if provided)<br/><br/>
`filterByKey(array, key, [value])`

### createArray

Create a new array<br/><br/>
`createArray(value1, [value2, value3, ...])`

### compare

Verify if two arrays are equals: they have the same values and the same order.<br/><br/>
`compare(array1, array2)`

### join

Concatenate all texts in `array` to a new text, separated by `separator`<br/>
Default value for `separator` is , (comma)<br/><br/>
`join(array, [separator])`

### getByIndex

Return the item at position `index` in `array`<br/><br/>
`getByIndex(array, index)`

### contains

Checks if `array` contains `value`<br/><br/>
`contains(array, value)`

### concatenate

Concatenate all texts<br/><br/>
`concatenate(text1, text2, [text3, ...])`

### split

Split `text` by `separator` into an array of subtexts<br/><br/>
`split(text, separator)`

### lower

Return `text` in lowercase<br/><br/>
`lower(text)`

### capitalize

Return `text` capitalized<br/><br/>
`capitalize(text)`

### uppercase

Return `text` in uppercase<br/><br/>
`uppercase(text)`

### indexOf

Return the position of the first occurence of `substext` inside `text`<br/>
Return -1 if not found<br/><br/>
`indexOf(text, subtext)`

### toText

Convert anything to a text<br/><br/>
`toText(value)`

### keys

Return an array of all keys present in `object`<br/><br/>
`keys(object)`

### values

Return an array of all values present in `object`<br/><br/>
`values(object)`

### getKeyValue

Return the value of the `key` in `object`<br/><br/>
`getKeyValue(object, key)`

### setKeyValue

Return `object` with `key` set to `value`<br/><br/>
`setKeyValue(object, key, value)`

### createObject

Convert a list of key/value to an object<br/><br/>
`createObject(key1, value1, [key2, value2, ...])`

### pick

Return an object that contains only `key1`, `key2`, ... from `object`<br/><br/>
`pick(object, key1, [key2, ...])`

### omit

Return an object that contains all keys from `object` except `key1`, `key2`, ...<br/><br/>
`omit(object, key1, [key2, ...])`

### now

`now` is deprecated, please use `date` from the Date plugin instead.<br/><br/>
`now()`

### timestamp

`timestamp` is deprecated, please use `toTimestamp` from the Date plugin instead.<br/><br/>
`timestamp()`

### fileToUrl

Return an url you can use on an image object to preview a file. If `file` is empty, use `placeholder` instead<br/><br/>
`fileToUrl(file, [placeholder])`

### toBool

Return a boolean (true or false) based on `value`<br/><br/>
`toBool(value)`

### lookup

Return the first object in `array` in which `key` is equal to `value`<br/>
Default value for `key` is 'id'<br/><br/>
`lookup(value, array, [key])`

### lookupArray

Return all objects in `array` in which `key` value is present in `arrayValues`<br/>
Default value for `key` is 'id'<br/><br/>
`lookupArray(arrayValues, array, [key])`

### rollup

Return all values of `key` for objects in `array`<br/>
Default value for `distinct` is false<br/><br/>
`rollup(array, key, [distinct])`

### findIndex

Return the index of the first value equal to `value` in `array`<br/>
Return -1 if not found<br/><br/>
`findIndex(array, value)`

### findIndexByKey

Return the index of the first object in which `key` value is equal to `value` in `array`<br/>
Return -1 if not found<br/><br/>
`findIndexByKey(array, key, value)`

### textLength

Return the number of characters in `text`<br/><br/>
`textLength(text)`

### trim

Remove whitespace from both ends of text
`trim(text)`

### trimStart

Remove whitespace from the beginning of text
`trimStart(text)`

### trimEnd

Remove whitespace from the end of text
`trimEnd(text)`

### subText

Return a subtext from `text` starting at `startIndex` to the end or to `endIndex` if provided<br/><br/>
`subText(text, startIndex, [endIndex])`

### isLoopFinished

Returns true if the provided `loop` is finished.<br/>
Should moslty be used in pass through conditions to get out of a loop action.<br/><br/>
`isLoopFinished(loop)`

### flat

Returns an array with all sub-array elements concatenated into it.<br/><br/>
`flat(array)`

### elementScrollPosition

Returns an object containing position properties of the element with `id`.<br/>
If `key` is specified, only the value for `key` will be returned.<br/>
Valid values for `key` are : 'visible', 'x', 'y', 'xPercent', 'yPercent', 'width', 'height'<br/><br/>
`elementScrollPosition(id, [key])`
