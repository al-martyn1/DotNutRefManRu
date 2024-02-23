## DotNut.AssetManager.readConfJson метод

Читает текстовый файл из каталога '/conf' и производит его разбор в таблицу, как файл в формате JSON.


```lua
function readConfJson( confJsonFileName   // string
                     )
// returns: table{DotNut.ErrorCode status, table data, string message}
```


### Параметры

**confJsonFileName** (**string**) - ![confJsonFileName]

### Возвращаемое значение

Возвращаемый тип: **table**{[DotNut.ErrorCode](../../DotNut/ErrorCode.md) status, **table** data, **string** message}



### Примечания

При возникновении какой-либо ошибки возвращается пустая таблица.
