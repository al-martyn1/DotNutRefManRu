## Drawing.Coords class


```lua
class Drawing.Coords
{
    // Member Fields

    x; // float
    y; // float


    // Functions

    constructor( x   // any_integral
               , y   // any_integral
               )

    function _add( c   // Drawing.Coords
                 )
    // returns: Drawing.Coords

    function _sub( c   // Drawing.Coords
                 )
    // returns: Drawing.Coords

    function _unm( c   // Drawing.Coords
                 )
    // returns: Drawing.Coords

    function _mul( c   // Drawing.Coords
                 )
    // returns: Drawing.Coords

    function _div( c   // Drawing.Coords
                 )
    // returns: Drawing.Coords

    function tostring()
    // returns: string

    function _tostring()
    // returns: string


} // class Drawing.Coords
```



### Member fields

**x** (**float**) - ![x]

**y** (**float**) - ![y]


### Methods


[Drawing.Coords.constructor](../Drawing/Coords/constructor.md) - ![__BRIEF]


**_add** - Support for the 'plus' ('+') operator. See [squirrel manual](http://squirrel-lang.org/squirreldoc/reference/language/metamethods.html#add) for details.


**_sub** - Support for the 'minus' ('-') operator. See [squirrel manual](http://squirrel-lang.org/squirreldoc/reference/language/metamethods.html#sub) for details.


**_unm** - Support for the 'unary minus' ('-') operator. See [squirrel manual](http://squirrel-lang.org/squirreldoc/reference/language/metamethods.html#unm) for details.


**_mul** - Support for the 'multiply' ('*') operator. See [squirrel manual](http://squirrel-lang.org/squirreldoc/reference/language/metamethods.html#mul) for details.


**_div** - Support for the 'divide' ('/') operator. See [squirrel manual](http://squirrel-lang.org/squirreldoc/reference/language/metamethods.html#div) for details.


**tostring** - Convert the value to string and returns it, see [squirrel manual](http://squirrel-lang.org/squirreldoc/reference/language/builtin_functions.html#string) for details. Exposed for compatibility with built-in types. The toString() function has also been implemented to comply with camelCase naming convetions.


**_tostring** - Support for the 'tostring' ('tostring') conversion method. See [squirrel manual](http://squirrel-lang.org/squirreldoc/reference/language/metamethods.html#tostring) for details.


