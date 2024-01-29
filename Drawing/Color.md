## ![class-section-title]


```lua
class Drawing.Color
{
    // Member Fields

    r; // integer
    g; // integer
    b; // integer
    a; // integer


    // Functions

    constructor( intValOrNameStr   // any_integral
               )

    static
    function fromRgb( r   // integer
                    , g   // integer
                    , b   // integer
                    )
    // returns: Drawing.Color

    static
    function fromUnsigned( u   // integer
                         )
    // returns: Drawing.Color

    static
    function fromInt( u   // integer
                    )
    // returns: Drawing.Color

    static
    function fromInteger( u   // integer
                        )
    // returns: Drawing.Color

    static
    function fromString( nameOrIntStr   // string
                       )
    // returns: Drawing.Color

    function toUnsigned()
    // returns: integer

    function toInt()
    // returns: integer

    function tointeger()
    // returns: integer

    function tofloat()
    // returns: float

    function tostring()
    // returns: string

    function _tostring()
    // returns: string


} // class Drawing.Color
```



### ![class-members-section-title]

**r** (**integer**) - ![r]

**g** (**integer**) - ![g]

**b** (**integer**) - ![b]

**a** (**integer**) - ![a]


### ![class-methods-section-title]


[Drawing.Color.constructor](../Drawing/Color/constructor.md) - ![__BRIEF]


[Drawing.Color.fromRgb](../Drawing/Color/fromRgb.md) - ![__BRIEF]


[Drawing.Color.fromUnsigned](../Drawing/Color/fromUnsigned.md) - ![__BRIEF]


[Drawing.Color.fromInt](../Drawing/Color/fromInt.md) - ![__BRIEF]


[Drawing.Color.fromInteger](../Drawing/Color/fromInteger.md) - ![__BRIEF]


[Drawing.Color.fromString](../Drawing/Color/fromString.md) - ![__BRIEF]


[Drawing.Color.toUnsigned](../Drawing/Color/toUnsigned.md) - ![__BRIEF]


[Drawing.Color.toInt](../Drawing/Color/toInt.md) - ![__BRIEF]


**tointeger** - ![tointeger]


**tofloat** - ![tofloat]


**tostring** - ![tostring]


**_tostring** - ![_tostring]


