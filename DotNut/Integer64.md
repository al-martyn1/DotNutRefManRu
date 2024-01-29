## DotNut.Integer64 class


```lua
class DotNut.Integer64
{
    // Functions

    function _add( v   // DotNut.Integer64
                 )
    // returns: DotNut.Integer64

    function _sub( v   // DotNut.Integer64
                 )
    // returns: DotNut.Integer64

    function _unm( v   // DotNut.Integer64
                 )
    // returns: DotNut.Integer64

    function _mul( v   // DotNut.Integer64
                 )
    // returns: DotNut.Integer64

    function _div( v   // DotNut.Integer64
                 )
    // returns: DotNut.Integer64

    function _modulo( v   // DotNut.Integer64
                    )
    // returns: DotNut.Integer64

    function _cmp( v   // DotNut.Integer64
                 )
    // returns: integer

    function lo()
    // returns: integer

    function hi()
    // returns: integer

    function setHiLo( h   // integer
                    , l   // integer
                    )

    function setLo( l   // integer
                  )

    function setHi( h   // integer
                  )

    function tostring()
    // returns: string

    function _tostring()
    // returns: string

    function tointeger()
    // returns: integer

    function tofloat()
    // returns: float


} // class DotNut.Integer64
```



### Methods


**_add** - Support for the 'plus' ('+') operator. See [squirrel manual](http://squirrel-lang.org/squirreldoc/reference/language/metamethods.html#add) for details.


**_sub** - Support for the 'minus' ('-') operator. See [squirrel manual](http://squirrel-lang.org/squirreldoc/reference/language/metamethods.html#sub) for details.


**_unm** - Support for the 'unary minus' ('-') operator. See [squirrel manual](http://squirrel-lang.org/squirreldoc/reference/language/metamethods.html#unm) for details.


**_mul** - Support for the 'multiply' ('*') operator. See [squirrel manual](http://squirrel-lang.org/squirreldoc/reference/language/metamethods.html#mul) for details.


**_div** - Support for the 'divide' ('/') operator. See [squirrel manual](http://squirrel-lang.org/squirreldoc/reference/language/metamethods.html#div) for details.


**_modulo** - Support for the 'modulo' ('%') operator. See [squirrel manual](http://squirrel-lang.org/squirreldoc/reference/language/metamethods.html#modulo) for details.


**_cmp** - Support for the compare (<, >, <=, >=, ==, !=) operators. See [squirrel manual](http://squirrel-lang.org/squirreldoc/reference/language/metamethods.html#cmp) for details.


[DotNut.Integer64.lo](../DotNut/Integer64/lo.md) - ![__BRIEF]


[DotNut.Integer64.hi](../DotNut/Integer64/hi.md) - ![__BRIEF]


[DotNut.Integer64.setHiLo](../DotNut/Integer64/setHiLo.md) - ![__BRIEF]


[DotNut.Integer64.setLo](../DotNut/Integer64/setLo.md) - ![__BRIEF]


[DotNut.Integer64.setHi](../DotNut/Integer64/setHi.md) - ![__BRIEF]


**tostring** - Convert the value to string and returns it, see [squirrel manual](http://squirrel-lang.org/squirreldoc/reference/language/builtin_functions.html#string) for details. Exposed for compatibility with built-in types. The toString() function has also been implemented to comply with camelCase naming convetions.


**_tostring** - Support for the 'tostring' ('tostring') conversion method. See [squirrel manual](http://squirrel-lang.org/squirreldoc/reference/language/metamethods.html#tostring) for details.


**tointeger** - Convert the value to integer and returns it, see [squirrel manual](http://squirrel-lang.org/squirreldoc/reference/language/builtin_functions.html#integer) for details. Exposed for compatibility with built-in types. The toInteger() function has also been implemented to comply with camelCase naming convetions.


**tofloat** - Convert the value to float and returns it, see [squirrel manual](http://squirrel-lang.org/squirreldoc/reference/language/builtin_functions.html#float) for details. Exposed for compatibility with built-in types. The toFloat() function has also been implemented to comply with camelCase naming convetions.


