## DotNut.AssetManager класс


```lua
class DotNut.AssetManager
{
    // Functions

    function isset()
    // returns: bool

    function isLastErrorOk()
    // returns: bool

    function getLastError()
    // returns: DotNut.ErrorCode

    function setLastError( err   // DotNut.ErrorCode
                         )
    // returns: DotNut.ErrorCode

    function clrLastError()
    // returns: DotNut.ErrorCode

    function getErrorCodeString( err   // DotNut.ErrorCode
                               )
    // returns: string

    function getPath( fullName   // string
                    )
    // returns: string

    function getFileName( fullName   // string
                        )
    // returns: string

    function getPathFile( fullName   // string
                        )
    // returns: string

    function getExt( fullName   // string
                   )
    // returns: string

    function getName( fullName   // string
                    )
    // returns: string

    function appendPath( path   // string
                       , name   // string
                       )
    // returns: string

    function appendExt( name   // string
                      , ext    // string
                      )
    // returns: string

    function getProjectName()
    // returns: string

    function readConfTextFile( confFileName   // string
                             )
    // returns: string

    function readConfDataFile( confFileName   // string
                             )
    // returns: DotNut.BinaryData

    function readAssetsDataFile( assetFileName   // string
                               )
    // returns: DotNut.BinaryData

    function readConfJson( confJsonFileName   // string
                         )
    // returns: table{DotNut.ErrorCode status, table data, string message}


} // class DotNut.AssetManager
```



### Методы


[isset](../DotNut/AssetManager/isset.md) - ![__BRIEF]


[isLastErrorOk](../DotNut/AssetManager/isLastErrorOk.md) - ![__BRIEF]


[getLastError](../DotNut/AssetManager/getLastError.md) - ![__BRIEF]


[setLastError](../DotNut/AssetManager/setLastError.md) - ![__BRIEF]


[clrLastError](../DotNut/AssetManager/clrLastError.md) - ![__BRIEF]


[getErrorCodeString](../DotNut/AssetManager/getErrorCodeString.md) - ![__BRIEF]


[getPath](../DotNut/AssetManager/getPath.md) - ![__BRIEF]


[getFileName](../DotNut/AssetManager/getFileName.md) - ![__BRIEF]


[getPathFile](../DotNut/AssetManager/getPathFile.md) - ![__BRIEF]


[getExt](../DotNut/AssetManager/getExt.md) - ![__BRIEF]


[getName](../DotNut/AssetManager/getName.md) - ![__BRIEF]


[appendPath](../DotNut/AssetManager/appendPath.md) - ![__BRIEF]


[appendExt](../DotNut/AssetManager/appendExt.md) - ![__BRIEF]


[getProjectName](../DotNut/AssetManager/getProjectName.md) - ![__BRIEF]


[readConfTextFile](../DotNut/AssetManager/readConfTextFile.md) - Читает текстовый файл из каталога '/conf'


[readConfDataFile](../DotNut/AssetManager/readConfDataFile.md) - Читает двоичный файл из каталога '/conf'.


[readAssetsDataFile](../DotNut/AssetManager/readAssetsDataFile.md) - Читает двоичный файл из каталога '/assets'.


[readConfJson](../DotNut/AssetManager/readConfJson.md) - Читает текстовый файл из каталога '/conf' и производит его разбор в таблицу, как файл в формате JSON.


