## Running Notes, 20141005

 * `Series()`: one-dimensional array with optional **index** of labels (pp. 112-115)
    * **datatypes**
      * `Series.values` => `array` datatype
      * `Series.index` => `Int64Index` datatype
      * `Series([...], index=[...])` => `Index` ("**object**") datatype, associative array
      * `Series(dict)`: convert Python `dict` to `Series`
    * **missing data**: `NaN marks missing data; detected by `isnull(Series)`; reverse with `notnull(Series)`
    * **data alignment**: `Series` + `Series`: natural join of keys ("data alignment")
    * **name**: `Series` and `Series.index` have assignable `name` attribute
 * `DataFrame()`
 


[end]