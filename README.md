# whosonfirst-data-postalcode-ca

Who's On First postal code data for the Canada (CA).

## Important

As of this writing most but _not all_ postal codes have geometries. That said only about 1,600 records have `Polygon` geometries. The remaining (~800K) postal codes have all been assigned an approximate geometry, specifically the centroid for their containing `FSA`.

For example the geometry for the postal code [T6R 2R3](https://github.com/whosonfirst-data/whosonfirst-data-postalcode-ca/blob/master/data/554/865/797/554865797.geojson) will be the centroid for the postal code [T6R](https://github.com/whosonfirst-data/whosonfirst-data-postalcode-ca/blob/master/data/504/804/689/504804689.geojson). Additionally these records (with derived coordinates) will contain a `mz:is_approximate=1` property.

This work is still in the early stages and some important ancillary artifacts normally found in Who's On First data repositories (like `meta` files) have not been created yet.

## License

https://github.com/whosonfirst/whosonfirst-data/blob/master/LICENSE.md

## See also

* https://whosonfirst.mapzen.com
* https://github.com/whosonfirst-data/whosonfirst-data-postalcode

* http://www12.statcan.gc.ca/census-recensement/2011/geo/bound-limit/bound-limit-2011-eng.cfm
* http://open.canada.ca/en/suggested-datasets/postal-code-database