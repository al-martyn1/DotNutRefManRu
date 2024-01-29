## Drawing.Color класс


```lua
class Drawing.Color
{
    // Member Fields

    r; // integer
    g; // integer
    b; // integer
    a; // integer


    // Functions

    constructor( clrInit   // integer|float|string|array of integer[r,g,b,a]|Drawing.Color
               )

    static
    function fromRgb( r   // integer
                    , g   // integer
                    , b   // integer
                    )
    // returns: Drawing.Color

    static
    function fromUnsigned( u   // integer
                         )
    // returns: Drawing.Color

    static
    function fromInt( u   // integer
                    )
    // returns: Drawing.Color

    static
    function fromInteger( u   // integer
                        )
    // returns: Drawing.Color

    static
    function fromString( nameOrIntStr   // string
                       )
    // returns: Drawing.Color

    function toUnsigned()
    // returns: integer

    function toInt()
    // returns: integer

    function tointeger()
    // returns: integer

    function tofloat()
    // returns: float

    function tostring()
    // returns: string

    function _tostring()
    // returns: string


} // class Drawing.Color
```



### Поля класса

**r** (**integer**) - ![r]

**g** (**integer**) - ![g]

**b** (**integer**) - ![b]

**a** (**integer**) - ![a]


### Методы


[constructor](../Drawing/Color/constructor.md) - ![__BRIEF]


[fromRgb](../Drawing/Color/fromRgb.md) - ![__BRIEF]


[fromUnsigned](../Drawing/Color/fromUnsigned.md) - ![__BRIEF]


[fromInt](../Drawing/Color/fromInt.md) - ![__BRIEF]


[fromInteger](../Drawing/Color/fromInteger.md) - ![__BRIEF]


[fromString](../Drawing/Color/fromString.md) - ![__BRIEF]


[toUnsigned](../Drawing/Color/toUnsigned.md) - ![__BRIEF]


[toInt](../Drawing/Color/toInt.md) - ![__BRIEF]


**tointeger** - Преобразует значение в integer и возвращает его, см. [squirrel manual](http://squirrel-lang.org/squirreldoc/reference/language/builtin_functions.html#integer) для получения подробностей. Реализован для совместимости со встроенными типами. Метод toInteger() также реализован для соответствия соглашениям об именовании camelCase.


**tofloat** - Преобразует значение во float и возвращает его, см. [squirrel manual](http://squirrel-lang.org/squirreldoc/reference/language/builtin_functions.html#float) для получения подробностей. Реализован для совместимости со встроенными типами. Метод  toFloat() также реализован для соответствия соглашениям об именовании camelCase.


**tostring** - Преобразует значение в string и возвращает его, см. [squirrel manual](http://squirrel-lang.org/squirreldoc/reference/language/builtin_functions.html#string) для получения подробностей. Реализован для совместимости со встроенными типами. Метод toString() также реализован для соответствия соглашениям об именовании camelCase.


**_tostring** - Поддержка преобразования в строку. См. [squirrel manual](http://squirrel-lang.org/squirreldoc/reference/language/metamethods.html#tostring) для получения подробностей.


