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


[DotNut.BinaryData.len](../DotNut/BinaryData/len.md) - ![__BRIEF]


[DotNut.BinaryData.pop](../DotNut/BinaryData/pop.md) - ![__BRIEF]


[DotNut.BinaryData.top](../DotNut/BinaryData/top.md) - ![__BRIEF]


[DotNut.BinaryData.slice](../DotNut/BinaryData/slice.md) - ![__BRIEF]


[DotNut.BinaryData.push](../DotNut/BinaryData/push.md) - ![__BRIEF]


[DotNut.BinaryData.append](../DotNut/BinaryData/append.md) - ![__BRIEF]


[DotNut.BinaryData.extend](../DotNut/BinaryData/extend.md) - ![__BRIEF]


[DotNut.BinaryData.insert](../DotNut/BinaryData/insert.md) - ![__BRIEF]


[DotNut.BinaryData.remove](../DotNut/BinaryData/remove.md) - ![__BRIEF]


[DotNut.BinaryData.resize](../DotNut/BinaryData/resize.md) - ![__BRIEF]


[DotNut.BinaryData.reverse](../DotNut/BinaryData/reverse.md) - ![__BRIEF]


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


