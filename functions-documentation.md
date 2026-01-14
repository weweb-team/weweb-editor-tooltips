### if

Return `value1` if `condition` is true, otherwise return `value2`<br/>The condition and the 2 values are mandatory<br/><br/>
`if(condition, value1, value2)`

### ifEmpty

Return `value1` if not empty, otherwise return `value2` <br/><br/>
`ifEmpty(value1, value2)`

### not

Return true if `value` is falsy, otherwise return false <br/><br/>
`not(value)`

### switch

Compare `expression` to `value1`, `value2`, ... and return `result1` if `expression` is exaclty equal to `value1`, `result2` if `expression` is exaclty equal to `value2`, ... If no value match exaclty, and a `defaultValue` is provided, return `defaultValue` else return `undefined` <br/><br/>
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
Use `key` argument to access subkeys properties inside complex objects.<br/><br/>
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

### lowercase

Return `text` in lowercase<br/><br/>
`lowercase(text)`

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

### objectToArray

Returns an array corresponding to the enumerable string-keyed property key-value pairs<br/><br/>
`objectToArray(object)`

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

Returns `true` or `false`. If the value is omitted or is 0, -0, 0n, null, false, NaN, undefined, or the empty string (""), then the object has an initial value of false. All other values, including any object, an empty array ([]), or the string "false", create an object with an initial value of true.<br/><br/>
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

Return the number of characters in `text`<br/>
`text` must be a string. Use `length` for arrays<br/><br/>
`textLength(text)`

### trim

Remove whitespace from both ends of `text`<br/><br/>
`trim(text)`

### trimStart

Remove whitespace from the beginning of `text`<br/><br/>
`trimStart(text)`

### trimEnd

Remove whitespace from the end of `text`<br/><br/>
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

### translate

Take a multilang object property and return the text corresponding to the the current lang.
`translate(prop)`

### isEmail

Check if `value` is a valid email format<br/><br/>
`isEmail(value)`

### date

Create a date from components or parse a date string. Returns current date if no arguments provided.<br/><br/>
`date()` OR `date(dateString)` OR `date(year, month, day, [hour], [minute], [second], [ms])`

### dateRealtime

Return the current date and time, updating in realtime every second.<br/><br/>
`dateRealtime()`

### toDateISO

Convert a date to ISO 8601 format string (YYYY-MM-DDTHH:mm:ss.sssZ).<br/><br/>
`toDateISO(date)`

### formatDate

Format a date according to a pattern.<br/>Common tokens: `YYYY` (year), `MM` (month), `DD` (day), `HH` (hour 24h), `hh` (hour 12h), `mm` (minute), `ss` (second), `A` (AM/PM).<br/><br/>
`formatDate(date, [format], [locale])`

### fromTime

Return a relative time string from now (e.g., "5 minutes ago", "in 2 hours").<br/>Set `withoutSuffix` to true to get duration only (e.g., "5 minutes").<br/><br/>
`fromTime(date, [withoutSuffix], [locale])`

### toTime

Return a relative time string to a date (e.g., "5 minutes ago", "in 2 hours").<br/>Set `withoutSuffix` to true to get duration only (e.g., "5 minutes").<br/><br/>
`toTime(date, [withoutSuffix], [locale])`

### compareDate

Compare two dates and return the difference.<br/>Precision: `millisecond`, `second`, `minute`, `hour`, `day`, `week`, `month`, `year`.<br/>Returns integer by default, set `float` to true for decimal.<br/><br/>
`compareDate(date1, date2, [precision], [float])`

### getSecond

Get the second (0-59) from a date.<br/><br/>
`getSecond(date)`

### getMinute

Get the minute (0-59) from a date.<br/><br/>
`getMinute(date)`

### getHour

Get the hour (0-23) from a date.<br/><br/>
`getHour(date)`

### getDay

Get the day of the month (1-31) from a date.<br/><br/>
`getDay(date)`

### getDayOfWeek

Get the day of the week (0-6, where 0 is Sunday) from a date.<br/><br/>
`getDayOfWeek(date)`

### getMonth

Get the month (1-12) from a date.<br/><br/>
`getMonth(date)`

### getYear

Get the full year from a date.<br/><br/>
`getYear(date)`

### getDayOfYear

Get the day of the year (1-366) from a date.<br/><br/>
`getDayOfYear(date)`

### getWeekOfYear

Get the week number of the year (1-53) from a date.<br/><br/>
`getWeekOfYear(date)`

### addSeconds

Add or subtract seconds from a date. Use negative values to subtract.<br/><br/>
`addSeconds(date, amount)`

### addMinutes

Add or subtract minutes from a date. Use negative values to subtract.<br/><br/>
`addMinutes(date, amount)`

### addHours

Add or subtract hours from a date. Use negative values to subtract.<br/><br/>
`addHours(date, amount)`

### addDays

Add or subtract days from a date. Use negative values to subtract.<br/><br/>
`addDays(date, amount)`

### addMonths

Add or subtract months from a date. Use negative values to subtract.<br/><br/>
`addMonths(date, amount)`

### addYears

Add or subtract years from a date. Use negative values to subtract.<br/><br/>
`addYears(date, amount)`

### setSecond

Set the second (0-59) of a date.<br/><br/>
`setSecond(date, value)`

### setMinute

Set the minute (0-59) of a date.<br/><br/>
`setMinute(date, value)`

### setHour

Set the hour (0-23) of a date.<br/><br/>
`setHour(date, value)`

### setDay

Set the day of the month (1-31) of a date.<br/><br/>
`setDay(date, value)`

### setDayOfWeek

Set the day of the week (0-6, where 0 is Sunday) of a date.<br/><br/>
`setDayOfWeek(date, value)`

### setMonth

Set the month (1-12) of a date.<br/><br/>
`setMonth(date, value)`

### setYear

Set the full year of a date.<br/><br/>
`setYear(date, value)`

### toTimestamp

Convert a date to Unix timestamp (milliseconds since January 1, 1970).<br/><br/>
`toTimestamp(date)`

### getBrowserTimezone

Get the browser's current timezone (e.g., "America/New_York", "Europe/Paris").<br/><br/>
`getBrowserTimezone()`

### convertDateTimezone

Convert a date to a different timezone.<br/>Set `preserve` to true to keep the same local time in the new timezone.<br/><br/>
`convertDateTimezone(date, timezone, [preserve])`

### formatDateTimezone

Format a date in a specific timezone.<br/><br/>
`formatDateTimezone(date, format, timezone, [locale])`
