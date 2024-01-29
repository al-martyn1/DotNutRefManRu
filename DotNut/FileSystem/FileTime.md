## DotNut.FileSystem.FileTime class


```lua
class DotNut.FileSystem.FileTime
{
    // Functions

    function _add( v   // DotNut.FileSystem.FileTime
                 )
    // returns: DotNut.FileSystem.FileTime

    function _sub( v   // DotNut.FileSystem.FileTime
                 )
    // returns: DotNut.FileSystem.FileTime

    function _unm( v   // DotNut.FileSystem.FileTime
                 )
    // returns: DotNut.FileSystem.FileTime

    function _mul( v   // DotNut.FileSystem.FileTime
                 )
    // returns: DotNut.FileSystem.FileTime

    function _div( v   // DotNut.FileSystem.FileTime
                 )
    // returns: DotNut.FileSystem.FileTime

    function _modulo( v   // DotNut.FileSystem.FileTime
                    )
    // returns: DotNut.FileSystem.FileTime

    function _cmp( v   // DotNut.FileSystem.FileTime
                 )
    // returns: integer

    function tostring()
    // returns: string

    function _tostring()
    // returns: string

    function tointeger()
    // returns: integer

    function tointeger64()
    // returns: DotNut.Integer64

    function tofloat()
    // returns: float

    function format( fmtStr   // string
                   )
    // returns: string

    function isset()
    // returns: bool


} // class DotNut.FileSystem.FileTime
```



### Methods


**_add** - Support for the 'plus' ('+') operator.


**_sub** - Support for the 'minus' ('-') operator.


**_unm** - Support for the 'unary minus' ('-') operator.


**_mul** - Support for the 'multiply' ('*') operator.


**_div** - Support for the 'divide' ('/') operator.


**_modulo** - Support for the 'modulo' ('%') operator.


**_cmp** - Support for the compare (<, >, <=, >=, ==, !=) operators.


**tostring** - Convert the value to string and returns it. Exposed for compatibility with built-in types. The toString() function has also been implemented to comply with camelCase naming convetions.


**_tostring** - Support for the 'tostring' ('tostring') conversion method.


**tointeger** - Convert the value to integer and returns it. Exposed for compatibility with built-in types. The toInteger() function has also been implemented to comply with camelCase naming convetions.


**tointeger64** - Convert the value to DotNut.Integer64 and returns it. The toInteger64() function has also been implemented to comply with camelCase naming convetions.


**tofloat** - Convert the value to float and returns it. Exposed for compatibility with built-in types. The toFloat() function has also been implemented to comply with camelCase naming convetions.


[DotNut.FileSystem.FileTime.format](../../DotNut/FileSystem/FileTime/format.md) - ![__BRIEF]


[DotNut.FileSystem.FileTime.isset](../../DotNut/FileSystem/FileTime/isset.md) - ![__BRIEF]


