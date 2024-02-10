## DotNut.FileSystem.FileSystem класс


```lua
class DotNut.FileSystem.FileSystem
{
    // Functions

    constructor( parentFs   // DotNut.FileSystem.FileSystem
               )

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

    function normalizeFilename( name   // string
                              )
    // returns: string

    function makePathCanonical( path   // string
                              )
    // returns: string

    function makeNativePathCanonical( path   // string
                                    )
    // returns: string

    function mapVirtualPath( path   // string
                           )
    // returns: string

    function virtualizeRealPath( path   // string
                               )
    // returns: string

    function sealSettings()

    function getConfigurator()
    // returns: DotNut.FileSystem.FileSystemConfigurator

    function createDirectory( dirPath   // string
                            , bForce    // bool
                            )
    // returns: bool

    function enumerateDirectory( dirPath   // string
                               )
    // returns: array of DotNut.FileSystem.DirectoryEntry

    function testMaskMatch( entry   // DotNut.FileSystem.DirectoryEntryInfo
                          , mask    // DotNut.FileSystem.FileMask
                          )
    // returns: bool

    function enumerateDirectoryEx( dirPath          // string
                                 , enumerateFlags   // DotNut.FileSystem.EnumerateFlags
                                 , sortFlags        // DotNut.FileSystem.SortFlags
                                 )
    // returns: array of DotNut.FileSystem.DirectoryEntryInfo

    function compareFilenames( n1             // string
                             , n2             // string
                             , compareFlags   // DotNut.FileSystem.SortFlags
                             )
    // returns: integer

    function isFileExistAndReadable( fileName   // string
                                   )
    // returns: bool

    function isDirectory( dirPath   // string
                        )
    // returns: bool

    function readTextFile( fileName   // string
                         )
    // returns: string

    function writeTextFile( fileName     // string
                          , text         // string
                          , writeFlags   // DotNut.FileSystem.WriteFileFlags
                          )
    // returns: DotNut.ErrorCode

    function readDataFile( fileName   // string
                         )
    // returns: DotNut.BinaryData

    function writeDataFile( fileName     // string
                          , data         // DotNut.BinaryData
                          , writeFlags   // DotNut.FileSystem.WriteFileFlags
                          )
    // returns: DotNut.ErrorCode


} // class DotNut.FileSystem.FileSystem
```



### Методы


[constructor](../../DotNut/FileSystem/FileSystem/constructor.md) - ![__BRIEF]


[isset](../../DotNut/FileSystem/FileSystem/isset.md) - ![__BRIEF]


[isLastErrorOk](../../DotNut/FileSystem/FileSystem/isLastErrorOk.md) - ![__BRIEF]


[getLastError](../../DotNut/FileSystem/FileSystem/getLastError.md) - ![__BRIEF]


[setLastError](../../DotNut/FileSystem/FileSystem/setLastError.md) - ![__BRIEF]


[clrLastError](../../DotNut/FileSystem/FileSystem/clrLastError.md) - ![__BRIEF]


[getErrorCodeString](../../DotNut/FileSystem/FileSystem/getErrorCodeString.md) - ![__BRIEF]


[getPath](../../DotNut/FileSystem/FileSystem/getPath.md) - ![__BRIEF]


[getFileName](../../DotNut/FileSystem/FileSystem/getFileName.md) - ![__BRIEF]


[getPathFile](../../DotNut/FileSystem/FileSystem/getPathFile.md) - ![__BRIEF]


[getExt](../../DotNut/FileSystem/FileSystem/getExt.md) - ![__BRIEF]


[getName](../../DotNut/FileSystem/FileSystem/getName.md) - ![__BRIEF]


[appendPath](../../DotNut/FileSystem/FileSystem/appendPath.md) - ![__BRIEF]


[appendExt](../../DotNut/FileSystem/FileSystem/appendExt.md) - ![__BRIEF]


[normalizeFilename](../../DotNut/FileSystem/FileSystem/normalizeFilename.md) - ![__BRIEF]


[makePathCanonical](../../DotNut/FileSystem/FileSystem/makePathCanonical.md) - ![__BRIEF]


[makeNativePathCanonical](../../DotNut/FileSystem/FileSystem/makeNativePathCanonical.md) - ![__BRIEF]


[mapVirtualPath](../../DotNut/FileSystem/FileSystem/mapVirtualPath.md) - ![__BRIEF]


[virtualizeRealPath](../../DotNut/FileSystem/FileSystem/virtualizeRealPath.md) - ![__BRIEF]


[sealSettings](../../DotNut/FileSystem/FileSystem/sealSettings.md) - ![__BRIEF]


[getConfigurator](../../DotNut/FileSystem/FileSystem/getConfigurator.md) - ![__BRIEF]


[createDirectory](../../DotNut/FileSystem/FileSystem/createDirectory.md) - ![__BRIEF]


[enumerateDirectory](../../DotNut/FileSystem/FileSystem/enumerateDirectory.md) - ![__BRIEF]


[testMaskMatch](../../DotNut/FileSystem/FileSystem/testMaskMatch.md) - ![__BRIEF]


[enumerateDirectoryEx](../../DotNut/FileSystem/FileSystem/enumerateDirectoryEx.md) - ![__BRIEF]


[compareFilenames](../../DotNut/FileSystem/FileSystem/compareFilenames.md) - ![__BRIEF]


[isFileExistAndReadable](../../DotNut/FileSystem/FileSystem/isFileExistAndReadable.md) - ![__BRIEF]


[isDirectory](../../DotNut/FileSystem/FileSystem/isDirectory.md) - ![__BRIEF]


[readTextFile](../../DotNut/FileSystem/FileSystem/readTextFile.md) - ![__BRIEF]


[writeTextFile](../../DotNut/FileSystem/FileSystem/writeTextFile.md) - ![__BRIEF]


[readDataFile](../../DotNut/FileSystem/FileSystem/readDataFile.md) - ![__BRIEF]


[writeDataFile](../../DotNut/FileSystem/FileSystem/writeDataFile.md) - ![__BRIEF]


