## DotNut.BinaryData class


```lua
class DotNut.BinaryData
{
    // Functions

    function len()
    // returns: integer

    function pop()
    // returns: integer

    function top()
    // returns: integer

    function slice( start   // integer
                  , end     // integer
                  )
    // returns: DotNut.BinaryData

    function push( b   // integer
                 )

    function append( b   // integer
                   )

    function extend( data   // DotNut.BinaryData
                   )

    function insert( idx   // integer
                   , b     // integer
                   )

    function remove( idx   // integer
                   )

    function resize( newSize   // integer
                   , b         // integer
                   )

    function reverse()

    function _set( idx   // integer
                 , b     // integer
                 )

    function _get( idx   // integer
                 )
    // returns: integer

    function setByte( idx   // integer
                    , b     // integer
                    )

    function getByte( idx   // integer
                    )
    // returns: integer

    function getHostEndianness()
    // returns: DotNut.Endianness

    function convertEndianness( srcEndianness   // DotNut.Endianness
                              )

    function tointeger()
    // returns: integer

    function tointeger64()
    // returns: DotNut.toInteger64

    function toArray()
    // returns: array of integer

    function tostring()
    // returns: string


} // class DotNut.BinaryData
```



### Methods


**len** - Returns the string/array length. String/Array compatible method. See [squirrel manual](http://squirrel-lang.org/squirreldoc/reference/language/builtin_functions.html#array.len) for details.


**pop** - Removes a value from the back of the container. Array compatible method. See [squirrel manual](http://squirrel-lang.org/squirreldoc/reference/language/builtin_functions.html#array.pop) for details.


**top** - Returns the value of the container with the higher index. Array compatible method. See [squirrel manual](http://squirrel-lang.org/squirreldoc/reference/language/builtin_functions.html#array.top) for details.


**slice** - Returns a section of the container as new container. String/Array compatible method. See [squirrel manual](http://squirrel-lang.org/squirreldoc/reference/language/builtin_functions.html#array.slice) for details.


**push** - Appends the value at the end of the array. Array compatible method. See [squirrel manual](http://squirrel-lang.org/squirreldoc/reference/language/builtin_functions.html#array.push) for details.


**append** - Appends the value at the end of the container. Array compatible method. See [squirrel manual](http://squirrel-lang.org/squirreldoc/reference/language/builtin_functions.html#array.append) for details.


**extend** - Extends the container by appending all the items in the given container. Array compatible method. See [squirrel manual](http://squirrel-lang.org/squirreldoc/reference/language/builtin_functions.html#array.extend) for details.


**insert** - Inserts the value at the position ‘idx’ in the container. Array compatible method. See [squirrel manual](http://squirrel-lang.org/squirreldoc/reference/language/builtin_functions.html#array.insert) for details.


**remove** - Removes the value at the position ‘idx’ in the container. Array compatible method. See [squirrel manual](http://squirrel-lang.org/squirreldoc/reference/language/builtin_functions.html#array.remove) for details.


**resize** - Resizes the container. Value of the parameter ‘fill’ will be used to fill the new container’s slots when the size specified is bigger than the previous size. Array compatible method. See [squirrel manual](http://squirrel-lang.org/squirreldoc/reference/language/builtin_functions.html#array.resize) for details.


**reverse** - Reverse the elements of the container in place. Array compatible method. See [squirrel manual](http://squirrel-lang.org/squirreldoc/reference/language/builtin_functions.html#array.reverse) for details.


**_set** - Support for the index ('[]') operator. See [squirrel manual](http://squirrel-lang.org/squirreldoc/reference/language/metamethods.html#set) for details.


**_get** - Support for the index ('[]') operator. See [squirrel manual](http://squirrel-lang.org/squirreldoc/reference/language/metamethods.html#get) for details.


[DotNut.BinaryData.setByte](../DotNut/BinaryData/setByte.md) - ![__BRIEF]


[DotNut.BinaryData.getByte](../DotNut/BinaryData/getByte.md) - ![__BRIEF]


[DotNut.BinaryData.getHostEndianness](../DotNut/BinaryData/getHostEndianness.md) - ![__BRIEF]


[DotNut.BinaryData.convertEndianness](../DotNut/BinaryData/convertEndianness.md) - ![__BRIEF]


**tointeger** - Convert the value to integer and returns it, see [squirrel manual](http://squirrel-lang.org/squirreldoc/reference/language/builtin_functions.html#integer) for details. Exposed for compatibility with built-in types. The toInteger() function has also been implemented to comply with camelCase naming convetions.


**tointeger64** - Convert the value to DotNut.Integer64 and returns it. The toInteger64() function has also been implemented to comply with camelCase naming convetions.


[DotNut.BinaryData.toArray](../DotNut/BinaryData/toArray.md) - ![__BRIEF]


**tostring** - Convert the value to string and returns it, see [squirrel manual](http://squirrel-lang.org/squirreldoc/reference/language/builtin_functions.html#string) for details. Exposed for compatibility with built-in types. The toString() function has also been implemented to comply with camelCase naming convetions.


