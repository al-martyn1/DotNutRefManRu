## DotNut.FileSystem.FileTime класс


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



### Методы


**_add** - Поддержка оператора 'plus' ('+'). См. [squirrel manual](http://squirrel-lang.org/squirreldoc/reference/language/metamethods.html#add) для получения подробностей.


**_sub** - Поддержка оператора 'minus' ('-'). См. [squirrel manual](http://squirrel-lang.org/squirreldoc/reference/language/metamethods.html#sub) для получения подробностей.


**_unm** - Поддержка оператора 'unary minus' ('-'). См. [squirrel manual](http://squirrel-lang.org/squirreldoc/reference/language/metamethods.html#unm) для получения подробностей.


**_mul** - Поддержка оператора 'multiply' ('*'). См. [squirrel manual](http://squirrel-lang.org/squirreldoc/reference/language/metamethods.html#mul) для получения подробностей.


**_div** - Поддержка оператора 'divide' ('/'). См. [squirrel manual](http://squirrel-lang.org/squirreldoc/reference/language/metamethods.html#div) для получения подробностей.


**_modulo** - Поддержка оператора 'modulo' ('%'). См. [squirrel manual](http://squirrel-lang.org/squirreldoc/reference/language/metamethods.html#modulo) для получения подробностей.


**_cmp** - Поддержка операторов сравнения (<, >, <=, >=, ==, !=). См. [squirrel manual](http://squirrel-lang.org/squirreldoc/reference/language/metamethods.html#cmp) для получения подробностей.


**tostring** - Преобразует значение в string и возвращает его, см. [squirrel manual](http://squirrel-lang.org/squirreldoc/reference/language/builtin_functions.html#string) для получения подробностей. Реализован для совместимости со встроенными типами. Метод toString() также реализован для соответствия соглашениям об именовании camelCase.


**_tostring** - Поддержка преобразования в строку. См. [squirrel manual](http://squirrel-lang.org/squirreldoc/reference/language/metamethods.html#tostring) для получения подробностей.


**tointeger** - Преобразует значение в integer и возвращает его, см. [squirrel manual](http://squirrel-lang.org/squirreldoc/reference/language/builtin_functions.html#integer) для получения подробностей. Реализован для совместимости со встроенными типами. Метод toInteger() также реализован для соответствия соглашениям об именовании camelCase.


**tointeger64** - Преобразует значение в DotNut.Integer64 и возвращает его. Метод toInteger64() также реализован для соответствия соглашениям об именовании camelCase.


**tofloat** - Преобразует значение во float и возвращает его, см. [squirrel manual](http://squirrel-lang.org/squirreldoc/reference/language/builtin_functions.html#float) для получения подробностей. Реализован для совместимости со встроенными типами. Метод  toFloat() также реализован для соответствия соглашениям об именовании camelCase.


[format](../../DotNut/FileSystem/FileTime/format.md) - ![__BRIEF]


[isset](../../DotNut/FileSystem/FileTime/isset.md) - ![__BRIEF]


