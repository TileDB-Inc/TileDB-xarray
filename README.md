<a href="https://tiledb.com"><img src="https://github.com/TileDB-Inc/TileDB/raw/dev/doc/source/_static/tiledb-logo_color_no_margin_@4x.png" alt="TileDB logo" width="400"></a>

# TileDB-xarray

This library provides a TileDB backend engine for xarray `open_dataset` function.

Example usage:

```python
import xarray as xr
dataset = xr.open_dataset(
    "tiledb_array_uri",
    backend_kwargs={"key": key, "timestamp": timestamp},
    engine="tiledb"
    )
```

## Quick Links

* TileDB
  * [Homepage](https://tiledb.com)
  * [Documentation](https://docs.tiledb.com/main/)
  * [Forum](https://forum.tiledb.io/)
  * [Organization](https://github.com/TileDB-Inc/)

* xarray
  * [Documentation](http://xarray.pydata.org/en/stable/)
  * [GitHub](https://github.com/pydata/xarray/)
