## DotNut.FileSystem.FileSystemConfigurator класс


```lua
class DotNut.FileSystem.FileSystemConfigurator
{
    // Functions

    constructor()

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

    function setGlobalReadOnly( ro   // bool
                              )
    // returns: bool

    function getGlobalReadOnly()
    // returns: bool

    function clearMounts()
    // returns: DotNut.ErrorCode

    function removeMountPoint( mntPointName   // string
                             )
    // returns: DotNut.ErrorCode

    function addMountPoint( mntPointName     // string
                          , mntPointTarget   // string
                          )
    // returns: DotNut.ErrorCode

    function addMountPointEx( mntPointName     // string
                            , mntPointTarget   // string
                            , flags            // DotNut.FileSystem.FileTypeFlags
                            )
    // returns: DotNut.ErrorCode


} // class DotNut.FileSystem.FileSystemConfigurator
```



### Методы


[constructor](../../DotNut/FileSystem/FileSystemConfigurator/constructor.md) - ![__BRIEF]


[isset](../../DotNut/FileSystem/FileSystemConfigurator/isset.md) - ![__BRIEF]


[isLastErrorOk](../../DotNut/FileSystem/FileSystemConfigurator/isLastErrorOk.md) - ![__BRIEF]


[getLastError](../../DotNut/FileSystem/FileSystemConfigurator/getLastError.md) - ![__BRIEF]


[setLastError](../../DotNut/FileSystem/FileSystemConfigurator/setLastError.md) - ![__BRIEF]


[clrLastError](../../DotNut/FileSystem/FileSystemConfigurator/clrLastError.md) - ![__BRIEF]


[getErrorCodeString](../../DotNut/FileSystem/FileSystemConfigurator/getErrorCodeString.md) - ![__BRIEF]


[getPath](../../DotNut/FileSystem/FileSystemConfigurator/getPath.md) - ![__BRIEF]


[getFileName](../../DotNut/FileSystem/FileSystemConfigurator/getFileName.md) - ![__BRIEF]


[getPathFile](../../DotNut/FileSystem/FileSystemConfigurator/getPathFile.md) - ![__BRIEF]


[getExt](../../DotNut/FileSystem/FileSystemConfigurator/getExt.md) - ![__BRIEF]


[getName](../../DotNut/FileSystem/FileSystemConfigurator/getName.md) - ![__BRIEF]


[appendPath](../../DotNut/FileSystem/FileSystemConfigurator/appendPath.md) - ![__BRIEF]


[appendExt](../../DotNut/FileSystem/FileSystemConfigurator/appendExt.md) - ![__BRIEF]


[normalizeFilename](../../DotNut/FileSystem/FileSystemConfigurator/normalizeFilename.md) - ![__BRIEF]


[makePathCanonical](../../DotNut/FileSystem/FileSystemConfigurator/makePathCanonical.md) - ![__BRIEF]


[makeNativePathCanonical](../../DotNut/FileSystem/FileSystemConfigurator/makeNativePathCanonical.md) - ![__BRIEF]


[mapVirtualPath](../../DotNut/FileSystem/FileSystemConfigurator/mapVirtualPath.md) - ![__BRIEF]


[virtualizeRealPath](../../DotNut/FileSystem/FileSystemConfigurator/virtualizeRealPath.md) - ![__BRIEF]


[setGlobalReadOnly](../../DotNut/FileSystem/FileSystemConfigurator/setGlobalReadOnly.md) - ![__BRIEF]


[getGlobalReadOnly](../../DotNut/FileSystem/FileSystemConfigurator/getGlobalReadOnly.md) - ![__BRIEF]


[clearMounts](../../DotNut/FileSystem/FileSystemConfigurator/clearMounts.md) - ![__BRIEF]


[removeMountPoint](../../DotNut/FileSystem/FileSystemConfigurator/removeMountPoint.md) - ![__BRIEF]


[addMountPoint](../../DotNut/FileSystem/FileSystemConfigurator/addMountPoint.md) - ![__BRIEF]


[addMountPointEx](../../DotNut/FileSystem/FileSystemConfigurator/addMountPointEx.md) - ![__BRIEF]


