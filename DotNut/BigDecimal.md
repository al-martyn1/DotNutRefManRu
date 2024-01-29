## DotNut.BigDecimal class


```lua
class DotNut.BigDecimal
{
    // Functions

    function _add( v   // DotNut.BigDecimal
                 )
    // returns: DotNut.BigDecimal

    function _sub( v   // DotNut.BigDecimal
                 )
    // returns: DotNut.BigDecimal

    function _unm( v   // DotNut.BigDecimal
                 )
    // returns: DotNut.BigDecimal

    function _mul( v   // DotNut.BigDecimal
                 )
    // returns: DotNut.BigDecimal

    function _div( v   // DotNut.BigDecimal
                 )
    // returns: DotNut.BigDecimal

    function _cmp( v   // DotNut.BigDecimal
                 )
    // returns: integer

    function divEx( v           // DotNut.BigDecimal
                  , precision   // integer
                  )
    // returns: DotNut.BigDecimal

    function precision()
    // returns: integer

    function round( precision        // integer
                  , roundingMethod   // DotNut.BigDecimalRoundingMethod
                  )
    // returns: DotNut.BigDecimal

    function isZero()
    // returns: bool

    function sgn()
    // returns: integer

    function abs()
    // returns: DotNut.BigDecimal

    function neg()
    // returns: DotNut.BigDecimal

    function toStringEx( precision   // integer
                       )
    // returns: string

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


} // class DotNut.BigDecimal
```



### Methods


**_add** - Support for the 'plus' ('+') operator.


**_sub** - Support for the 'minus' ('-') operator.


**_unm** - Support for the 'unary minus' ('-') operator.


**_mul** - Support for the 'multiply' ('*') operator.


**_div** - Support for the 'divide' ('/') operator.


**_cmp** - Support for the compare (<, >, <=, >=, ==, !=) operators.


[DotNut.BigDecimal.divEx](../DotNut/BigDecimal/divEx.md) - ![__BRIEF]


[DotNut.BigDecimal.precision](../DotNut/BigDecimal/precision.md) - ![__BRIEF]


[DotNut.BigDecimal.round](../DotNut/BigDecimal/round.md) - ![__BRIEF]


[DotNut.BigDecimal.isZero](../DotNut/BigDecimal/isZero.md) - ![__BRIEF]


[DotNut.BigDecimal.sgn](../DotNut/BigDecimal/sgn.md) - ![__BRIEF]


[DotNut.BigDecimal.abs](../DotNut/BigDecimal/abs.md) - ![__BRIEF]


[DotNut.BigDecimal.neg](../DotNut/BigDecimal/neg.md) - ![__BRIEF]


[DotNut.BigDecimal.toStringEx](../DotNut/BigDecimal/toStringEx.md) - ![__BRIEF]


**tostring** - Convert the value to string and returns it. Exposed for compatibility with built-in types. The toString() function has also been implemented to comply with camelCase naming convetions.


**_tostring** - Support for the 'tostring' ('tostring') conversion method.


**tointeger** - Convert the value to integer and returns it. Exposed for compatibility with built-in types. The toInteger() function has also been implemented to comply with camelCase naming convetions.


**tointeger64** - Convert the value to DotNut.Integer64 and returns it. The toInteger64() function has also been implemented to comply with camelCase naming convetions.


**tofloat** - Convert the value to float and returns it. Exposed for compatibility with built-in types. The toFloat() function has also been implemented to comply with camelCase naming convetions.


