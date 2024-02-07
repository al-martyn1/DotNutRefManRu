## DotNut.Utils.parseValueWithUnits функция


```lua
function parseValueWithUnits( strValueWithUnits   // string
                            , valueType           // DotNut.ValueType
                            , caseMatch           // DotNut.CaseMatchType
                            , units               // array of [string unitStr,integer|float unitValue]
                            , defaultUnits        // integer|float
                            )
// returns: table{DotNut.ErrorCode status, integer|float value, integer units}
```


### Параметры

**strValueWithUnits** (**string**) - ![strValueWithUnits]

**valueType** ([DotNut.ValueType](../../DotNut/ValueType.md)) - ![valueType]

**caseMatch** ([DotNut.CaseMatchType](../../DotNut/CaseMatchType.md)) - ![caseMatch]

**units** (**array** of [**string** unitStr,**integer** | **float** unitValue]) - ![units]

**defaultUnits** (**integer** | **float**) - ![defaultUnits]

### Возвращаемое значение

Возвращаемый тип: **table**{[DotNut.ErrorCode](../../DotNut/ErrorCode.md) status, **integer** | **float** value, **integer** units}

table{DotNut.ErrorCode status, integer | float value, integer units}

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


