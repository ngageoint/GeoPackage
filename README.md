# GeoPackage
Main Page for the NGA [GeoPackage Libraries](http://ngageoint.github.io/GeoPackage/) providing [OGC GeoPackage](http://www.geopackage.org/) [spec](http://www.geopackage.org/spec) [implementations](http://www.geopackage.org/implementations.html)

A SDK that provides the ability to manage GeoPackage files providing read, write, import, export, share, and open support. Open GeoPackage files provide read and write access to features and tiles.

- [Java](http://ngageoint.github.io/geopackage-java/) – A Java library providing GeoPackage functionality and command line tools. Relies on [Core Java](https://github.com/ngageoint/geopackage-core-java).
  - [GitHub](https://github.com/ngageoint/geopackage-java)
  - [Javadoc](http://ngageoint.github.io/geopackage-java/docs/api/)
  - [The Central Repository](http://search.maven.org/#artifactdetails|mil.nga.geopackage|geopackage|3.0.0|jar)
  - [OGC](http://www.opengeospatial.org/resource/products/details/?pid=1487)

- [Android](http://ngageoint.github.io/geopackage-android/) - An Android SDK providing GeoPackage functionality and utilities to Android apps. Relies on [Core Java](https://github.com/ngageoint/geopackage-core-java).
  - [GitHub](https://github.com/ngageoint/geopackage-android)
  - [Javadoc](http://ngageoint.github.io/geopackage-android/docs/api/)
  - [The Central Repository](http://search.maven.org/#artifactdetails|mil.nga.geopackage|geopackage-android|3.0.0|aar)
  - [OGC](http://www.opengeospatial.org/resource/products/details/?pid=1488)

- [Android Map](http://ngageoint.github.io/geopackage-android-map/) - An Android Map SDK providing Google Map library implementations in addition to the inherited base [GeoPackage Android](https://github.com/ngageoint/geopackage-android/) functionality.
  - [GitHub](https://github.com/ngageoint/geopackage-android-map)
  - [Javadoc](http://ngageoint.github.io/geopackage-android-map/docs/api/)
  - [The Central Repository](http://search.maven.org/#artifactdetails|mil.nga.geopackage.map|geopackage-android-map|3.0.0|aar)
  - [Examples](https://github.com/ngageoint/geopackage-android-map/tree/master/docs/examples)

- [iOS](http://ngageoint.github.io/geopackage-ios/) - An iOS SDK providing GeoPackage functionality and utilities to iOS apps.
  - [GitHub](https://github.com/ngageoint/geopackage-ios)
  - [CocoaDocs](http://cocoadocs.org/docsets/geopackage-ios)
  - [CocoaPods](https://cocoapods.org/pods/geopackage-ios)
  - [OGC](http://www.opengeospatial.org/resource/products/details/?pid=1489)
  - [Examples](https://github.com/ngageoint/geopackage-ios/tree/master/docs/examples)

- [JS](http://ngageoint.github.io/geopackage-js/) - A JavaScript library providing GeoPackage functionality and utilities to node and web applications.
  - [GitHub](https://github.com/ngageoint/geopackage-js)
  - [GeoPackage Viewer](http://ngageoint.github.io/geopackage-js/)
  - [NPM](https://www.npmjs.com/package/@ngageoint/geopackage)
  - [OGC](http://www.opengeospatial.org/resource/products/details/?pid=1492)
  - [Examples](https://github.com/ngageoint/geopackage-js/tree/master/docs/examples)

- [Core Java](http://ngageoint.github.io/geopackage-core-java/) - A non-standalone library providing core GeoPackage functionality to the Java and Android libraries.
  - [GitHub](https://github.com/ngageoint/geopackage-core-java)
  - [Javadoc](http://ngageoint.github.io/geopackage-core-java/docs/api/)
  - [The Central Repository](http://search.maven.org/#artifactdetails|mil.nga.geopackage|geopackage-core|3.0.0|jar)

- [NGA Extensions](http://ngageoint.github.io/GeoPackage/docs/extensions/) - NGA extensions to the GeoPackage spec as defined by the OGC GeoPackage [extension mechanism](http://www.geopackage.org/spec/#_extension_mechanism) and defined using the [extension template](http://www.geopackage.org/spec/#extension_template).

# MapCache

An app that utilizes and demonstrates the functionality in the GeoPackage Mobile Libraries.

- [Android](http://ngageoint.github.io/geopackage-mapcache-android) - An Android app that can be built and installed from Android Studio or directly from the APK.
  - [GitHub](https://github.com/ngageoint/geopackage-mapcache-android)
  - [APK](https://github.com/ngageoint/geopackage-mapcache-android/releases/download/1.20/mapcache-1.20.apk)

- [iOS](http://ngageoint.github.io/geopackage-mapcache-ios) - An iOS app that can be built and installed from Xcode.
  - [GitHub](https://github.com/ngageoint/geopackage-mapcache-ios)
  - [Video](https://owncloud.devops.geointservices.io/index.php/s/Q9Z8wdP7d40empT)

# Simple Features

A non GeoPackage specific set of libraries based upon the [OGC Simple Feature Access](http://www.opengeospatial.org/standards/sfa) standard.

### Java

- [Simple Features Java](http://ngageoint.github.io/simple-features-java/) - Base library of geometry objects and utilities.
  - [GitHub](https://github.com/ngageoint/simple-features-java)
  - [Javadoc](http://ngageoint.github.io/simple-features-java/docs/api/)
  - [The Central Repository](http://search.maven.org/#artifactdetails|mil.nga|sf|2.0.0|jar)

- [Simple Features Well Known Binary Java](http://ngageoint.github.io/simple-features-wkb-java/) - Library for writing and reading Simple Feature Geometries to and from Well-Known Binary.
  - [GitHub](https://github.com/ngageoint/simple-features-wkb-java)
  - [Javadoc](http://ngageoint.github.io/simple-features-wkb-java/docs/api/)
  - [The Central Repository](http://search.maven.org/#artifactdetails|mil.nga.sf|sf-wkb|2.0.0|jar)

- [Simple Features GeoJSON Java](http://ngageoint.github.io/simple-features-geojson-java/) - Library for writing and reading Simple Feature Geometries to and from GeoJSON.
  - [GitHub](https://github.com/ngageoint/simple-features-geojson-java)
  - [Javadoc](http://ngageoint.github.io/simple-features-geojson-java/docs/api/)
  - [The Central Repository](http://search.maven.org/#artifactdetails|mil.nga.sf|sf-geojson|2.0.0|jar)

- [Simple Features Projection Java](http://ngageoint.github.io/simple-features-proj-java/) - Library for performing projection conversions between Simple Feature Geometries.
  - [GitHub](https://github.com/ngageoint/simple-features-proj-java)
  - [Javadoc](http://ngageoint.github.io/simple-features-proj-java/docs/api/)
  - [The Central Repository](http://search.maven.org/#artifactdetails|mil.nga.sf|sf-proj|2.0.0|jar)

### iOS

- [Simple Features iOS](http://ngageoint.github.io/simple-features-ios/) - Base library of geometry objects and utilities.
  - [GitHub](https://github.com/ngageoint/simple-features-ios)
  - [CocoaDocs](http://cocoadocs.org/docsets/sf-ios)
  - [CocoaPods](https://cocoapods.org/pods/sf-ios)

- [Simple Features Well Known Binary iOS](http://ngageoint.github.io/simple-features-wkb-ios/) - Library for writing and reading Simple Feature Geometries to and from Well-Known Binary.
  - [GitHub](https://github.com/ngageoint/simple-features-wkb-ios)
  - [CocoaDocs](http://cocoadocs.org/docsets/sf-wkb-ios)
  - [CocoaPods](https://cocoapods.org/pods/sf-wkb-ios)

- [Simple Features Projection iOS](http://ngageoint.github.io/simple-features-proj-ios/) - Library for performing projection conversions between Simple Feature Geometries.
  - [GitHub](https://github.com/ngageoint/simple-features-proj-ios)
  - [CocoaDocs](http://cocoadocs.org/docsets/sf-proj-ios)
  - [CocoaPods](https://cocoapods.org/pods/sf-proj-ios)

# TIFF

A non GeoPackage specific library for reading and writing Tagged Image File Format files.

- [Java](http://ngageoint.github.io/tiff-java/) - A Java library providing Tagged Image File Format functionality.
  - [GitHub](https://github.com/ngageoint/tiff-java)
  - [Javadoc](http://ngageoint.github.io/tiff-java/docs/api/)
  - [The Central Repository](http://search.maven.org/#artifactdetails|mil.nga|tiff|2.0.0|jar)

- [iOS](http://ngageoint.github.io/tiff-ios/) - An iOS library providing Tagged Image File Format functionality.
  - [GitHub](https://github.com/ngageoint/tiff-ios)
  - [CocoaDocs](http://cocoadocs.org/docsets/tiff-ios)
  - [CocoaPods](https://cocoapods.org/pods/tiff-ios)
