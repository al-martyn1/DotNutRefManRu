## DotNut.Utils пространство имён
```lua
table /* namespace */ DotNut.Utils
{


    // Functions

    function parseValueWithUnits( strValueWithUnits   // string
                                , valueType           // DotNut.ValueType
                                , caseMatch           // DotNut.CaseMatchType
                                , units               // array of [string unitStr,integer|float unitValue]
                                , defaultUnits        // integer|float
                                )
    // returns: table{DotNut.ErrorCode status, integer|float value, integer units}



} // table namespace DotNut.Utils
```


### Функции


[parseValueWithUnits](../DotNut/Utils/parseValueWithUnits.md) - Разбор строки с единицами измерения, например: '12.5cm'

