## Drawing.Context class


```lua
class Drawing.Context
{
    // Functions

    function flushBits()

    function setDrawingPrecise( p   // Drawing.DrawingPrecise
                              )
    // returns: Drawing.DrawingPrecise

    function getDrawingPrecise()
    // returns: Drawing.DrawingPrecise

    function getRawSize()
    // returns: Drawing.Coords

    function getSize()
    // returns: Drawing.Coords

    function distanceBetween( pos1   // Drawing.Coords
                            , pos2   // Drawing.Coords
                            )
    // returns: float

    function reflectPoint( point               // Drawing.Coords
                         , reflectRelativeTo   // Drawing.Coords
                         )
    // returns: Drawing.Coords

    function setCollectMarkers( newCollectMarkersMode   // bool
                              )
    // returns: bool

    function getCollectMarkers()
    // returns: bool

    function markerAdd( markerPos   // Drawing.Coords
                      )
    // returns: bool

    function markerAddEx( markerPos    // Drawing.Coords
                        , markerSize   // any_integral
                        )
    // returns: bool

    function markersClear()
    // returns: bool

    function markersDraw()
    // returns: bool

    function markersDrawEx( penId   // int
                          )
    // returns: bool

    function markerSetDefSize( markerSize   // any_integral
                             )
    // returns: float

    function markerGetDefSize()
    // returns: float

    function setSmoothingMode( smoothingMode   // Drawing.SmoothingMode
                             )
    // returns: Drawing.SmoothingMode

    function getSmoothingMode()
    // returns: Drawing.SmoothingMode

    function setTextColor( clr   // Drawing.Color
                         )
    // returns: Drawing.Color

    function getTextColor()
    // returns: Drawing.Color

    function setBkColor( clr   // Drawing.Color
                       )
    // returns: Drawing.Color

    function getBkColor()
    // returns: Drawing.Color

    function setBkMode( bkMode   // Drawing.BkMode
                      )
    // returns: Drawing.BkMode

    function getBkMode()
    // returns: Drawing.BkMode

    function getDialigBaseUnits()
    // returns: Drawing.Coords

    function mapRawToLogicPos( c   // Drawing.Coords
                             )
    // returns: Drawing.Coords

    function mapRawToLogicSize( c   // Drawing.Coords
                              )
    // returns: Drawing.Coords

    function getPixelSize()
    // returns: Drawing.Coords

    function getScaledPos( c   // Drawing.Coords
                         )
    // returns: Drawing.Coords

    function getScaledSize( c   // Drawing.Coords
                          )
    // returns: Drawing.Coords

    function setOffset( c   // Drawing.Coords
                      )
    // returns: Drawing.Coords

    function getOffset()
    // returns: Drawing.Coords

    function setScale( c   // Drawing.Coords
                     )
    // returns: Drawing.Coords

    function getScale()
    // returns: Drawing.Coords

    function setPenScale( scale   // any_integral
                        )
    // returns: float

    function getPenScale()
    // returns: float

    function createSolidPen( penParams   // Drawing.PenParams
                           , clr         // Drawing.Color
                           )
    // returns: integer

    function selectPen( penId   // integer
                      )
    // returns: integer

    function selectNewSolidPen( penParams   // Drawing.PenParams
                              , clr         // Drawing.Color
                              )
    // returns: integer

    function getCurPen()
    // returns: integer

    function getPenColor( penId   // integer
                        )
    // returns: Drawing.Color

    function getPenParams( penId   // integer
                         )
    // returns: Drawing.PenParams

    function setDefaultCosmeticPen( penId   // integer
                                  )
    // returns: integer

    function getDefaultCosmeticPen()
    // returns: integer

    function createSolidBrush( rgb   // Drawing.Color
                             )
    // returns: integer

    function selectBrush( brushId   // integer
                        )
    // returns: integer

    function selectNewSolidBrush( rgb   // Drawing.Color
                                )
    // returns: integer

    function getCurBrush()
    // returns: integer

    function createFont( fontParams   // Drawing.FontParams
                       )
    // returns: integer

    function createFontEx( fontParams   // Drawing.FontParams
                         , height       // any_integral
                         )
    // returns: integer

    function createOrFindFont( fontParams   // Drawing.FontParams
                             )
    // returns: integer

    function createOrFindFontEx( fontParams   // Drawing.FontParams
                               , height       // any_integral
                               )
    // returns: integer

    function selectFont( fontId   // integer
                       )
    // returns: integer

    function selectNewFont( fontParams   // Drawing.FontParams
                          )
    // returns: integer

    function selectNewFontEx( fontParams   // Drawing.FontParams
                            , height       // any_integral
                            )
    // returns: integer

    function createFontWithFace( fontParams   // Drawing.FontParams
                               , fontFace     // string
                               )
    // returns: integer

    function createOrFindFontWithFace( fontParams   // Drawing.FontParams
                                     , fontFace     // string
                                     )
    // returns: integer

    function getCurFont()
    // returns: integer

    function getFontParamsById( id   // integer
                              )
    // returns: Drawing.FontParams

    function beginPath()
    // returns: bool

    function beginPathFrom( c   // Drawing.Coords
                          )
    // returns: bool

    function endPath( bStroke   // bool
                    , bFill     // bool
                    )
    // returns: bool

    function closeFigure()
    // returns: bool

    function isPathStarted()
    // returns: bool

    function moveTo( to   // Drawing.Coords
                   )
    // returns: bool

    function lineTo( to   // Drawing.Coords
                   )
    // returns: bool

    function ellipse( leftTop       // Drawing.Coords
                    , rightBottom   // Drawing.Coords
                    )
    // returns: bool

    function fillEllipse( leftTop       // Drawing.Coords
                        , rightBottom   // Drawing.Coords
                        , drawFrame     // bool
                        )
    // returns: bool

    function ellipticArcTo( leftTop            // Drawing.Coords
                          , rightBottom        // Drawing.Coords
                          , arcStartRefPoint   // Drawing.Coords
                          , arcEndRefPoint     // Drawing.Coords
                          , arcDirection       // Drawing.ArcDirection
                          )
    // returns: bool

    function getLastArcEndPos()
    // returns: Drawing.Coords

    function arcToPos( centerPos      // Drawing.Coords
                     , endPos         // Drawing.Coords
                     , arcDirection   // Drawing.ArcDirection
                     )
    // returns: bool

    function arcByAngleDeg( centerPos   // Drawing.Coords
                          , angle       // any_integral
                          )
    // returns: bool

    function roundRectFigure( cornersR   // any_integral
                            , points     // array of Drawing.Coords
                            )
    // returns: bool

    function circle( centerPos   // Drawing.Coords
                   , r           // any_integral
                   )
    // returns: bool

    function fillCircle( centerPos   // Drawing.Coords
                       , r           // any_integral
                       , drawFrame   // bool
                       )
    // returns: bool

    function roundRect( cornersR      // any_integral
                      , leftTop       // Drawing.Coords
                      , rightBottom   // Drawing.Coords
                      )
    // returns: bool

    function fillRoundRect( cornersR      // any_integral
                          , leftTop       // Drawing.Coords
                          , rightBottom   // Drawing.Coords
                          , drawFrame     // bool
                          )
    // returns: bool

    function rect( leftTop       // Drawing.Coords
                 , rightBottom   // Drawing.Coords
                 )
    // returns: bool

    function fillRect( leftTop       // Drawing.Coords
                     , rightBottom   // Drawing.Coords
                     , drawFrame     // bool
                     )
    // returns: bool

    function fillGradientRect( leftTop          // Drawing.Coords
                             , rightBottom      // Drawing.Coords
                             , gradientParams   // Drawing.GradientParams
                             , gradientType     // Drawing.GradientType
                             , excludeFrame     // bool
                             )
    // returns: bool

    function fillGradientRoundRect( cornersR         // any_integral
                                  , leftTop          // Drawing.Coords
                                  , rightBottom      // Drawing.Coords
                                  , gradientParams   // Drawing.GradientParams
                                  , gradientType     // Drawing.GradientType
                                  , excludeFrame     // bool
                                  , fillBreakPos     // float
                                  , fillFlags        // Drawing.GradientRoundRectFillFlags
                                  )
    // returns: bool

    function fillGradientCircle( pos              // Drawing.Coords
                               , r                // any_integral
                               , gradientParams   // Drawing.GradientParams
                               , excludeFrame     // bool
                               )
    // returns: bool

    function textOut( pos    // Drawing.Coords
                    , text   // string
                    )
    // returns: bool


} // class Drawing.Context
```



### Methods


[Drawing.Context.flushBits](../Drawing/Context/flushBits.md) - ![__BRIEF]


[Drawing.Context.setDrawingPrecise](../Drawing/Context/setDrawingPrecise.md) - ![__BRIEF]


[Drawing.Context.getDrawingPrecise](../Drawing/Context/getDrawingPrecise.md) - ![__BRIEF]


[Drawing.Context.getRawSize](../Drawing/Context/getRawSize.md) - ![__BRIEF]


[Drawing.Context.getSize](../Drawing/Context/getSize.md) - ![__BRIEF]


[Drawing.Context.distanceBetween](../Drawing/Context/distanceBetween.md) - ![__BRIEF]


[Drawing.Context.reflectPoint](../Drawing/Context/reflectPoint.md) - ![__BRIEF]


[Drawing.Context.setCollectMarkers](../Drawing/Context/setCollectMarkers.md) - ![__BRIEF]


[Drawing.Context.getCollectMarkers](../Drawing/Context/getCollectMarkers.md) - ![__BRIEF]


[Drawing.Context.markerAdd](../Drawing/Context/markerAdd.md) - ![__BRIEF]


[Drawing.Context.markerAddEx](../Drawing/Context/markerAddEx.md) - ![__BRIEF]


[Drawing.Context.markersClear](../Drawing/Context/markersClear.md) - ![__BRIEF]


[Drawing.Context.markersDraw](../Drawing/Context/markersDraw.md) - ![__BRIEF]


[Drawing.Context.markersDrawEx](../Drawing/Context/markersDrawEx.md) - ![__BRIEF]


[Drawing.Context.markerSetDefSize](../Drawing/Context/markerSetDefSize.md) - ![__BRIEF]


[Drawing.Context.markerGetDefSize](../Drawing/Context/markerGetDefSize.md) - ![__BRIEF]


[Drawing.Context.setSmoothingMode](../Drawing/Context/setSmoothingMode.md) - ![__BRIEF]


[Drawing.Context.getSmoothingMode](../Drawing/Context/getSmoothingMode.md) - ![__BRIEF]


[Drawing.Context.setTextColor](../Drawing/Context/setTextColor.md) - ![__BRIEF]


[Drawing.Context.getTextColor](../Drawing/Context/getTextColor.md) - ![__BRIEF]


[Drawing.Context.setBkColor](../Drawing/Context/setBkColor.md) - ![__BRIEF]


[Drawing.Context.getBkColor](../Drawing/Context/getBkColor.md) - ![__BRIEF]


[Drawing.Context.setBkMode](../Drawing/Context/setBkMode.md) - ![__BRIEF]


[Drawing.Context.getBkMode](../Drawing/Context/getBkMode.md) - ![__BRIEF]


[Drawing.Context.getDialigBaseUnits](../Drawing/Context/getDialigBaseUnits.md) - ![__BRIEF]


[Drawing.Context.mapRawToLogicPos](../Drawing/Context/mapRawToLogicPos.md) - ![__BRIEF]


[Drawing.Context.mapRawToLogicSize](../Drawing/Context/mapRawToLogicSize.md) - ![__BRIEF]


[Drawing.Context.getPixelSize](../Drawing/Context/getPixelSize.md) - ![__BRIEF]


[Drawing.Context.getScaledPos](../Drawing/Context/getScaledPos.md) - ![__BRIEF]


[Drawing.Context.getScaledSize](../Drawing/Context/getScaledSize.md) - ![__BRIEF]


[Drawing.Context.setOffset](../Drawing/Context/setOffset.md) - ![__BRIEF]


[Drawing.Context.getOffset](../Drawing/Context/getOffset.md) - ![__BRIEF]


[Drawing.Context.setScale](../Drawing/Context/setScale.md) - ![__BRIEF]


[Drawing.Context.getScale](../Drawing/Context/getScale.md) - ![__BRIEF]


[Drawing.Context.setPenScale](../Drawing/Context/setPenScale.md) - ![__BRIEF]


[Drawing.Context.getPenScale](../Drawing/Context/getPenScale.md) - ![__BRIEF]


[Drawing.Context.createSolidPen](../Drawing/Context/createSolidPen.md) - ![__BRIEF]


[Drawing.Context.selectPen](../Drawing/Context/selectPen.md) - ![__BRIEF]


[Drawing.Context.selectNewSolidPen](../Drawing/Context/selectNewSolidPen.md) - ![__BRIEF]


[Drawing.Context.getCurPen](../Drawing/Context/getCurPen.md) - ![__BRIEF]


[Drawing.Context.getPenColor](../Drawing/Context/getPenColor.md) - ![__BRIEF]


[Drawing.Context.getPenParams](../Drawing/Context/getPenParams.md) - ![__BRIEF]


[Drawing.Context.setDefaultCosmeticPen](../Drawing/Context/setDefaultCosmeticPen.md) - ![__BRIEF]


[Drawing.Context.getDefaultCosmeticPen](../Drawing/Context/getDefaultCosmeticPen.md) - ![__BRIEF]


[Drawing.Context.createSolidBrush](../Drawing/Context/createSolidBrush.md) - ![__BRIEF]


[Drawing.Context.selectBrush](../Drawing/Context/selectBrush.md) - ![__BRIEF]


[Drawing.Context.selectNewSolidBrush](../Drawing/Context/selectNewSolidBrush.md) - ![__BRIEF]


[Drawing.Context.getCurBrush](../Drawing/Context/getCurBrush.md) - ![__BRIEF]


[Drawing.Context.createFont](../Drawing/Context/createFont.md) - ![__BRIEF]


[Drawing.Context.createFontEx](../Drawing/Context/createFontEx.md) - ![__BRIEF]


[Drawing.Context.createOrFindFont](../Drawing/Context/createOrFindFont.md) - ![__BRIEF]


[Drawing.Context.createOrFindFontEx](../Drawing/Context/createOrFindFontEx.md) - ![__BRIEF]


[Drawing.Context.selectFont](../Drawing/Context/selectFont.md) - ![__BRIEF]


[Drawing.Context.selectNewFont](../Drawing/Context/selectNewFont.md) - ![__BRIEF]


[Drawing.Context.selectNewFontEx](../Drawing/Context/selectNewFontEx.md) - ![__BRIEF]


[Drawing.Context.createFontWithFace](../Drawing/Context/createFontWithFace.md) - ![__BRIEF]


[Drawing.Context.createOrFindFontWithFace](../Drawing/Context/createOrFindFontWithFace.md) - ![__BRIEF]


[Drawing.Context.getCurFont](../Drawing/Context/getCurFont.md) - ![__BRIEF]


[Drawing.Context.getFontParamsById](../Drawing/Context/getFontParamsById.md) - ![__BRIEF]


[Drawing.Context.beginPath](../Drawing/Context/beginPath.md) - ![__BRIEF]


[Drawing.Context.beginPathFrom](../Drawing/Context/beginPathFrom.md) - ![__BRIEF]


[Drawing.Context.endPath](../Drawing/Context/endPath.md) - ![__BRIEF]


[Drawing.Context.closeFigure](../Drawing/Context/closeFigure.md) - ![__BRIEF]


[Drawing.Context.isPathStarted](../Drawing/Context/isPathStarted.md) - ![__BRIEF]


[Drawing.Context.moveTo](../Drawing/Context/moveTo.md) - ![__BRIEF]


[Drawing.Context.lineTo](../Drawing/Context/lineTo.md) - ![__BRIEF]


[Drawing.Context.ellipse](../Drawing/Context/ellipse.md) - ![__BRIEF]


[Drawing.Context.fillEllipse](../Drawing/Context/fillEllipse.md) - ![__BRIEF]


[Drawing.Context.ellipticArcTo](../Drawing/Context/ellipticArcTo.md) - ![__BRIEF]


[Drawing.Context.getLastArcEndPos](../Drawing/Context/getLastArcEndPos.md) - ![__BRIEF]


[Drawing.Context.arcToPos](../Drawing/Context/arcToPos.md) - ![__BRIEF]


[Drawing.Context.arcByAngleDeg](../Drawing/Context/arcByAngleDeg.md) - ![__BRIEF]


[Drawing.Context.roundRectFigure](../Drawing/Context/roundRectFigure.md) - ![__BRIEF]


[Drawing.Context.circle](../Drawing/Context/circle.md) - ![__BRIEF]


[Drawing.Context.fillCircle](../Drawing/Context/fillCircle.md) - ![__BRIEF]


[Drawing.Context.roundRect](../Drawing/Context/roundRect.md) - ![__BRIEF]


[Drawing.Context.fillRoundRect](../Drawing/Context/fillRoundRect.md) - ![__BRIEF]


[Drawing.Context.rect](../Drawing/Context/rect.md) - ![__BRIEF]


[Drawing.Context.fillRect](../Drawing/Context/fillRect.md) - ![__BRIEF]


[Drawing.Context.fillGradientRect](../Drawing/Context/fillGradientRect.md) - ![__BRIEF]


[Drawing.Context.fillGradientRoundRect](../Drawing/Context/fillGradientRoundRect.md) - ![__BRIEF]


[Drawing.Context.fillGradientCircle](../Drawing/Context/fillGradientCircle.md) - ![__BRIEF]


[Drawing.Context.textOut](../Drawing/Context/textOut.md) - ![__BRIEF]


