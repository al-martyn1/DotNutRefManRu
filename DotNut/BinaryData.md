## DotNut.BinaryData класс


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



### Методы


**len** - Возвращает количество элементов контейнера. String/Array-совместимый метод. См. [squirrel manual](http://squirrel-lang.org/squirreldoc/reference/language/builtin_functions.html#array.len) для получения подробностей.


**pop** - Удаляет последний элемент контейнера. Array-совместимый метод. См. [squirrel manual](http://squirrel-lang.org/squirreldoc/reference/language/builtin_functions.html#array.pop) для получения подробностей.


**top** - Возвращает последний элемент контейнера. Array-совместимый метод. См. [squirrel manual](http://squirrel-lang.org/squirreldoc/reference/language/builtin_functions.html#array.top) для получения подробностей.


**slice** - Возвращает часть контейнера ('срез') как новый контейнер. String/Array-совместимый метод. См. [squirrel manual](http://squirrel-lang.org/squirreldoc/reference/language/builtin_functions.html#array.slice) для получения подробностей.


**push** - Добавляет элемент в конец контейнера. Array-совместимый метод. См. [squirrel manual](http://squirrel-lang.org/squirreldoc/reference/language/builtin_functions.html#array.push) для получения подробностей.


**append** - Добавляет элемент в конец контейнера. Array-совместимый метод. См. [squirrel manual](http://squirrel-lang.org/squirreldoc/reference/language/builtin_functions.html#array.append) для получения подробностей.


**extend** - Расширяет контейнер, добавляя контейнер, переданный в аргументе, в конец текущего. Array-совместимый метод. См. [squirrel manual](http://squirrel-lang.org/squirreldoc/reference/language/builtin_functions.html#array.extend) для получения подробностей.


**insert** - Вставляет значение в контейнер в позицию ‘idx’. Array-совместимый метод. См. [squirrel manual](http://squirrel-lang.org/squirreldoc/reference/language/builtin_functions.html#array.insert) для получения подробностей.


**remove** - Удаляет элемент контейнера в позиции ‘idx’. Array-совместимый метод. См. [squirrel manual](http://squirrel-lang.org/squirreldoc/reference/language/builtin_functions.html#array.remove) для получения подробностей.


**resize** - Изменяет размер контейнера, удаляя или добавляя элементы. Значение параметра ‘fill’ используется для добавления новых элементов при расширении. Array-совместимый метод. См. [squirrel manual](http://squirrel-lang.org/squirreldoc/reference/language/builtin_functions.html#array.resize) для получения подробностей.


**reverse** - Измеряет порядок элементов текущего контейнера на обратный. Array-совместимый метод. См. [squirrel manual](http://squirrel-lang.org/squirreldoc/reference/language/builtin_functions.html#array.reverse) для получения подробностей.


**_set** - Поддержка оператора индексирования ('[]'). См. [squirrel manual](http://squirrel-lang.org/squirreldoc/reference/language/metamethods.html#set) для получения подробностей.


**_get** - Поддержка оператора индексирования ('[]'). См. [squirrel manual](http://squirrel-lang.org/squirreldoc/reference/language/metamethods.html#get) для получения подробностей.


[DotNut.BinaryData.setByte](../DotNut/BinaryData/setByte.md) - ![__BRIEF]


[DotNut.BinaryData.getByte](../DotNut/BinaryData/getByte.md) - ![__BRIEF]


[DotNut.BinaryData.getHostEndianness](../DotNut/BinaryData/getHostEndianness.md) - ![__BRIEF]


[DotNut.BinaryData.convertEndianness](../DotNut/BinaryData/convertEndianness.md) - ![__BRIEF]


**tointeger** - Преобразует значение в integer и возвращает его, см. [squirrel manual](http://squirrel-lang.org/squirreldoc/reference/language/builtin_functions.html#integer) для получения подробностей. Реализован для совместимости со встроенными типами. Метод toInteger() также реализован для соответствия соглашениям об именовании camelCase.


**tointeger64** - Преобразует значение в DotNut.Integer64 и возвращает его. Метод toInteger64() также реализован для соответствия соглашениям об именовании camelCase.


[DotNut.BinaryData.toArray](../DotNut/BinaryData/toArray.md) - ![__BRIEF]


**tostring** - Преобразует значение в string и возвращает его, см. [squirrel manual](http://squirrel-lang.org/squirreldoc/reference/language/builtin_functions.html#string) для получения подробностей. Реализован для совместимости со встроенными типами. Метод toString() также реализован для соответствия соглашениям об именовании camelCase.


