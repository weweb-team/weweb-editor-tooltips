---start if---

### If

Return value1 if cond is true, otherwise it returns value2 <br/><br/>
`not(value)`

---end if---

---start ifempty---

### Ifempty

Return value1 if not empty, else return value2 <br/><br/>
`ifempty(value1, value2)`

---end ifempty---

---start not---

### Not

Return true if value is falsy, else return false <br/><br/>
`not(value)`

---end not---

---start switch---

### Switch

Compare expr to value1, value2, ... and return result1 if expr === value1, expr if expression === value2 <br/><br/>
`switch(expr, value1, result1, value2, result2, ...)`

---end switch---

---start average---

### Average

Return the average value of the values inside arr OR the average of value1, value2, ... <br/><br/>
`average(arr)` OR `average(value1, value2, [...])`

---end average---

---start sum---

### Sum

Return the sum of the values inside arr OR the sum of value1, value2, ...<br/><br/>
`sum(arr) OR sum(value1, value2, [...])`

---end sum---

---start round---

### Round

Return the sum of the values inside arr OR the sum of value1, value2, ...<br/><br/>
`round(value, precision)`
---end round---

---start rollupCount---

### RollupCount

Return the sum of each field of arr<br/><br/>
`rollupCount(arr, field)`

---end rollupCount---

---start toNumber---

### ToNumber

Convert value to a Number. Stop is use for decimal separator. Comma are not supported <br/><br/>
`toNumber(value)`

---end toNumber---

---start length---

### Length

Return the number of items in arr<br/><br/>
`length(arr)`

---end length---

---start slice---

### Slice

Return a new array containing value of arr starting at start index until end index (if provided) or the end of the array<br/><br/>
`slice(arr, start, [end])`

---end slice---

---start merge---

### Merge

Merge two or more arrays into one array<br/><br/>
`merge(arr1, arr2, [...])`

---end merge---

---start contains---

### Contains

Checks if arr contains value<br/><br/>
`contains(arr, value)`

---end contains---

---start map---

### Map

Return a new array containing only key from arr objects OR return a new array containing arr objects with only key1, key2, key3<br/><br/>
`map(arr, key) OR map(arr, key1, key2, ...)`

---end map---

---start reverse---

### Reverse

Return arr in reverse order<br/><br/>
`reverse(arr)`

---end reverse---

---start distinct---

### Distinct

Remove duplicates from arr<br/><br/>
`distinct(arr)`

---end distinct---

---start groupBy---

### groupBy

---end groupBy---
`groupBy(arr, field)`
---start sort---

### Sort

Order arr by asc or desc (depending of order value). Use `field` argument to access properties inside complex objects<br/><br/>
`sort(arr) OR sort(arr, order) OR sort(arr, order, field)`

---end sort---

---start add---

### Add

Return a new array with values added at the end of arr<br/><br/>
`add(arr, value1, [value2, value3, ...])`

---end add---

---start prepend---

### Prepend

Return a new array with values added at the start of arr<br/><br/>
`prepend(arr, value1, [value2, value3, ...])`

---end prepend---

---start remove---

### Remove

Return a new array with value removed from arr<br/><br/>
`remove(arr, value)`

---end remove---

---start filterByKey---

### FilterByKey

Return a new array with only object where key is true (or equal to value if provided)<br/><br/>
`filterByKey(arr, key, [value])`

---end filterByKey---

---start toList---

### ToList

Return a new array<br/><br/>
`toList(value1, [value2, value3, ...])`

---end toList---

---start join---

### Join

Return a string containing all elements from an array using the given separator (comma by default)<br/><br/>
`join(arr, [separator])`

---end join---

---start getByIndex---

### GetByIndex

Return an element from an array for a given index<br/><br/>
`getByIndex(arr, index)`

---end getByIndex---

---start contains---

### Contains

Checks if text contains value<br/><br/>
`contains(text, value)`

---end contains---

---start concatenate---

### Concatenate

Concatenate all textes<br/><br/>
`concatenate(text1, text2, [text3, ...])`

---end concatenate---

---start split---

### Split

Splits a text into an array of subtexts<br/><br/>
`split(text, separator)`

---end split---

---start lower---

### Lower

Return text with lowercase<br/><br/>
`lower(text)`

---end lower---

---start capitalize---

### Capitalize

Return text capitalize<br/><br/>
`capitalize(text)`

---end capitalize---

---start uppercase---

### Uppercase

Return text with uppercase<br/><br/>
`uppercase(text)`

---end uppercase---

---start indexOf---

### Uppercase

Return the position of the first occurence of substext inside text. Returns -1 if not found<br/><br/>
`indexOf(text, subtext)`

---end indexOf---

---start toText---

### ToText

Convert anything to a text<br/><br/>
`toText(value)`

---end toText---

---start keys---

### Keys

Return an array of obj properties name<br/><br/>
`keys(obj)`

---end keys---

---start values---

### Values

Return an array of obj properties value<br/><br/>
`values(obj)`

---end values---

---start getByKey---

### GetByKey

Return the value of the key property of obj<br/><br/>
`getByKey(obj, key)`

---end getByKey---

---start setByKey---

### SetByKey

Return a new object, with all properties of obj, but property key is replaced by value<br/><br/>
`setByKey(obj, key, value)`

---end setByKey---

---start toObject---

### ToObject

Convert a list of key/value to an object<br/><br/>
`toObject(key1, value1, [key2, value2, ...])`

---end toObject---

---start pick---

### Pick

Return an object that contains only the picked properties using keys<br/><br/>
`pick(obj, key1, [key2, ...])`

---end pick---

---start omit---

### Omit

Return an object that not contains the omited properties using keys<br/><br/>
`omit(obj, key1, [key2, ...])`

---end omit---

---start now---

### Now

Return the current date in ISO 8601 format<br/><br/>
`now()`

---end now---

---start timestamp---

### Timestamp

Return a timestamp for the current date<br/><br/>
`timestamp()`

---end timestamp---

---start fileToUrl---

### FileToUrl

Return an url you can use on an image object to preview a file upload field. If file is empty, use placeholder instead<br/><br/>
`fileToUrl(file, [placeholder])`

---end fileToUrl---

---start toBool---

### ToBool

Return a boolean (true or false) based on the value passed. Examples for falsy values : Empty string, wrong calcul, null, 0<br/><br/>
`toBool(value)`

---end toBool---
