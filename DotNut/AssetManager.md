## DotNut.AssetManager class


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

    function readConfJson( confJsonFileName   // string
                         )
    // returns: table


} // class DotNut.AssetManager
```



### Methods


[DotNut.AssetManager.isset](../DotNut/AssetManager/isset.md) - ![__BRIEF]


[DotNut.AssetManager.isLastErrorOk](../DotNut/AssetManager/isLastErrorOk.md) - ![__BRIEF]


[DotNut.AssetManager.getLastError](../DotNut/AssetManager/getLastError.md) - ![__BRIEF]


[DotNut.AssetManager.setLastError](../DotNut/AssetManager/setLastError.md) - ![__BRIEF]


[DotNut.AssetManager.clrLastError](../DotNut/AssetManager/clrLastError.md) - ![__BRIEF]


[DotNut.AssetManager.getErrorCodeString](../DotNut/AssetManager/getErrorCodeString.md) - ![__BRIEF]


[DotNut.AssetManager.getPath](../DotNut/AssetManager/getPath.md) - ![__BRIEF]


[DotNut.AssetManager.getFileName](../DotNut/AssetManager/getFileName.md) - ![__BRIEF]


[DotNut.AssetManager.getPathFile](../DotNut/AssetManager/getPathFile.md) - ![__BRIEF]


[DotNut.AssetManager.getExt](../DotNut/AssetManager/getExt.md) - ![__BRIEF]


[DotNut.AssetManager.getName](../DotNut/AssetManager/getName.md) - ![__BRIEF]


[DotNut.AssetManager.appendPath](../DotNut/AssetManager/appendPath.md) - ![__BRIEF]


[DotNut.AssetManager.appendExt](../DotNut/AssetManager/appendExt.md) - ![__BRIEF]


[DotNut.AssetManager.getProjectName](../DotNut/AssetManager/getProjectName.md) - ![__BRIEF]


[DotNut.AssetManager.readConfTextFile](../DotNut/AssetManager/readConfTextFile.md) - ![__BRIEF]


[DotNut.AssetManager.readConfDataFile](../DotNut/AssetManager/readConfDataFile.md) - ![__BRIEF]


[DotNut.AssetManager.readConfJson](../DotNut/AssetManager/readConfJson.md) - ![__BRIEF]


