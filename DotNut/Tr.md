## DotNut.Tr пространство имён


Сервис для локализации приложений (перевода). Предоставляет API для получения локализованных сообщений.
```lua
table /* namespace */ DotNut.Tr
{


    // Functions

    function setDefLang( langId   // string
                       )
    // returns: string

    function getDefLang()
    // returns: string

    function setDefCategory( catId   // string
                           )
    // returns: string

    function getDefCategory()
    // returns: string

    function tr( msgId   // string
               )
    // returns: string

    function tr2( msgId   // string
                , catId   // string
                )
    // returns: string

    function tr3( msgId    // string
                , catId    // string
                , langId   // string
                )
    // returns: string

    function msgHasTr( msgId   // string
                     )
    // returns: bool

    function msgHasTr2( msgId   // string
                      , catId   // string
                      )
    // returns: bool

    function msgHasTr3( msgId    // string
                      , catId    // string
                      , langId   // string
                      )
    // returns: bool



} // table namespace DotNut.Tr
```


### Функции


[setDefLang](../DotNut/Tr/setDefLang.md) - Задаёт язык локализации сообщений по умолчанию


[getDefLang](../DotNut/Tr/getDefLang.md) - Возвращает текущий язык локализации, установленный по умолчанию.


[setDefCategory](../DotNut/Tr/setDefCategory.md) - Установка категории сообщений по умолчанию.


[getDefCategory](../DotNut/Tr/getDefCategory.md) - Возвращает текущущий идентификатор категории сообщений, установленный по умолчанию для получения локализованных сообщений


[tr](../DotNut/Tr/tr.md) - Возвращает локализованную строку сообщения


[tr2](../DotNut/Tr/tr2.md) - Возвращает локализованную строку сообщения с учетом указанной категории


[tr3](../DotNut/Tr/tr3.md) - Возвращает локализованную строку сообщения с учетом указанной категории и языка


[msgHasTr](../DotNut/Tr/msgHasTr.md) - Проверяет наличие локализации для сообщения.


[msgHasTr2](../DotNut/Tr/msgHasTr2.md) - Проверяет наличие локализации для сообщения в категории.


[msgHasTr3](../DotNut/Tr/msgHasTr3.md) - Проверяет наличие локализации для сообщения в категории для указанного языка.

