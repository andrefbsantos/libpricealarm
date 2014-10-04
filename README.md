# libpricealarm

Java alarms triggered when price crosses a boundary or surpasses given variation.

## Building
Run `mvn process-resources` once to make Maven aware of the plugins we use to download and install dependencies which are not in Maven repositories. For then on you can run `mvn package` to create a jar.

## Versioning
libpricealarm follows [Semantic Versioning](http://semver.org) with the API being the public methods and attributes provided by its classes.
