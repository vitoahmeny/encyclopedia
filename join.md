# Array.prototype.join()

The JavaScript `join()` method joins all elements in the array into a a string.

## Syntax

```
string = array.join(separator);
```

## Parameter

**separator** - Optional. Specifies a string to separate each element of the array. If not specified, the array elements are separated with a comma.

## Return Value

Return a string after joining all elements of the array.

## Example
The following example creats an array, then join the array using different parameters.

```
var myArray = ["water", "fire", "air", "earth"]

```

**Join myArray with the default separator:**

```
var str = myArray.join();

```
### Value of `str`

```
'water,fire,air,earth'
```

**Join myArray with a comma and a space:**

```
var str = myArray.join(', ') 
```
### Value of `str`

```
'water, fire, air, earth'
```
**Join myArray with an empty string:**

```
str = myArray.join('')

```
If separator is an empty string, all elements are joined without any characters in between them.

### Value of `str`

```
'waterfireairearth'

```

**Join myArray with a plus sign**

```
str = myArray.join(' + ')
```

### Value of `str`

```
"water + fire + air + earth"
```
