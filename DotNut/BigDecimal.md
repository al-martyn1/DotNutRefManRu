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


[DotNut.BigDecimal.tostring](../DotNut/BigDecimal/tostring.md) - ![__BRIEF]


**_tostring** - Support for the 'tostring' ('tostring') conversion method.


[DotNut.BigDecimal.tointeger](../DotNut/BigDecimal/tointeger.md) - ![__BRIEF]


[DotNut.BigDecimal.tointeger64](../DotNut/BigDecimal/tointeger64.md) - ![__BRIEF]


[DotNut.BigDecimal.tofloat](../DotNut/BigDecimal/tofloat.md) - ![__BRIEF]


