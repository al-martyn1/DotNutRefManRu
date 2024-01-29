## DotNut.BigDecimal класс


```lua
class DotNut.BigDecimal
{
    // Functions

    constructor( v   // any_number
               )

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



### Методы


[DotNut.BigDecimal.constructor](../DotNut/BigDecimal/constructor.md) - ![__BRIEF]


**_add** - Поддержка оператора 'plus' ('+'). См. [squirrel manual](http://squirrel-lang.org/squirreldoc/reference/language/metamethods.html#add) для получения подробностей.


**_sub** - Поддержка оператора 'minus' ('-'). См. [squirrel manual](http://squirrel-lang.org/squirreldoc/reference/language/metamethods.html#sub) для получения подробностей.


**_unm** - Поддержка оператора 'unary minus' ('-'). См. [squirrel manual](http://squirrel-lang.org/squirreldoc/reference/language/metamethods.html#unm) для получения подробностей.


**_mul** - Поддержка оператора 'multiply' ('*'). См. [squirrel manual](http://squirrel-lang.org/squirreldoc/reference/language/metamethods.html#mul) для получения подробностей.


**_div** - Поддержка оператора 'divide' ('/'). См. [squirrel manual](http://squirrel-lang.org/squirreldoc/reference/language/metamethods.html#div) для получения подробностей.


**_cmp** - Поддержка операторов сравнения (<, >, <=, >=, ==, !=). См. [squirrel manual](http://squirrel-lang.org/squirreldoc/reference/language/metamethods.html#cmp) для получения подробностей.


[DotNut.BigDecimal.divEx](../DotNut/BigDecimal/divEx.md) - ![__BRIEF]


[DotNut.BigDecimal.precision](../DotNut/BigDecimal/precision.md) - ![__BRIEF]


[DotNut.BigDecimal.round](../DotNut/BigDecimal/round.md) - ![__BRIEF]


[DotNut.BigDecimal.isZero](../DotNut/BigDecimal/isZero.md) - ![__BRIEF]


[DotNut.BigDecimal.sgn](../DotNut/BigDecimal/sgn.md) - ![__BRIEF]


[DotNut.BigDecimal.abs](../DotNut/BigDecimal/abs.md) - ![__BRIEF]


[DotNut.BigDecimal.neg](../DotNut/BigDecimal/neg.md) - ![__BRIEF]


[DotNut.BigDecimal.toStringEx](../DotNut/BigDecimal/toStringEx.md) - ![__BRIEF]


**tostring** - Преобразует значение в string и возвращает его, см. [squirrel manual](http://squirrel-lang.org/squirreldoc/reference/language/builtin_functions.html#string) для получения подробностей. Реализован для совместимости со встроенными типами. Метод toString() также реализован для соответствия соглашениям об именовании camelCase.


**_tostring** - Поддержка преобразования в строку. См. [squirrel manual](http://squirrel-lang.org/squirreldoc/reference/language/metamethods.html#tostring) для получения подробностей.


**tointeger** - Преобразует значение в integer и возвращает его, см. [squirrel manual](http://squirrel-lang.org/squirreldoc/reference/language/builtin_functions.html#integer) для получения подробностей. Реализован для совместимости со встроенными типами. Метод toInteger() также реализован для соответствия соглашениям об именовании camelCase.


**tointeger64** - Преобразует значение в DotNut.Integer64 и возвращает его. Метод toInteger64() также реализован для соответствия соглашениям об именовании camelCase.


**tofloat** - Преобразует значение во float и возвращает его, см. [squirrel manual](http://squirrel-lang.org/squirreldoc/reference/language/builtin_functions.html#float) для получения подробностей. Реализован для совместимости со встроенными типами. Метод  toFloat() также реализован для соответствия соглашениям об именовании camelCase.


