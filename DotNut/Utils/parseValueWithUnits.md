## DotNut.Utils.parseValueWithUnits функция

Разбор строки с единицами измерения, например: '12.5cm'.


```lua
function parseValueWithUnits( strValueWithUnits   // string
                            , valueType           // DotNut.ValueType
                            , caseMatch           // bool|DotNut.CaseMatchType
                            , units               // array of [string unitStr, integer unitValue]
                            , defaultUnits        // integer
                            )
// returns: table{DotNut.ErrorCode status, integer|float value, integer units}
```


### Параметры

**strValueWithUnits** (**string**) - Входная строка, содержащая значение с единицами измерений.

**valueType** ([DotNut.ValueType](../../DotNut/ValueType.md)) - тип значения, влияет на допустимые в строке символы и на тип результата (float | integer).

**caseMatch** (**bool** | [DotNut.CaseMatchType](../../DotNut/CaseMatchType.md)) - одно из значений [DotNut.CaseMatchType](../../DotNut/CaseMatchType.md), или bool: false - для точного соответствия регистра, true - для игнорирования регистра символов в единице измерения.

**units** (**array** of [**string** unitStr, **integer** unitValue]) - массив возможных значений единиц измерений в виде пар (массивов) строкового представления и целочисленного идентификатора.

**defaultUnits** (**integer**) - единицы измерений по умолчанию, если они отсутствуют в строке.

### Возвращаемое значение

Возвращаемый тип: **table**{[DotNut.ErrorCode](../../DotNut/ErrorCode.md) status, **integer** | **float** value, **integer** units}

- status ([DotNut.ErrorCode](../../DotNut/ErrorCode.md)) - код ошибки, DotNut.ErrorCode.Ok, если преобразование прошло успешно.
- value (integer | float) - значение величины
- units (integer) - идентификтор единицы измерения, один из заданных в параметре **units**.



### Пример использования

Пример разбора значения длины, значения можно задавать в милиметрах, сантиметрах, дециметрах, метрах и километрах:
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
.
