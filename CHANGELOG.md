# Postpass Changelog

## Unreleased

* Documentation improvements
* Internal refactoring
* drop "collection=false" option; you will now always get (Geo)JSON and there is no way around it
* drop "own_agg=false" option; we now always do the aggregation in the code, never in Postgres.
* rename "properties" in GeoJSON FeatureCollection to "postpass_properties" in order to be GeoJSON compliant
* rename "metadata" in JSON output to "postpass_properties" for consistency

## 0.2

## 0.1

* Initial release
