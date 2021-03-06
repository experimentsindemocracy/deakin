# Deakin

### Geographical data for all political and administrative regions in Australia.

Deakin is a crowd sourced collection of geographical datasets for all administrative and political regions in Australia designed for consumption by APIs and apps.

It's 2014 and we still don't have a single collection of political boundaries for all local, state, federal, and related administrative regions, in an easy to consume format. Neither do we have comprehensive data sets with sufficiently open licenses.

Deakin intends to fix that.

## Data

The repo is a simple collection of `.geojson` files.  Each file in the `data/` directory represents the jurisdiction of a single political authority, and contains a collection of boundary data for each division within that jurisdiction.

Files are named descriptively so that jurisdictions will group appropriately by the file system i.e. `au-qld-local-brisbane-city-council.geojson` and conform the the [geojson schema](http://geojson.org/geojson-spec.html).

**Warning** - I'm still exploring the best format for things so expect the structure and API to change!


## Usage

Coming soon.....

- how to access
- how to map
- how to find polity from address or geopoint
- how to convert formats


## Contributions

Yes please!!!  More info to come...

## Roadmap

Coming soon....


## License

The geographic data in Deakin has been collected from a variety of data sources.

Unless otherwise specified, the information in Deakin is licensed under a [Creative Commons Attribution 4.0 International License](LICENSE). You are free to share and adapt the material for any purpose, even commercially so long as you give appropriate credit in your source code, website, or publication.

This product (Deakin) incorporates data that is:

- © Commonwealth of Australia (Australian Electoral Commission) 2014
  
  The Data (Commonwealth Electoral Boundaries (various years)) has been used in Deakin with the permission of the Australian Electoral Commission. The Australian Electoral Commission has not evaluated the Data as altered and incorporated within Deakin, and therefore gives no warranty regarding its accuracy, completeness, currency or suitability for any particular purpose.