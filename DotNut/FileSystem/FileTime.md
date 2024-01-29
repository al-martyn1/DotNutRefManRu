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


**_add** - Support for the 'plus' ('+') operator. See [squirrel manual](http://squirrel-lang.org/squirreldoc/reference/language/metamethods.html#add) for details.


**_sub** - Support for the 'minus' ('-') operator. See [squirrel manual](http://squirrel-lang.org/squirreldoc/reference/language/metamethods.html#sub) for details.


**_unm** - Support for the 'unary minus' ('-') operator. See [squirrel manual](http://squirrel-lang.org/squirreldoc/reference/language/metamethods.html#unm) for details.


**_mul** - Support for the 'multiply' ('*') operator. See [squirrel manual](http://squirrel-lang.org/squirreldoc/reference/language/metamethods.html#mul) for details.


**_div** - Support for the 'divide' ('/') operator. See [squirrel manual](http://squirrel-lang.org/squirreldoc/reference/language/metamethods.html#div) for details.


**_modulo** - Support for the 'modulo' ('%') operator. See [squirrel manual](http://squirrel-lang.org/squirreldoc/reference/language/metamethods.html#modulo) for details.


**_cmp** - Support for the compare (<, >, <=, >=, ==, !=) operators. See [squirrel manual](http://squirrel-lang.org/squirreldoc/reference/language/metamethods.html#cmp) for details.


**tostring** - Convert the value to string and returns it, see [squirrel manual](http://squirrel-lang.org/squirreldoc/reference/language/builtin_functions.html#string) for details. Exposed for compatibility with built-in types. The toString() function has also been implemented to comply with camelCase naming convetions.


**_tostring** - Support for the 'tostring' ('tostring') conversion method. See [squirrel manual](http://squirrel-lang.org/squirreldoc/reference/language/metamethods.html#tostring) for details.


**tointeger** - Convert the value to integer and returns it, see [squirrel manual](http://squirrel-lang.org/squirreldoc/reference/language/builtin_functions.html#integer) for details. Exposed for compatibility with built-in types. The toInteger() function has also been implemented to comply with camelCase naming convetions.


**tointeger64** - Convert the value to DotNut.Integer64 and returns it. The toInteger64() function has also been implemented to comply with camelCase naming convetions.


**tofloat** - Convert the value to float and returns it, see [squirrel manual](http://squirrel-lang.org/squirreldoc/reference/language/builtin_functions.html#float) for details. Exposed for compatibility with built-in types. The toFloat() function has also been implemented to comply with camelCase naming convetions.


[DotNut.FileSystem.FileTime.format](../../DotNut/FileSystem/FileTime/format.md) - ![__BRIEF]


[DotNut.FileSystem.FileTime.isset](../../DotNut/FileSystem/FileTime/isset.md) - ![__BRIEF]


