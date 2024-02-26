## Drawing.ImageList класс


```lua
class Drawing.ImageList
{
    // Functions

    constructor()

    function clear()

    function size()
    // returns: integer

    function empty()
    // returns: bool

    function getMimeTypeByFileName( string   // 
                                  )
    // returns: string

    function getImageInfo( imageIdx   // integer
                         )
    // returns: Drawing.ImageInfo

    function getAvailSizesByMime( binData    // DotNut.BinaryData
                                , mimeType   // string
                                )
    // returns: array of Drawing.ImageSize

    function getAvailSizesByExt( binData   // DotNut.BinaryData
                               , ext       // string
                               )
    // returns: array of Drawing.ImageSize

    function getNumberOfImagesByMime( binData    // DotNut.BinaryData
                                    , mimeType   // string
                                    )
    // returns: integer

    function getNumberOfImagesByExt( binData   // DotNut.BinaryData
                                   , ext       // string
                                   )
    // returns: integer

    function findBestFitImageByMime( binData         // DotNut.BinaryData
                                   , mimeType        // string
                                   , requestedSize   // Drawing.ImageSize
                                   )
    // returns: integer

    function findBestFitImageByExt( binData         // DotNut.BinaryData
                                  , ext             // string
                                  , requestedSize   // Drawing.ImageSize
                                  )
    // returns: integer

    function findBestFitImageByMimeGetFoundSize( binData         // DotNut.BinaryData
                                               , mimeType        // string
                                               , requestedSize   // Drawing.ImageSize
                                               )
    // returns: Drawing.ImageSize

    function findBestFitImageByExtGetFoundSize( binData         // DotNut.BinaryData
                                              , ext             // string
                                              , requestedSize   // Drawing.ImageSize
                                              )
    // returns: Drawing.ImageSize

    function getMimeTypeByFileName( name   // string
                                  )
    // returns: string

    function addImageByMime( binData       // DotNut.BinaryData
                           , mimeType      // string
                           , imageRawIdx   // integer
                           )
    // returns: integer

    function addImageByExt( binData       // DotNut.BinaryData
                          , ext           // string
                          , imageRawIdx   // integer
                          )
    // returns: integer

    function addImageFitSizeByMime( binData         // DotNut.BinaryData
                                  , mimeType        // string
                                  , requestedSize   // Drawing.ImageSize
                                  )
    // returns: integer

    function addImageFitSizeByExt( binData         // DotNut.BinaryData
                                 , ext             // string
                                 , requestedSize   // Drawing.ImageSize
                                 )
    // returns: integer

    function createMaskByColor( imageIdx   // integer
                              , clr        // Drawing.Color
                              )
    // returns: bool

    function createMaskByPos( imageIdx            // integer
                            , maskColorPixelPos   // Drawing.ImageSize
                            )
    // returns: bool

    function saveImageAsBmp( imageIdx   // integer
                           )
    // returns: DotNut.BinaryData

    function addImageBandFromMultipartImageByMime( imageData      // DotNut.BinaryData
                                                 , mimeType       // string
                                                 , frameMinSize   // Drawing.ImageSize
                                                 , flags          // Drawing.ImageListBandFlags
                                                 )
    // returns: Drawing.AddImageBandResult

    function addImageBandFromMultipartImageByExt( imageData      // DotNut.BinaryData
                                                , ext            // string
                                                , frameMinSize   // Drawing.ImageSize
                                                , flags          // Drawing.ImageListBandFlags
                                                )
    // returns: Drawing.AddImageBandResult

    function addImageBandFromMultipartImageByMimeRange( imageData       // DotNut.BinaryData
                                                      , mimeType        // string
                                                      , frameMinSize    // Drawing.ImageSize
                                                      , flags           // Drawing.ImageListBandFlags
                                                      , firstFrameIdx   // int
                                                      , numFrames       // int
                                                      )
    // returns: Drawing.AddImageBandResult

    function addImageBandFromMultipartImageByExtRange( imageData       // DotNut.BinaryData
                                                     , ext             // string
                                                     , frameMinSize    // Drawing.ImageSize
                                                     , flags           // Drawing.ImageListBandFlags
                                                     , firstFrameIdx   // int
                                                     , numFrames       // int
                                                     )
    // returns: Drawing.AddImageBandResult

    function addImageBandFromMultipartImageByMimeEx( imageData      // DotNut.BinaryData
                                                   , mimeType       // string
                                                   , frameMinSize   // Drawing.ImageSize
                                                   , flags          // Drawing.ImageListBandFlags
                                                   , frames         // array of int
                                                   )
    // returns: Drawing.AddImageBandResult

    function addImageBandFromMultipartImageByExtEx( imageData      // DotNut.BinaryData
                                                  , ext            // string
                                                  , frameMinSize   // Drawing.ImageSize
                                                  , flags          // Drawing.ImageListBandFlags
                                                  , frames         // array of int
                                                  )
    // returns: Drawing.AddImageBandResult


} // class Drawing.ImageList
```



### Методы


[constructor](../Drawing/ImageList/constructor.md) - ![__BRIEF]


[clear](../Drawing/ImageList/clear.md) - ![__BRIEF]


[size](../Drawing/ImageList/size.md) - ![__BRIEF]


[empty](../Drawing/ImageList/empty.md) - ![__BRIEF]


[getMimeTypeByFileName](../Drawing/ImageList/getMimeTypeByFileName.md) - ![__BRIEF]


[getImageInfo](../Drawing/ImageList/getImageInfo.md) - ![__BRIEF]


[getAvailSizesByMime](../Drawing/ImageList/getAvailSizesByMime.md) - ![__BRIEF]


[getAvailSizesByExt](../Drawing/ImageList/getAvailSizesByExt.md) - ![__BRIEF]


[getNumberOfImagesByMime](../Drawing/ImageList/getNumberOfImagesByMime.md) - ![__BRIEF]


[getNumberOfImagesByExt](../Drawing/ImageList/getNumberOfImagesByExt.md) - ![__BRIEF]


[findBestFitImageByMime](../Drawing/ImageList/findBestFitImageByMime.md) - ![__BRIEF]


[findBestFitImageByExt](../Drawing/ImageList/findBestFitImageByExt.md) - ![__BRIEF]


[findBestFitImageByMimeGetFoundSize](../Drawing/ImageList/findBestFitImageByMimeGetFoundSize.md) - ![__BRIEF]


[findBestFitImageByExtGetFoundSize](../Drawing/ImageList/findBestFitImageByExtGetFoundSize.md) - ![__BRIEF]


[getMimeTypeByFileName](../Drawing/ImageList/getMimeTypeByFileName.md) - ![__BRIEF]


[addImageByMime](../Drawing/ImageList/addImageByMime.md) - ![__BRIEF]


[addImageByExt](../Drawing/ImageList/addImageByExt.md) - ![__BRIEF]


[addImageFitSizeByMime](../Drawing/ImageList/addImageFitSizeByMime.md) - ![__BRIEF]


[addImageFitSizeByExt](../Drawing/ImageList/addImageFitSizeByExt.md) - ![__BRIEF]


[createMaskByColor](../Drawing/ImageList/createMaskByColor.md) - ![__BRIEF]


[createMaskByPos](../Drawing/ImageList/createMaskByPos.md) - ![__BRIEF]


[saveImageAsBmp](../Drawing/ImageList/saveImageAsBmp.md) - ![__BRIEF]


[addImageBandFromMultipartImageByMime](../Drawing/ImageList/addImageBandFromMultipartImageByMime.md) - ![__BRIEF]


[addImageBandFromMultipartImageByExt](../Drawing/ImageList/addImageBandFromMultipartImageByExt.md) - ![__BRIEF]


[addImageBandFromMultipartImageByMimeRange](../Drawing/ImageList/addImageBandFromMultipartImageByMimeRange.md) - ![__BRIEF]


[addImageBandFromMultipartImageByExtRange](../Drawing/ImageList/addImageBandFromMultipartImageByExtRange.md) - ![__BRIEF]


[addImageBandFromMultipartImageByMimeEx](../Drawing/ImageList/addImageBandFromMultipartImageByMimeEx.md) - ![__BRIEF]


[addImageBandFromMultipartImageByExtEx](../Drawing/ImageList/addImageBandFromMultipartImageByExtEx.md) - ![__BRIEF]


