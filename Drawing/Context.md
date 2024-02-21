## Drawing.Context класс


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
                        , markerSize   // integer|float|string
                        )
    // returns: bool

    function markersClear()
    // returns: bool

    function markersDraw()
    // returns: bool

    function markersDrawEx( penId   // integer
                          )
    // returns: bool

    function markerSetDefSize( markerSize   // integer|float|string
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

    function setPenScale( scale   // integer|float|string
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
                         , height       // integer|float|string
                         )
    // returns: integer

    function createOrFindFont( fontParams   // Drawing.FontParams
                             )
    // returns: integer

    function createOrFindFontEx( fontParams   // Drawing.FontParams
                               , height       // integer|float|string
                               )
    // returns: integer

    function selectFont( fontId   // integer
                       )
    // returns: integer

    function selectNewFont( fontParams   // Drawing.FontParams
                          )
    // returns: integer

    function selectNewFontEx( fontParams   // Drawing.FontParams
                            , height       // integer|float|string
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
                          , angle       // integer|float|string
                          )
    // returns: bool

    function roundRectFigure( cornersR   // integer|float|string
                            , points     // array of Drawing.Coords
                            )
    // returns: bool

    function circle( centerPos   // Drawing.Coords
                   , r           // integer|float|string
                   )
    // returns: bool

    function fillCircle( centerPos   // Drawing.Coords
                       , r           // integer|float|string
                       , drawFrame   // bool
                       )
    // returns: bool

    function roundRect( cornersR      // integer|float|string
                      , leftTop       // Drawing.Coords
                      , rightBottom   // Drawing.Coords
                      )
    // returns: bool

    function fillRoundRect( cornersR      // integer|float|string
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

    function fillGradientRoundRect( cornersR         // integer|float|string
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
                               , r                // integer|float|string
                               , gradientParams   // Drawing.GradientParams
                               , excludeFrame     // bool
                               )
    // returns: bool

    function textOut( pos    // Drawing.Coords
                    , text   // string
                    )
    // returns: bool

    function textOutWithFontAndColor( pos      // Drawing.Coords
                                    , fontId   // integer
                                    , clr      // Drawing.Color
                                    , text     // string
                                    )
    // returns: bool

    function drawTextColored( startPos    // Drawing.Coords
                            , widthLim    // integer|float|string
                            , flags       // DrawTextFlags
                            , text        // string
                            , stopChars   // string
                            , colors      // array of Drawing.Color
                            , bkColors    // array of Drawing.Color
                            , fontId      // integer
                            )
    // returns: bool

    function drawParaColored( startPos           // Drawing.Coords
                            , limits             // Drawing.Coords
                            , lineSpacing        // integer|float|string
                            , paraIndent         // integer|float|string
                            , tabSize            // integer|float|string
                            , flags              // DrawTextFlags
                            , horAlign           // Drawing.HorAlign
                            , vertAlign          // Drawing.VertAlign
                            , text               // string
                            , colors             // array of Drawing.Color
                            , bkColors           // array of Drawing.Color
                            , tabStopPositions   // array of integer|float|string
                            , fontId             // integer
                            )
    // returns: bool

    function drawMultiParasColored( startPos           // Drawing.Coords
                                  , limits             // Drawing.Coords
                                  , lineSpacing        // integer|float|string
                                  , paraIndent         // integer|float|string
                                  , tabSize            // integer|float|string
                                  , flags              // DrawTextFlags
                                  , horAlign           // Drawing.HorAlign
                                  , vertAlign          // Drawing.VertAlign
                                  , text               // string
                                  , colors             // array of Drawing.Color
                                  , bkColors           // array of Drawing.Color
                                  , tabStopPositions   // array of integer|float|string
                                  , paraColors         // array of Drawing.Color
                                  , paraBkColors       // array of Drawing.Color
                                  , fontId             // integer
                                  )
    // returns: bool

    function polyQuadraticBezier( cp1   // Drawing.Coords
                                , cp2   // Drawing.Coords
                                , cp3   // Drawing.Coords
                                )
    // returns: bool

    function polyQuadraticBezierTo( cp2   // Drawing.Coords
                                  , cp3   // Drawing.Coords
                                  )
    // returns: bool

    function polyCubicBezier( cp1   // Drawing.Coords
                            , cp2   // Drawing.Coords
                            , cp3   // Drawing.Coords
                            , cp4   // Drawing.Coords
                            )
    // returns: bool

    function polyCubicBezierTo( cp2   // Drawing.Coords
                              , cp3   // Drawing.Coords
                              , cp4   // Drawing.Coords
                              )
    // returns: bool

    function polyCubicBeziers( points   // array of Drawing.Coords
                             )
    // returns: bool

    function polyCubicBeziersTo( points   // array of Drawing.Coords
                               )
    // returns: bool

    function polyQuadraticBeziers( points   // array of Drawing.Coords
                                 )
    // returns: bool

    function polyQuadraticBeziersTo( points   // array of Drawing.Coords
                                   )
    // returns: bool

    function distanceBetween( pos1   // Drawing.Coords
                            , pos2   // Drawing.Coords
                            )
    // returns: float

    function reflectPoint( pos          // Drawing.Coords
                         , relativeTo   // Drawing.Coords
                         )
    // returns: Drawing.Coords

    function drawImageSimple( imgListWrapper   // Drawing.ImageList
                            , idx              // integer
                            , pos              // Drawing.Coords
                            )
    // returns: bool

    function drawImageSimpleEx( imgListWrapper   // Drawing.ImageList
                              , idx              // integer
                              , pos              // Drawing.Coords
                              , imgPartLeftTop   // Drawing.ImageSize
                              , imgPartSize      // Drawing.ImageSize
                              )
    // returns: bool


} // class Drawing.Context
```



### Методы


[flushBits](../Drawing/Context/flushBits.md) - ![__BRIEF]


[setDrawingPrecise](../Drawing/Context/setDrawingPrecise.md) - ![__BRIEF]


[getDrawingPrecise](../Drawing/Context/getDrawingPrecise.md) - ![__BRIEF]


[getRawSize](../Drawing/Context/getRawSize.md) - ![__BRIEF]


[getSize](../Drawing/Context/getSize.md) - ![__BRIEF]


[distanceBetween](../Drawing/Context/distanceBetween.md) - ![__BRIEF]


[reflectPoint](../Drawing/Context/reflectPoint.md) - ![__BRIEF]


[setCollectMarkers](../Drawing/Context/setCollectMarkers.md) - ![__BRIEF]


[getCollectMarkers](../Drawing/Context/getCollectMarkers.md) - ![__BRIEF]


[markerAdd](../Drawing/Context/markerAdd.md) - ![__BRIEF]


[markerAddEx](../Drawing/Context/markerAddEx.md) - ![__BRIEF]


[markersClear](../Drawing/Context/markersClear.md) - ![__BRIEF]


[markersDraw](../Drawing/Context/markersDraw.md) - ![__BRIEF]


[markersDrawEx](../Drawing/Context/markersDrawEx.md) - ![__BRIEF]


[markerSetDefSize](../Drawing/Context/markerSetDefSize.md) - ![__BRIEF]


[markerGetDefSize](../Drawing/Context/markerGetDefSize.md) - ![__BRIEF]


[setSmoothingMode](../Drawing/Context/setSmoothingMode.md) - ![__BRIEF]


[getSmoothingMode](../Drawing/Context/getSmoothingMode.md) - ![__BRIEF]


[setTextColor](../Drawing/Context/setTextColor.md) - ![__BRIEF]


[getTextColor](../Drawing/Context/getTextColor.md) - ![__BRIEF]


[setBkColor](../Drawing/Context/setBkColor.md) - ![__BRIEF]


[getBkColor](../Drawing/Context/getBkColor.md) - ![__BRIEF]


[setBkMode](../Drawing/Context/setBkMode.md) - ![__BRIEF]


[getBkMode](../Drawing/Context/getBkMode.md) - ![__BRIEF]


[getDialigBaseUnits](../Drawing/Context/getDialigBaseUnits.md) - ![__BRIEF]


[mapRawToLogicPos](../Drawing/Context/mapRawToLogicPos.md) - ![__BRIEF]


[mapRawToLogicSize](../Drawing/Context/mapRawToLogicSize.md) - ![__BRIEF]


[getPixelSize](../Drawing/Context/getPixelSize.md) - ![__BRIEF]


[getScaledPos](../Drawing/Context/getScaledPos.md) - ![__BRIEF]


[getScaledSize](../Drawing/Context/getScaledSize.md) - ![__BRIEF]


[setOffset](../Drawing/Context/setOffset.md) - ![__BRIEF]


[getOffset](../Drawing/Context/getOffset.md) - ![__BRIEF]


[setScale](../Drawing/Context/setScale.md) - ![__BRIEF]


[getScale](../Drawing/Context/getScale.md) - ![__BRIEF]


[setPenScale](../Drawing/Context/setPenScale.md) - ![__BRIEF]


[getPenScale](../Drawing/Context/getPenScale.md) - ![__BRIEF]


[createSolidPen](../Drawing/Context/createSolidPen.md) - ![__BRIEF]


[selectPen](../Drawing/Context/selectPen.md) - ![__BRIEF]


[selectNewSolidPen](../Drawing/Context/selectNewSolidPen.md) - ![__BRIEF]


[getCurPen](../Drawing/Context/getCurPen.md) - ![__BRIEF]


[getPenColor](../Drawing/Context/getPenColor.md) - ![__BRIEF]


[getPenParams](../Drawing/Context/getPenParams.md) - ![__BRIEF]


[setDefaultCosmeticPen](../Drawing/Context/setDefaultCosmeticPen.md) - ![__BRIEF]


[getDefaultCosmeticPen](../Drawing/Context/getDefaultCosmeticPen.md) - ![__BRIEF]


[createSolidBrush](../Drawing/Context/createSolidBrush.md) - ![__BRIEF]


[selectBrush](../Drawing/Context/selectBrush.md) - ![__BRIEF]


[selectNewSolidBrush](../Drawing/Context/selectNewSolidBrush.md) - ![__BRIEF]


[getCurBrush](../Drawing/Context/getCurBrush.md) - ![__BRIEF]


[createFont](../Drawing/Context/createFont.md) - ![__BRIEF]


[createFontEx](../Drawing/Context/createFontEx.md) - ![__BRIEF]


[createOrFindFont](../Drawing/Context/createOrFindFont.md) - ![__BRIEF]


[createOrFindFontEx](../Drawing/Context/createOrFindFontEx.md) - ![__BRIEF]


[selectFont](../Drawing/Context/selectFont.md) - ![__BRIEF]


[selectNewFont](../Drawing/Context/selectNewFont.md) - ![__BRIEF]


[selectNewFontEx](../Drawing/Context/selectNewFontEx.md) - ![__BRIEF]


[createFontWithFace](../Drawing/Context/createFontWithFace.md) - ![__BRIEF]


[createOrFindFontWithFace](../Drawing/Context/createOrFindFontWithFace.md) - ![__BRIEF]


[getCurFont](../Drawing/Context/getCurFont.md) - ![__BRIEF]


[getFontParamsById](../Drawing/Context/getFontParamsById.md) - ![__BRIEF]


[beginPath](../Drawing/Context/beginPath.md) - ![__BRIEF]


[beginPathFrom](../Drawing/Context/beginPathFrom.md) - ![__BRIEF]


[endPath](../Drawing/Context/endPath.md) - ![__BRIEF]


[closeFigure](../Drawing/Context/closeFigure.md) - ![__BRIEF]


[isPathStarted](../Drawing/Context/isPathStarted.md) - ![__BRIEF]


[moveTo](../Drawing/Context/moveTo.md) - ![__BRIEF]


[lineTo](../Drawing/Context/lineTo.md) - ![__BRIEF]


[ellipse](../Drawing/Context/ellipse.md) - ![__BRIEF]


[fillEllipse](../Drawing/Context/fillEllipse.md) - ![__BRIEF]


[ellipticArcTo](../Drawing/Context/ellipticArcTo.md) - ![__BRIEF]


[getLastArcEndPos](../Drawing/Context/getLastArcEndPos.md) - ![__BRIEF]


[arcToPos](../Drawing/Context/arcToPos.md) - ![__BRIEF]


[arcByAngleDeg](../Drawing/Context/arcByAngleDeg.md) - ![__BRIEF]


[roundRectFigure](../Drawing/Context/roundRectFigure.md) - ![__BRIEF]


[circle](../Drawing/Context/circle.md) - ![__BRIEF]


[fillCircle](../Drawing/Context/fillCircle.md) - ![__BRIEF]


[roundRect](../Drawing/Context/roundRect.md) - ![__BRIEF]


[fillRoundRect](../Drawing/Context/fillRoundRect.md) - ![__BRIEF]


[rect](../Drawing/Context/rect.md) - ![__BRIEF]


[fillRect](../Drawing/Context/fillRect.md) - ![__BRIEF]


[fillGradientRect](../Drawing/Context/fillGradientRect.md) - ![__BRIEF]


[fillGradientRoundRect](../Drawing/Context/fillGradientRoundRect.md) - ![__BRIEF]


[fillGradientCircle](../Drawing/Context/fillGradientCircle.md) - ![__BRIEF]


[textOut](../Drawing/Context/textOut.md) - ![__BRIEF]


[textOutWithFontAndColor](../Drawing/Context/textOutWithFontAndColor.md) - ![__BRIEF]


[drawTextColored](../Drawing/Context/drawTextColored.md) - ![__BRIEF]


[drawParaColored](../Drawing/Context/drawParaColored.md) - ![__BRIEF]


[drawMultiParasColored](../Drawing/Context/drawMultiParasColored.md) - ![__BRIEF]


[polyQuadraticBezier](../Drawing/Context/polyQuadraticBezier.md) - ![__BRIEF]


[polyQuadraticBezierTo](../Drawing/Context/polyQuadraticBezierTo.md) - ![__BRIEF]


[polyCubicBezier](../Drawing/Context/polyCubicBezier.md) - ![__BRIEF]


[polyCubicBezierTo](../Drawing/Context/polyCubicBezierTo.md) - ![__BRIEF]


[polyCubicBeziers](../Drawing/Context/polyCubicBeziers.md) - ![__BRIEF]


[polyCubicBeziersTo](../Drawing/Context/polyCubicBeziersTo.md) - ![__BRIEF]


[polyQuadraticBeziers](../Drawing/Context/polyQuadraticBeziers.md) - ![__BRIEF]


[polyQuadraticBeziersTo](../Drawing/Context/polyQuadraticBeziersTo.md) - ![__BRIEF]


[distanceBetween](../Drawing/Context/distanceBetween.md) - ![__BRIEF]


[reflectPoint](../Drawing/Context/reflectPoint.md) - ![__BRIEF]


[drawImageSimple](../Drawing/Context/drawImageSimple.md) - ![__BRIEF]


[drawImageSimpleEx](../Drawing/Context/drawImageSimpleEx.md) - ![__BRIEF]


