## Running Notes, 20141005

 * `Series()`: like ordered Python `dict` (pp. 112-115)
    * `Series.values` => `array` datatype
    * `Series.index` => `Int64Index` datatype
    * `Series([...], index=[...])` => `Index` ("**object**") datatype, associative array
    * `Series(dict)`: convert dict to Series
    * `NaN marks missing data; detected by `isnull(Series)`; reverse with `notnull(Series)`
    * `Series` + `Series`: natural join of keys ("**data alignment**")
 * `DataFrame()`
 


[end]