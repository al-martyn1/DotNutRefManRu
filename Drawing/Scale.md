## Drawing.Scale class


```lua
class Drawing.Scale
{
    // Member Fields

    x; // float
    y; // float


    // Functions

    constructor( x   // any_integral
               , y   // any_integral
               )

    function _add( c   // Drawing.Scale
                 )
    // returns: Drawing.Scale

    function _sub( c   // Drawing.Scale
                 )
    // returns: Drawing.Scale

    function _unm( c   // Drawing.Scale
                 )
    // returns: Drawing.Scale

    function _mul( c   // Drawing.Scale
                 )
    // returns: Drawing.Scale

    function _div( c   // Drawing.Scale
                 )
    // returns: Drawing.Scale

    function tostring()
    // returns: string

    function _tostring()
    // returns: string


} // class Drawing.Scale
```



### Member fields

**x** (**float**) - ![x]

**y** (**float**) - ![y]


### Methods


[Drawing.Scale.constructor](../Drawing/Scale/constructor.md) - ![__BRIEF]


**_add** - Support for the 'plus' ('+') operator.


**_sub** - Support for the 'minus' ('-') operator.


**_unm** - Support for the 'unary minus' ('-') operator.


**_mul** - Support for the 'multiply' ('*') operator.


**_div** - Support for the 'divide' ('/') operator.


[Drawing.Scale.tostring](../Drawing/Scale/tostring.md) - ![__BRIEF]


**_tostring** - Support for the 'tostring' ('tostring') conversion method.


