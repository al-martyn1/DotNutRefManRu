## DotNut.Integer64 класс


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



### Методы


**_add** - Поддержка оператора 'plus' ('+'). См.[squirrel manual](http://squirrel-lang.org/squirreldoc/reference/language/metamethods.html#add) для получения подробностей.


**_sub** - Поддержка оператора 'minus' ('-'). См.[squirrel manual](http://squirrel-lang.org/squirreldoc/reference/language/metamethods.html#sub) для получения подробностей.


**_unm** - Поддержка оператора 'unary minus' ('-'). См.[squirrel manual](http://squirrel-lang.org/squirreldoc/reference/language/metamethods.html#unm) для получения подробностей.


**_mul** - Поддержка оператора 'multiply' ('*'). См.[squirrel manual](http://squirrel-lang.org/squirreldoc/reference/language/metamethods.html#mul) для получения подробностей.


**_div** - Поддержка оператора 'divide' ('/'). См.[squirrel manual](http://squirrel-lang.org/squirreldoc/reference/language/metamethods.html#div) для получения подробностей.


**_modulo** - Поддержка оператора 'modulo' ('%'). См.[squirrel manual](http://squirrel-lang.org/squirreldoc/reference/language/metamethods.html#modulo) для получения подробностей.


**_cmp** - Поддержка операторов сравнения (<, >, <=, >=, ==, !=). См.[squirrel manual](http://squirrel-lang.org/squirreldoc/reference/language/metamethods.html#cmp) для получения подробностей.


[DotNut.Integer64.lo](../DotNut/Integer64/lo.md) - ![__BRIEF]


[DotNut.Integer64.hi](../DotNut/Integer64/hi.md) - ![__BRIEF]


[DotNut.Integer64.setHiLo](../DotNut/Integer64/setHiLo.md) - ![__BRIEF]


[DotNut.Integer64.setLo](../DotNut/Integer64/setLo.md) - ![__BRIEF]


[DotNut.Integer64.setHi](../DotNut/Integer64/setHi.md) - ![__BRIEF]


**tostring** - Преобразует значение в string и возвращает его, см.[squirrel manual](http://squirrel-lang.org/squirreldoc/reference/language/builtin_functions.html#string) для получения подробностей. Реализован для совместимости со встроенными типами. Метод toString() также реализован для соответствия соглашениям об именовании camelCase.


**_tostring** - Поддержка преобразования в строку. См.[squirrel manual](http://squirrel-lang.org/squirreldoc/reference/language/metamethods.html#tostring) для получения подробностей.


**tointeger** - Преобразует значение в integer и возвращает его, см.[squirrel manual](http://squirrel-lang.org/squirreldoc/reference/language/builtin_functions.html#integer) для получения подробностей. Реализован для совместимости со встроенными типами. Метод toInteger() также реализован для соответствия соглашениям об именовании camelCase.


**tofloat** - Преобразует значение во float и возвращает его, см.[squirrel manual](http://squirrel-lang.org/squirreldoc/reference/language/builtin_functions.html#float) для получения подробностей. Реализован для совместимости со встроенными типами. Метод  toFloat() также реализован для соответствия соглашениям об именовании camelCase.


