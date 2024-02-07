## DotNut.Utils.parseValueWithUnits функция

Разбор строки с единицами измерения, например: '12.5cm'


```lua
function parseValueWithUnits( strValueWithUnits   // string
                            , valueType           // DotNut.ValueType
                            , caseMatch           // bool|DotNut.CaseMatchType
                            , units               // array of [string unitStr,integer unitValue]
                            , defaultUnits        // integer
                            )
// returns: table{DotNut.ErrorCode status, integer|float value, integer units}
```


### Параметры

**strValueWithUnits** (**string**) - ![strValueWithUnits]

**valueType** ([DotNut.ValueType](../../DotNut/ValueType.md)) - ![valueType]

**caseMatch** (**bool** | [DotNut.CaseMatchType](../../DotNut/CaseMatchType.md)) - ![caseMatch]

**units** (**array** of [**string** unitStr,**integer** unitValue]) - ![units]

**defaultUnits** (**integer**) - ![defaultUnits]

### Возвращаемое значение

Возвращаемый тип: **table**{[DotNut.ErrorCode](../../DotNut/ErrorCode.md) status, **integer** | **float** value, **integer** units}

- status ([DotNut.ErrorCode](../../DotNut/ErrorCode.md)) - код ошибки, DotNut.ErrorCode::Ok, если преобразование прошло успешно.
- value (integer | float) - значение величины
- units (integer) - идентификтор единыцы измерения, один из заданных в параметрах.



### Примечания

Пример использования:
```lua
// Задаем сразу степени 10, по умолчанию - сантиметры
// Set up powers of ten, cm by default
local valWithUnits = DotNut.Utils.parseValueWithUnits( "10.5cm"
                                                     , DotNut.ValueType.ValueFloat
                                                     , DotNut.CaseMatchType.CaseIgnore
                                                     , [ ["mm",-3]
                                                       , ["cm",-2]
                                                       , ["dm",-1]
                                                       , ["m",0]
                                                       , ["km",3]
                                                       ]
                                                     , -2
                                                     );
if (valWithUnits.status!=DotNut.ErrorCode.Ok)
{
    smpprintln("Failed to parse value with units");
}
else
{
    smpprintln("Value with units, value module: [" + valWithUnits.value.tostring() + "], value units: [" + valWithUnits.units.tostring() + "]");
}
```

