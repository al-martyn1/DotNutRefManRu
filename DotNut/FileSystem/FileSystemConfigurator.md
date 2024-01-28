## DotNut.FileSystem.FileSystemConfigurator class


```lua
class DotNut.FileSystem.FileSystemConfigurator
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



### Methods


[DotNut.FileSystem.FileSystemConfigurator.isset](../../DotNut/FileSystem/FileSystemConfigurator/isset.md) - ![__BRIEF]


[DotNut.FileSystem.FileSystemConfigurator.isLastErrorOk](../../DotNut/FileSystem/FileSystemConfigurator/isLastErrorOk.md) - ![__BRIEF]


[DotNut.FileSystem.FileSystemConfigurator.getLastError](../../DotNut/FileSystem/FileSystemConfigurator/getLastError.md) - ![__BRIEF]


[DotNut.FileSystem.FileSystemConfigurator.setLastError](../../DotNut/FileSystem/FileSystemConfigurator/setLastError.md) - ![__BRIEF]


[DotNut.FileSystem.FileSystemConfigurator.clrLastError](../../DotNut/FileSystem/FileSystemConfigurator/clrLastError.md) - ![__BRIEF]


[DotNut.FileSystem.FileSystemConfigurator.getErrorCodeString](../../DotNut/FileSystem/FileSystemConfigurator/getErrorCodeString.md) - ![__BRIEF]


[DotNut.FileSystem.FileSystemConfigurator.getPath](../../DotNut/FileSystem/FileSystemConfigurator/getPath.md) - ![__BRIEF]


[DotNut.FileSystem.FileSystemConfigurator.getFileName](../../DotNut/FileSystem/FileSystemConfigurator/getFileName.md) - ![__BRIEF]


[DotNut.FileSystem.FileSystemConfigurator.getPathFile](../../DotNut/FileSystem/FileSystemConfigurator/getPathFile.md) - ![__BRIEF]


[DotNut.FileSystem.FileSystemConfigurator.getExt](../../DotNut/FileSystem/FileSystemConfigurator/getExt.md) - ![__BRIEF]


[DotNut.FileSystem.FileSystemConfigurator.getName](../../DotNut/FileSystem/FileSystemConfigurator/getName.md) - ![__BRIEF]


[DotNut.FileSystem.FileSystemConfigurator.appendPath](../../DotNut/FileSystem/FileSystemConfigurator/appendPath.md) - ![__BRIEF]


[DotNut.FileSystem.FileSystemConfigurator.appendExt](../../DotNut/FileSystem/FileSystemConfigurator/appendExt.md) - ![__BRIEF]


[DotNut.FileSystem.FileSystemConfigurator.normalizeFilename](../../DotNut/FileSystem/FileSystemConfigurator/normalizeFilename.md) - ![__BRIEF]


[DotNut.FileSystem.FileSystemConfigurator.makePathCanonical](../../DotNut/FileSystem/FileSystemConfigurator/makePathCanonical.md) - ![__BRIEF]


[DotNut.FileSystem.FileSystemConfigurator.makeNativePathCanonical](../../DotNut/FileSystem/FileSystemConfigurator/makeNativePathCanonical.md) - ![__BRIEF]


[DotNut.FileSystem.FileSystemConfigurator.mapVirtualPath](../../DotNut/FileSystem/FileSystemConfigurator/mapVirtualPath.md) - ![__BRIEF]


[DotNut.FileSystem.FileSystemConfigurator.virtualizeRealPath](../../DotNut/FileSystem/FileSystemConfigurator/virtualizeRealPath.md) - ![__BRIEF]


[DotNut.FileSystem.FileSystemConfigurator.setGlobalReadOnly](../../DotNut/FileSystem/FileSystemConfigurator/setGlobalReadOnly.md) - ![__BRIEF]


[DotNut.FileSystem.FileSystemConfigurator.getGlobalReadOnly](../../DotNut/FileSystem/FileSystemConfigurator/getGlobalReadOnly.md) - ![__BRIEF]


[DotNut.FileSystem.FileSystemConfigurator.clearMounts](../../DotNut/FileSystem/FileSystemConfigurator/clearMounts.md) - ![__BRIEF]


[DotNut.FileSystem.FileSystemConfigurator.removeMountPoint](../../DotNut/FileSystem/FileSystemConfigurator/removeMountPoint.md) - ![__BRIEF]


[DotNut.FileSystem.FileSystemConfigurator.addMountPoint](../../DotNut/FileSystem/FileSystemConfigurator/addMountPoint.md) - ![__BRIEF]


[DotNut.FileSystem.FileSystemConfigurator.addMountPointEx](../../DotNut/FileSystem/FileSystemConfigurator/addMountPointEx.md) - ![__BRIEF]


