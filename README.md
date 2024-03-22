Table of Contents
=================

* [MapCache](#mapcache)
* [GeoPackage](#geopackage)
* [Simple Features](#simple-features)
* [Projections](#projections)
* [Coordinate Reference Systems](#coordinate-reference-systems)
* [TIFF](#tiff)
* [OGC API](#ogc-api)
* [Color](#color)
* [Grid](#grid)

#### Dependency Graphs

- [![Java & Android](https://img.shields.io/static/v1?label=&logo=github&color=informational&message=Java%20%26%20Android)](https://github.com/ngageoint/GeoPackage/blob/master/DependencyJavaAndroid.md)
- [![iOS](https://img.shields.io/static/v1?label=&logo=github&color=informational&message=iOS)](https://github.com/ngageoint/GeoPackage/blob/master/DependencyiOS.md)
- [![JavaScript](https://img.shields.io/static/v1?label=&logo=github&color=informational&message=JavaScript)](https://github.com/ngageoint/GeoPackage/blob/master/DependencyJavaScript.md)

# MapCache

An app that utilizes and demonstrates the functionality in the GeoPackage Mobile Libraries.

- [Android](http://ngageoint.github.io/geopackage-mapcache-android) - An Android app that can be built and installed from Android Studio or directly from the APK.
  - [![GitHub](https://img.shields.io/github/release/ngageoint/geopackage-mapcache-android.svg?label=GitHub&sort=semver)](https://github.com/ngageoint/geopackage-mapcache-android) [![Build](https://github.com/ngageoint/geopackage-mapcache-android/workflows/Build/badge.svg)](https://github.com/ngageoint/geopackage-mapcache-android/actions/workflows/build.yml)
  - [![Google Play](https://img.shields.io/static/v1?label=&logo=Google-Play&color=informational&message=Google%20Play)](https://play.google.com/store/apps/details?id=mil.nga.mapcache)
  - [![Legacy APK](https://img.shields.io/static/v1?label=&logo=Android&color=informational&message=Legacy%20APK)](https://ngageoint.github.io/geopackage-mapcache-android/legacy/mapcache.zip)

- [iOS](http://ngageoint.github.io/geopackage-mapcache-ios) - An iOS app that can be built and installed from Xcode.
  - [![GitHub](https://img.shields.io/github/release/ngageoint/geopackage-mapcache-ios.svg?label=GitHub&sort=semver)](https://github.com/ngageoint/geopackage-mapcache-ios) [![Build Archive](https://github.com/ngageoint/geopackage-mapcache-ios/workflows/Build%20Archive/badge.svg)](https://github.com/ngageoint/geopackage-mapcache-ios/actions/workflows/build-archive.yml)
  - [![App Store](https://img.shields.io/static/v1?label=&logo=Apple&color=informational&message=App%20Store)](https://apps.apple.com/us/app/mapcache-by-nga/id1477252454)

- Desktop - A desktop application running in Electron, built for Windows, Linux, and MacOS.
  - [![GitHub](https://img.shields.io/github/release/ngageoint/mapcache-electron.svg?label=GitHub&sort=semver)](https://github.com/ngageoint/mapcache-electron)
  - [![Release](https://img.shields.io/github/release/ngageoint/mapcache-electron.svg?label=Release&sort=semver)](https://github.com/ngageoint/mapcache-electron/releases/latest)

# GeoPackage

Main Page for the NGA [GeoPackage Libraries](http://ngageoint.github.io/GeoPackage/) providing [OGC GeoPackage](http://www.geopackage.org/) [spec](http://www.geopackage.org/spec) [implementations](http://www.geopackage.org/implementations.html)

An [OGC Certified](https://portal.ogc.org/public_ogc/compliance/products_compliant2.php?org_match=US%20National%20Geospatial-Intelligence%20Agency%20(NGA)) SDK that provides the ability to manage GeoPackage files providing read, write, import, export, share, and open support. Open GeoPackage files provide read and write access to features and tiles.

- [Java](http://ngageoint.github.io/geopackage-java/) – A Java library providing GeoPackage functionality and command line tools. Relies on [Core Java](https://github.com/ngageoint/geopackage-core-java).
  - [![GitHub](https://img.shields.io/github/release/ngageoint/geopackage-java.svg?label=GitHub&sort=semver)](https://github.com/ngageoint/geopackage-java) [![Build & Test](https://github.com/ngageoint/geopackage-java/workflows/Build%20&%20Test/badge.svg)](https://github.com/ngageoint/geopackage-java/actions/workflows/build-test.yml)
  - [![Javadoc](https://img.shields.io/maven-central/v/mil.nga.geopackage/geopackage.svg?label=Javadoc&colorB=39be00)](http://ngageoint.github.io/geopackage-java/docs/api/)
  - [![The Central Repository](https://img.shields.io/maven-central/v/mil.nga.geopackage/geopackage.svg?label=The%20Central%20Repository)](https://search.maven.org/artifact/mil.nga.geopackage/geopackage)
  - [![OGC](https://img.shields.io/badge/OGC-v6-blue)](https://www.ogc.org/resource/products/details/?pid=1731)

- [Android](http://ngageoint.github.io/geopackage-android/) - An Android SDK providing GeoPackage functionality and utilities to Android apps. Relies on [Core Java](https://github.com/ngageoint/geopackage-core-java).
  - [![GitHub](https://img.shields.io/github/release/ngageoint/geopackage-android.svg?label=GitHub&sort=semver)](https://github.com/ngageoint/geopackage-android) [![Build Artifacts](https://github.com/ngageoint/geopackage-android/workflows/Build%20Artifacts/badge.svg)](https://github.com/ngageoint/geopackage-android/actions/workflows/build-artifacts.yml)
[![Test](https://github.com/ngageoint/geopackage-android/workflows/Test/badge.svg)](https://github.com/ngageoint/geopackage-android/actions/workflows/test.yml)
  - [![Javadoc](https://img.shields.io/maven-central/v/mil.nga.geopackage/geopackage-android.svg?label=Javadoc&colorB=39be00)](http://ngageoint.github.io/geopackage-android/docs/api/)
  - [![The Central Repository](https://img.shields.io/maven-central/v/mil.nga.geopackage/geopackage-android.svg?label=The%20Central%20Repository)](https://search.maven.org/artifact/mil.nga.geopackage/geopackage-android)
  - [![OGC](https://img.shields.io/badge/OGC-v6-blue)](https://www.ogc.org/resource/products/details/?pid=1732)

- [Android Map](http://ngageoint.github.io/geopackage-android-map/) - An Android Map SDK providing Google Map library implementations in addition to the inherited base [GeoPackage Android](https://github.com/ngageoint/geopackage-android/) functionality.
  - [![GitHub](https://img.shields.io/github/release/ngageoint/geopackage-android-map.svg?label=GitHub&sort=semver)](https://github.com/ngageoint/geopackage-android-map) [![Build Artifacts](https://github.com/ngageoint/geopackage-android-map/workflows/Build%20Artifacts/badge.svg)](https://github.com/ngageoint/geopackage-android-map/actions/workflows/build-artifacts.yml)
[![Test](https://github.com/ngageoint/geopackage-android-map/workflows/Test/badge.svg)](https://github.com/ngageoint/geopackage-android-map/actions/workflows/test.yml)
  - [![Javadoc](https://img.shields.io/maven-central/v/mil.nga.geopackage.map/geopackage-android-map.svg?label=Javadoc&colorB=39be00)](http://ngageoint.github.io/geopackage-android-map/docs/api/)
  - [![The Central Repository](https://img.shields.io/maven-central/v/mil.nga.geopackage.map/geopackage-android-map.svg?label=The%20Central%20Repository)](https://search.maven.org/artifact/mil.nga.geopackage.map/geopackage-android-map)
  - [![Examples](https://img.shields.io/static/v1?label=&logo=Android&color=informational&message=Examples)](https://github.com/ngageoint/geopackage-android-map/tree/master/docs/examples)

- [iOS](http://ngageoint.github.io/geopackage-ios/) - An iOS SDK providing GeoPackage functionality and utilities to iOS apps.
  - [![GitHub](https://img.shields.io/github/release/ngageoint/geopackage-ios.svg?label=GitHub&sort=semver)](https://github.com/ngageoint/geopackage-ios) [![Build & Test](https://github.com/ngageoint/geopackage-ios/workflows/Build%20&%20Test/badge.svg)](https://github.com/ngageoint/geopackage-ios/actions/workflows/build-test.yml)
  - [![Appledoc](https://img.shields.io/github/release/ngageoint/geopackage-ios.svg?label=Appledoc&colorB=39be00)](http://ngageoint.github.io/geopackage-ios/docs/api)
  - [![CocoaPods](https://img.shields.io/cocoapods/v/geopackage-ios.svg?label=CocoaPods)](https://cocoapods.org/pods/geopackage-ios)
  - [![OGC](https://img.shields.io/badge/OGC-v8-blue)](https://www.ogc.org/resource/products/details/?pid=1819) [![OGC](https://www.ogc.org/pub/www/files/favicon.ico) Official Reference Implementation](https://github.com/opengeospatial/cite/wiki/Reference-Implementations)
  - [![Examples](https://img.shields.io/static/v1?label=&logo=iOS&color=informational&message=Examples)](https://github.com/ngageoint/geopackage-ios/tree/master/docs/examples)

- [JavaScript](http://ngageoint.github.io/geopackage-js/) - A JavaScript library providing GeoPackage functionality and utilities to node and web applications.
  - [![GitHub](https://img.shields.io/github/release/ngageoint/geopackage-js.svg?label=GitHub&sort=semver)](https://github.com/ngageoint/geopackage-js) [![Build and Run Tests](https://github.com/ngageoint/geopackage-js/workflows/Build%20and%20Run%20Tests/badge.svg)](https://github.com/ngageoint/geopackage-js/actions/workflows/run-tests.yml)
  - [![GeoPackage Viewer](https://img.shields.io/static/v1?label=&logo=JavaScript&color=informational&message=GeoPackage%20Viewer)](http://ngageoint.github.io/geopackage-viewer-js/)
  - [![NPM](https://img.shields.io/npm/v/@ngageoint/geopackage.svg)](https://www.npmjs.com/package/@ngageoint/geopackage)
  - [![OGC](https://img.shields.io/badge/OGC-v5-blue)](https://www.ogc.org/resource/products/details/?pid=1768)
  - [![Examples](https://img.shields.io/static/v1?label=&logo=JavaScript&color=informational&message=Examples)](https://github.com/ngageoint/geopackage-js/tree/master/docs/examples)

- [Core Java](http://ngageoint.github.io/geopackage-core-java/) - A non-standalone library providing core GeoPackage functionality to the Java and Android libraries.
  - [![GitHub](https://img.shields.io/github/release/ngageoint/geopackage-core-java.svg?label=GitHub&sort=semver)](https://github.com/ngageoint/geopackage-core-java) [![Build & Test](https://github.com/ngageoint/geopackage-core-java/workflows/Build%20&%20Test/badge.svg)](https://github.com/ngageoint/geopackage-core-java/actions/workflows/build-test.yml)
  - [![Javadoc](https://img.shields.io/maven-central/v/mil.nga.geopackage/geopackage-core.svg?label=Javadoc&colorB=39be00)](http://ngageoint.github.io/geopackage-core-java/docs/api/)
  - [![The Central Repository](https://img.shields.io/maven-central/v/mil.nga.geopackage/geopackage-core.svg?label=The%20Central%20Repository)](https://search.maven.org/artifact/mil.nga.geopackage/geopackage-core)

- [NGA Extensions](http://ngageoint.github.io/GeoPackage/docs/extensions/) - NGA extensions to the GeoPackage spec as defined by the OGC GeoPackage [extension mechanism](http://www.geopackage.org/spec/#_extension_mechanism) and defined using the [extension template](http://www.geopackage.org/spec/#extension_template).
  - [![Contents Id](https://img.shields.io/static/v1?label=&color=informational&message=Contents%20Id)](http://ngageoint.github.io/GeoPackage/docs/extensions/contents-id.html)
  - [![Feature Style](https://img.shields.io/static/v1?label=&color=informational&message=Feature%20Style)](http://ngageoint.github.io/GeoPackage/docs/extensions/feature-style.html)
  - [![Feature Tile Link](https://img.shields.io/static/v1?label=&color=informational&message=Feature%20Tile%20Link)](http://ngageoint.github.io/GeoPackage/docs/extensions/feature-tile-link.html)
  - [![Geometry Index](https://img.shields.io/static/v1?label=&color=informational&message=Geometry%20Index)](http://ngageoint.github.io/GeoPackage/docs/extensions/geometry-index.html)
  - [![Properties](https://img.shields.io/static/v1?label=&color=informational&message=Properties)](http://ngageoint.github.io/GeoPackage/docs/extensions/properties.html)
  - [![Tile Scaling](https://img.shields.io/static/v1?label=&color=informational&message=Tile%20Scaling)](http://ngageoint.github.io/GeoPackage/docs/extensions/tile-scaling.html)

- [Examples](https://github.com/ngageoint/GeoPackage/tree/master/docs/examples) - GeoPackage file examples

- [SQLite Exec](http://github.com/ngageoint/geopackage-java/tree/master/script/sqlite-exec) - Command utility that executes SQL statements on a SQLite database, including GeoPackages.
  - [![sqlite-exec.zip](https://img.shields.io/github/release/ngageoint/geopackage-java.svg?label=sqlite-exec.zip)](https://github.com/ngageoint/geopackage-java/releases/latest/download/sqlite-exec.zip)

# Simple Features

Libraries based upon the [OGC Simple Feature Access](http://www.opengeospatial.org/standards/sfa) standard (not GeoPackage specific).

### Java

- [Simple Features Java](http://ngageoint.github.io/simple-features-java/) - Base library of geometry objects and utilities.
  - [![GitHub](https://img.shields.io/github/release/ngageoint/simple-features-java.svg?label=GitHub&sort=semver)](https://github.com/ngageoint/simple-features-java) [![Build & Test](https://github.com/ngageoint/simple-features-java/workflows/Build%20&%20Test/badge.svg)](https://github.com/ngageoint/simple-features-java/actions/workflows/build-test.yml)
  - [![Javadoc](https://img.shields.io/maven-central/v/mil.nga/sf.svg?label=Javadoc&colorB=39be00)](http://ngageoint.github.io/simple-features-java/docs/api/)
  - [![The Central Repository](https://img.shields.io/maven-central/v/mil.nga/sf.svg?label=The%20Central%20Repository)](https://search.maven.org/artifact/mil.nga/sf)

- [Simple Features Well-Known Binary Java](http://ngageoint.github.io/simple-features-wkb-java/) - Library for writing and reading Simple Feature Geometries to and from Well-Known Binary.
  - [![GitHub](https://img.shields.io/github/release/ngageoint/simple-features-wkb-java.svg?label=GitHub&sort=semver)](https://github.com/ngageoint/simple-features-wkb-java) [![Build & Test](https://github.com/ngageoint/simple-features-wkb-java/workflows/Build%20&%20Test/badge.svg)](https://github.com/ngageoint/simple-features-wkb-java/actions/workflows/build-test.yml)
  - [![Javadoc](https://img.shields.io/maven-central/v/mil.nga.sf/sf-wkb.svg?label=Javadoc&colorB=39be00)](http://ngageoint.github.io/simple-features-wkb-java/docs/api/)
  - [![The Central Repository](https://img.shields.io/maven-central/v/mil.nga.sf/sf-wkb.svg?label=The%20Central%20Repository)](https://search.maven.org/artifact/mil.nga.sf/sf-wkb)

- [Simple Features Well-Known Text Java](http://ngageoint.github.io/simple-features-wkt-java/) - Library for writing and reading Simple Feature Geometries to and from Well-Known Text.
  - [![GitHub](https://img.shields.io/github/release/ngageoint/simple-features-wkt-java.svg?label=GitHub&sort=semver)](https://github.com/ngageoint/simple-features-wkt-java) [![Build & Test](https://github.com/ngageoint/simple-features-wkt-java/workflows/Build%20&%20Test/badge.svg)](https://github.com/ngageoint/simple-features-wkt-java/actions/workflows/build-test.yml)
  - [![Javadoc](https://img.shields.io/maven-central/v/mil.nga.sf/sf-wkt.svg?label=Javadoc&colorB=39be00)](http://ngageoint.github.io/simple-features-wkt-java/docs/api/)
  - [![The Central Repository](https://img.shields.io/maven-central/v/mil.nga.sf/sf-wkt.svg?label=The%20Central%20Repository)](https://search.maven.org/artifact/mil.nga.sf/sf-wkt)

- [Simple Features GeoJSON Java](http://ngageoint.github.io/simple-features-geojson-java/) - Library for writing and reading Simple Feature Geometries to and from GeoJSON.
  - [![GitHub](https://img.shields.io/github/release/ngageoint/simple-features-geojson-java.svg?label=GitHub&sort=semver)](https://github.com/ngageoint/simple-features-geojson-java) [![Build & Test](https://github.com/ngageoint/simple-features-geojson-java/workflows/Build%20&%20Test/badge.svg)](https://github.com/ngageoint/simple-features-geojson-java/actions/workflows/build-test.yml)
  - [![Javadoc](https://img.shields.io/maven-central/v/mil.nga.sf/sf-geojson.svg?label=Javadoc&colorB=39be00)](http://ngageoint.github.io/simple-features-geojson-java/docs/api/)
  - [![The Central Repository](https://img.shields.io/maven-central/v/mil.nga.sf/sf-geojson.svg?label=The%20Central%20Repository)](https://search.maven.org/artifact/mil.nga.sf/sf-geojson)

- [Simple Features Projection Java](http://ngageoint.github.io/simple-features-proj-java/) - Library for performing projection conversions between Simple Feature Geometries.
  - [![GitHub](https://img.shields.io/github/release/ngageoint/simple-features-proj-java.svg?label=GitHub&sort=semver)](https://github.com/ngageoint/simple-features-proj-java) [![Build & Test](https://github.com/ngageoint/simple-features-proj-java/workflows/Build%20&%20Test/badge.svg)](https://github.com/ngageoint/simple-features-proj-java/actions/workflows/build-test.yml)
  - [![Javadoc](https://img.shields.io/maven-central/v/mil.nga.sf/sf-proj.svg?label=Javadoc&colorB=39be00)](http://ngageoint.github.io/simple-features-proj-java/docs/api/)
  - [![The Central Repository](https://img.shields.io/maven-central/v/mil.nga.sf/sf-proj.svg?label=The%20Central%20Repository)](https://search.maven.org/artifact/mil.nga.sf/sf-proj)

### iOS

- [Simple Features iOS](http://ngageoint.github.io/simple-features-ios/) - Base library of geometry objects and utilities.
  - [![GitHub](https://img.shields.io/github/release/ngageoint/simple-features-ios.svg?label=GitHub&sort=semver)](https://github.com/ngageoint/simple-features-ios) [![Build & Test](https://github.com/ngageoint/simple-features-ios/workflows/Build%20&%20Test/badge.svg)](https://github.com/ngageoint/simple-features-ios/actions/workflows/build-test.yml)
  - [![Appledoc](https://img.shields.io/github/release/ngageoint/simple-features-ios.svg?label=Appledoc&colorB=39be00)](http://ngageoint.github.io/simple-features-ios/docs/api)
  - [![CocoaPods](https://img.shields.io/cocoapods/v/sf-ios.svg?label=CocoaPods)](https://cocoapods.org/pods/sf-ios)

- [Simple Features Well-Known Binary iOS](http://ngageoint.github.io/simple-features-wkb-ios/) - Library for writing and reading Simple Feature Geometries to and from Well-Known Binary.
  - [![GitHub](https://img.shields.io/github/release/ngageoint/simple-features-wkb-ios.svg?label=GitHub&sort=semver)](https://github.com/ngageoint/simple-features-wkb-ios) [![Build & Test](https://github.com/ngageoint/simple-features-wkb-ios/workflows/Build%20&%20Test/badge.svg)](https://github.com/ngageoint/simple-features-wkb-ios/actions/workflows/build-test.yml)
  - [![Appledoc](https://img.shields.io/github/release/ngageoint/simple-features-wkb-ios.svg?label=Appledoc&colorB=39be00)](http://ngageoint.github.io/simple-features-wkb-ios/docs/api)
  - [![CocoaPods](https://img.shields.io/cocoapods/v/sf-wkb-ios.svg?label=CocoaPods)](https://cocoapods.org/pods/sf-wkb-ios)

- [Simple Features Well-Known Text iOS](http://ngageoint.github.io/simple-features-wkt-ios/) - Library for writing and reading Simple Feature Geometries to and from Well-Known Text.
  - [![GitHub](https://img.shields.io/github/release/ngageoint/simple-features-wkt-ios.svg?label=GitHub&sort=semver)](https://github.com/ngageoint/simple-features-wkt-ios) [![Build & Test](https://github.com/ngageoint/simple-features-wkt-ios/workflows/Build%20&%20Test/badge.svg)](https://github.com/ngageoint/simple-features-wkt-ios/actions/workflows/build-test.yml)
  - [![Appledoc](https://img.shields.io/github/release/ngageoint/simple-features-wkt-ios.svg?label=Appledoc&colorB=39be00)](http://ngageoint.github.io/simple-features-wkt-ios/docs/api)
  - [![CocoaPods](https://img.shields.io/cocoapods/v/sf-wkt-ios.svg?label=CocoaPods)](https://cocoapods.org/pods/sf-wkt-ios)

- [Simple Features GeoJSON iOS](http://ngageoint.github.io/simple-features-geojson-ios/) - Library for writing and reading Simple Feature Geometries to and from GeoJSON.
  - [![GitHub](https://img.shields.io/github/release/ngageoint/simple-features-geojson-ios.svg?label=GitHub&sort=semver)](https://github.com/ngageoint/simple-features-geojson-ios) [![Build & Test](https://github.com/ngageoint/simple-features-geojson-ios/workflows/Build%20&%20Test/badge.svg)](https://github.com/ngageoint/simple-features-geojson-ios/actions/workflows/build-test.yml)
  - [![Appledoc](https://img.shields.io/github/release/ngageoint/simple-features-geojson-ios.svg?label=Appledoc&colorB=39be00)](http://ngageoint.github.io/simple-features-geojson-ios/docs/api)
  - [![CocoaPods](https://img.shields.io/cocoapods/v/sf-geojson-ios.svg?label=CocoaPods)](https://cocoapods.org/pods/sf-geojson-ios)

- [Simple Features Projection iOS](http://ngageoint.github.io/simple-features-proj-ios/) - Library for performing projection conversions between Simple Feature Geometries.
  - [![GitHub](https://img.shields.io/github/release/ngageoint/simple-features-proj-ios.svg?label=GitHub&sort=semver)](https://github.com/ngageoint/simple-features-proj-ios) [![Build & Test](https://github.com/ngageoint/simple-features-proj-ios/workflows/Build%20&%20Test/badge.svg)](https://github.com/ngageoint/simple-features-proj-ios/actions/workflows/build-test.yml)
  - [![Appledoc](https://img.shields.io/github/release/ngageoint/simple-features-proj-ios.svg?label=Appledoc&colorB=39be00)](http://ngageoint.github.io/simple-features-proj-ios/docs/api)
  - [![CocoaPods](https://img.shields.io/cocoapods/v/sf-proj-ios.svg?label=CocoaPods)](https://cocoapods.org/pods/sf-proj-ios)

### JavaScript

- [Simple Features JavaScript](http://ngageoint.github.io/simple-features-js/) - Base library of geometry objects and utilities.
  - [![GitHub](https://img.shields.io/github/release/ngageoint/simple-features-js.svg?label=GitHub&sort=semver)](https://github.com/ngageoint/simple-features-js) [![Build & Test](https://github.com/ngageoint/simple-features-js/actions/workflows/run-tests.yml/badge.svg)](https://github.com/ngageoint/simple-features-js/actions/workflows/run-tests.yml)
  - [![API](https://img.shields.io/github/release/ngageoint/simple-features-js.svg?label=API&colorB=39be00)](http://ngageoint.github.io/simple-features-js/api/)
  - [![NPM](https://img.shields.io/npm/v/@ngageoint/simple-features-js.svg)](https://www.npmjs.com/package/@ngageoint/simple-features-js)

- [Simple Features Well-Known Binary JavaScript](http://ngageoint.github.io/simple-features-wkb-js/) - Library for writing and reading Simple Feature Geometries to and from Well-Known Binary.
  - [![GitHub](https://img.shields.io/github/release/ngageoint/simple-features-wkb-js.svg?label=GitHub&sort=semver)](https://github.com/ngageoint/simple-features-wkb-js) [![Build & Test](https://github.com/ngageoint/simple-features-wkb-js/actions/workflows/run-tests.yml/badge.svg)](https://github.com/ngageoint/simple-features-wkb-js/actions/workflows/run-tests.yml)
  - [![API](https://img.shields.io/github/release/ngageoint/simple-features-wkb-js.svg?label=API&colorB=39be00)](http://ngageoint.github.io/simple-features-wkb-js/api/)
  - [![NPM](https://img.shields.io/npm/v/@ngageoint/simple-features-wkb-js.svg)](https://www.npmjs.com/package/@ngageoint/simple-features-wkb-js)

- [Simple Features Well-Known Text JavaScript](http://ngageoint.github.io/simple-features-wkt-js/) - Library for writing and reading Simple Feature Geometries to and from Well-Known Text.
  - [![GitHub](https://img.shields.io/github/release/ngageoint/simple-features-wkt-js.svg?label=GitHub&sort=semver)](https://github.com/ngageoint/simple-features-wkt-js) [![Build & Test](https://github.com/ngageoint/simple-features-wkt-js/actions/workflows/run-tests.yml/badge.svg)](https://github.com/ngageoint/simple-features-wkt-js/actions/workflows/run-tests.yml)
  - [![API](https://img.shields.io/github/release/ngageoint/simple-features-wkt-js.svg?label=API&colorB=39be00)](http://ngageoint.github.io/simple-features-wkt-js/api/)
  - [![NPM](https://img.shields.io/npm/v/@ngageoint/simple-features-wkt-js.svg)](https://www.npmjs.com/package/@ngageoint/simple-features-wkt-js)

- [Simple Features GeoJSON JavaScript](http://ngageoint.github.io/simple-features-geojson-js/) - Library for writing and reading Simple Feature Geometries to and from GeoJSON.
  - [![GitHub](https://img.shields.io/github/release/ngageoint/simple-features-geojson-js.svg?label=GitHub&sort=semver)](https://github.com/ngageoint/simple-features-geojson-js) [![Build & Test](https://github.com/ngageoint/simple-features-geojson-js/actions/workflows/run-tests.yml/badge.svg)](https://github.com/ngageoint/simple-features-geojson-js/actions/workflows/run-tests.yml)
  - [![API](https://img.shields.io/github/release/ngageoint/simple-features-geojson-js.svg?label=API&colorB=39be00)](http://ngageoint.github.io/simple-features-geojson-js/api/)
  - [![NPM](https://img.shields.io/npm/v/@ngageoint/simple-features-geojson-js.svg)](https://www.npmjs.com/package/@ngageoint/simple-features-geojson-js)

- [Simple Features Projection JavaScript](http://ngageoint.github.io/simple-features-proj-js/) - Library for performing projection conversions between Simple Feature Geometries.
  - [![GitHub](https://img.shields.io/github/release/ngageoint/simple-features-proj-js.svg?label=GitHub&sort=semver)](https://github.com/ngageoint/simple-features-proj-js) [![Build & Test](https://github.com/ngageoint/simple-features-proj-js/actions/workflows/run-tests.yml/badge.svg)](https://github.com/ngageoint/simple-features-proj-js/actions/workflows/run-tests.yml)
  - [![API](https://img.shields.io/github/release/ngageoint/simple-features-proj-js.svg?label=API&colorB=39be00)](http://ngageoint.github.io/simple-features-proj-js/api/)
  - [![NPM](https://img.shields.io/npm/v/@ngageoint/simple-features-proj-js.svg)](https://www.npmjs.com/package/@ngageoint/simple-features-proj-js)


# Projections

  Library for performing projection conversions between coordinates (not GeoPackage specific).

  - [Java](http://ngageoint.github.io/projections-java/) - A Java library providing projections functionality.
    - [![GitHub](https://img.shields.io/github/release/ngageoint/projections-java.svg?label=GitHub&sort=semver)](https://github.com/ngageoint/projections-java) [![Build & Test](https://github.com/ngageoint/projections-java/workflows/Build%20&%20Test/badge.svg)](https://github.com/ngageoint/projections-java/actions/workflows/build-test.yml)
    - [![Javadoc](https://img.shields.io/maven-central/v/mil.nga/proj.svg?label=Javadoc&colorB=39be00)](http://ngageoint.github.io/projections-java/docs/api/)
    - [![The Central Repository](https://img.shields.io/maven-central/v/mil.nga/proj.svg?label=The%20Central%20Repository)](https://search.maven.org/artifact/mil.nga/proj)

  - [iOS](http://ngageoint.github.io/projections-ios/) - An iOS library providing projections functionality.
    - [![GitHub](https://img.shields.io/github/release/ngageoint/projections-ios.svg?label=GitHub&sort=semver)](https://github.com/ngageoint/projections-ios) [![Build & Test](https://github.com/ngageoint/projections-ios/workflows/Build%20&%20Test/badge.svg)](https://github.com/ngageoint/projections-ios/actions/workflows/build-test.yml)
    - [![Appledoc](https://img.shields.io/github/release/ngageoint/projections-ios.svg?label=Appledoc&colorB=39be00)](http://ngageoint.github.io/projections-ios/docs/api)
    - [![CocoaPods](https://img.shields.io/cocoapods/v/proj-ios.svg?label=CocoaPods)](https://cocoapods.org/pods/proj-ios)

  - [JavaScript](http://ngageoint.github.io/projections-js/) - A JavaScript library providing projections functionality.
    - [![GitHub](https://img.shields.io/github/release/ngageoint/projections-js.svg?label=GitHub&sort=semver)](https://github.com/ngageoint/projections-js) [![Build & Test](https://github.com/ngageoint/projections-js/actions/workflows/run-tests.yml/badge.svg)](https://github.com/ngageoint/projections-js/actions/workflows/run-tests.yml)
    - [![API](https://img.shields.io/github/release/ngageoint/projections-js.svg?label=API&colorB=39be00)](http://ngageoint.github.io/projections-js/api/)
    - [![NPM](https://img.shields.io/npm/v/@ngageoint/projections-js.svg)](https://www.npmjs.com/package/@ngageoint/projections-js)

  - [PROJ](https://github.com/ngageoint/PROJ/wiki) - An OSGeo PROJ fork to support C/C++ CocoaPods for use on iOS and other Apple platforms.
    - [![GitHub](https://img.shields.io/github/release/ngageoint/PROJ.svg?label=GitHub&sort=semver)](https://github.com/ngageoint/PROJ)
    - [![CocoaPods](https://img.shields.io/cocoapods/v/PROJ.svg?label=CocoaPods)](https://cocoapods.org/pods/PROJ)
    - [![OSGeo/PROJ](https://img.shields.io/github/v/release/OSGeo/PROJ.svg?label=OSGeo/PROJ&sort=semver)](https://github.com/OSGeo/PROJ)
    
  - [Project](http://github.com/ngageoint/projections-java/tree/master/script/project) - Command utility to perform coordinate transformations from a source projection to a target projection.
    - [![project.zip](https://img.shields.io/github/release/ngageoint/projections-java.svg?label=project.zip)](https://github.com/ngageoint/projections-java/releases/latest/download/project.zip)

# Coordinate Reference Systems

  Library implementation of the OGC [Geographic information — Well-known text representation of coordinate reference systems](http://docs.opengeospatial.org/is/18-010r7/18-010r7.html) specification (not GeoPackage specific).

  - [Java](http://ngageoint.github.io/coordinate-reference-systems-java/) - A Java library providing Coordinate Reference System and Well-Known Text functionality.
    - [![GitHub](https://img.shields.io/github/release/ngageoint/coordinate-reference-systems-java.svg?label=GitHub&sort=semver)](https://github.com/ngageoint/coordinate-reference-systems-java) [![Build & Test](https://github.com/ngageoint/coordinate-reference-systems-java/workflows/Build%20&%20Test/badge.svg)](https://github.com/ngageoint/coordinate-reference-systems-java/actions/workflows/build-test.yml)
    - [![Javadoc](https://img.shields.io/maven-central/v/mil.nga/crs.svg?label=Javadoc&colorB=39be00)](http://ngageoint.github.io/coordinate-reference-systems-java/docs/api/)
    - [![The Central Repository](https://img.shields.io/maven-central/v/mil.nga/crs.svg?label=The%20Central%20Repository)](https://search.maven.org/artifact/mil.nga/crs)

  - [iOS](http://ngageoint.github.io/coordinate-reference-systems-ios/) - An iOS library providing Coordinate Reference System and Well-Known Text functionality.
    - [![GitHub](https://img.shields.io/github/release/ngageoint/coordinate-reference-systems-ios.svg?label=GitHub&sort=semver)](https://github.com/ngageoint/coordinate-reference-systems-ios) [![Build & Test](https://github.com/ngageoint/coordinate-reference-systems-ios/workflows/Build%20&%20Test/badge.svg)](https://github.com/ngageoint/coordinate-reference-systems-ios/actions/workflows/build-test.yml)
    - [![Appledoc](https://img.shields.io/github/release/ngageoint/coordinate-reference-systems-ios.svg?label=Appledoc&colorB=39be00)](http://ngageoint.github.io/coordinate-reference-systems-ios/docs/api)
    - [![CocoaPods](https://img.shields.io/cocoapods/v/crs-ios.svg?label=CocoaPods)](https://cocoapods.org/pods/crs-ios)

  - [Pretty](http://github.com/ngageoint/coordinate-reference-systems-java/tree/master/script/pretty) - Command utility to parse and pretty print OGC Coordinate Reference System Well-Known Text.
    - [![pretty.zip](https://img.shields.io/github/release/ngageoint/coordinate-reference-systems-java.svg?label=pretty.zip)](https://github.com/ngageoint/coordinate-reference-systems-java/releases/latest/download/pretty.zip)

# TIFF

Library for reading and writing Tagged Image File Format files (not GeoPackage specific).

- [Java](http://ngageoint.github.io/tiff-java/) - A Java library providing Tagged Image File Format functionality.
  - [![GitHub](https://img.shields.io/github/release/ngageoint/tiff-java.svg?label=GitHub&sort=semver)](https://github.com/ngageoint/tiff-java) [![Build & Test](https://github.com/ngageoint/tiff-java/workflows/Build%20&%20Test/badge.svg)](https://github.com/ngageoint/tiff-java/actions/workflows/build-test.yml)
  - [![Javadoc](https://img.shields.io/maven-central/v/mil.nga/tiff.svg?label=Javadoc&colorB=39be00)](http://ngageoint.github.io/tiff-java/docs/api/)
  - [![The Central Repository](https://img.shields.io/maven-central/v/mil.nga/tiff.svg?label=The%20Central%20Repository)](https://search.maven.org/artifact/mil.nga/tiff)

- [iOS](http://ngageoint.github.io/tiff-ios/) - An iOS library providing Tagged Image File Format functionality.
  - [![GitHub](https://img.shields.io/github/release/ngageoint/tiff-ios.svg?label=GitHub&sort=semver)](https://github.com/ngageoint/tiff-ios) [![Build & Test](https://github.com/ngageoint/tiff-ios/workflows/Build%20&%20Test/badge.svg)](https://github.com/ngageoint/tiff-ios/actions/workflows/build-test.yml)
  - [![Appledoc](https://img.shields.io/github/release/ngageoint/tiff-ios.svg?label=Appledoc&colorB=39be00)](http://ngageoint.github.io/tiff-ios/docs/api)
  - [![CocoaPods](https://img.shields.io/cocoapods/v/tiff-ios.svg?label=CocoaPods)](https://cocoapods.org/pods/tiff-ios)

# OGC API

Libraries based upon the [OGC API Specification](https://github.com/opengeospatial/oapi_common) (not GeoPackage specific).

- [Features JSON Java](http://ngageoint.github.io/ogc-api-features-json-java/) - A Java library for writing and reading [OGC API - Features](https://github.com/opengeospatial/WFS_FES) to and from JSON.
  - [![GitHub](https://img.shields.io/github/release/ngageoint/ogc-api-features-json-java.svg?label=GitHub&sort=semver)](https://github.com/ngageoint/ogc-api-features-json-java) [![Build & Test](https://github.com/ngageoint/ogc-api-features-json-java/workflows/Build%20&%20Test/badge.svg)](https://github.com/ngageoint/ogc-api-features-json-java/actions/workflows/build-test.yml)
  - [![Javadoc](https://img.shields.io/maven-central/v/mil.nga.oapi.features/oapi-features-json.svg?label=Javadoc&colorB=39be00)](http://ngageoint.github.io/ogc-api-features-json-java/docs/api/)
  - [![The Central Repository](https://img.shields.io/maven-central/v/mil.nga.oapi.features/oapi-features-json.svg?label=The%20Central%20Repository)](https://search.maven.org/artifact/mil.nga.oapi.features/oapi-features-json)

- [Features JSON iOS](http://ngageoint.github.io/ogc-api-features-json-ios/) - An iOS library for writing and reading [OGC API - Features](https://github.com/opengeospatial/WFS_FES) to and from JSON.
  - [![GitHub](https://img.shields.io/github/release/ngageoint/ogc-api-features-json-ios.svg?label=GitHub&sort=semver)](https://github.com/ngageoint/ogc-api-features-json-ios) [![Build & Test](https://github.com/ngageoint/ogc-api-features-json-ios/workflows/Build%20&%20Test/badge.svg)](https://github.com/ngageoint/ogc-api-features-json-ios/actions/workflows/build-test.yml)
  - [![Appledoc](https://img.shields.io/github/release/ngageoint/ogc-api-features-json-ios.svg?label=Appledoc&colorB=39be00)](http://ngageoint.github.io/ogc-api-features-json-ios/docs/api)
  - [![CocoaPods](https://img.shields.io/cocoapods/v/ogc-api-features-json-ios.svg?label=CocoaPods)](https://cocoapods.org/pods/ogc-api-features-json-ios)

# Color

Library providing color representation with support for hex, RBG, arithmetic RBG, HSL, and integer colors (not GeoPackage specific).

- [Java](http://ngageoint.github.io/color-java/) - A Java color library.
  - [![GitHub](https://img.shields.io/github/release/ngageoint/color-java.svg?label=GitHub&sort=semver)](https://github.com/ngageoint/color-java) [![Build & Test](https://github.com/ngageoint/color-java/workflows/Build%20&%20Test/badge.svg)](https://github.com/ngageoint/color-java/actions/workflows/build-test.yml)
  - [![Javadoc](https://img.shields.io/maven-central/v/mil.nga/color.svg?label=Javadoc&colorB=39be00)](http://ngageoint.github.io/color-java/docs/api/)
  - [![The Central Repository](https://img.shields.io/maven-central/v/mil.nga/color.svg?label=The%20Central%20Repository)](https://search.maven.org/artifact/mil.nga/color)

- [iOS](http://ngageoint.github.io/color-ios/) - An iOS color library.
  - [![GitHub](https://img.shields.io/github/release/ngageoint/color-ios.svg?label=GitHub&sort=semver)](https://github.com/ngageoint/color-ios) [![Build & Test](https://github.com/ngageoint/color-ios/workflows/Build%20&%20Test/badge.svg)](https://github.com/ngageoint/color-ios/actions/workflows/build-test.yml)
  - [![Appledoc](https://img.shields.io/github/release/ngageoint/color-ios.svg?label=Appledoc&colorB=39be00)](http://ngageoint.github.io/color-ios/docs/api)
  - [![CocoaPods](https://img.shields.io/cocoapods/v/color-ios.svg?label=CocoaPods)](https://cocoapods.org/pods/color-ios)

- [JavaScript](http://ngageoint.github.io/color-js/) - A JavaScript color library.
  - [![GitHub](https://img.shields.io/github/release/ngageoint/color-js.svg?label=GitHub&sort=semver)](https://github.com/ngageoint/color-js) [![Build & Test](https://github.com/ngageoint/color-js/workflows/Build%20&%20Test/badge.svg)](https://github.com/ngageoint/color-js/actions/workflows/build-test.yml)
  - [![API](https://img.shields.io/github/release/ngageoint/color-js.svg?label=API&colorB=39be00)](http://ngageoint.github.io/color-js/api/)
  - [![NPM](https://img.shields.io/npm/v/@ngageoint/color-js.svg)](https://www.npmjs.com/package/@ngageoint/color-js)

# Grid

Libraries providing geospatial reference system grid functionality (not used by or specific to GeoPackage).

### Java

- [Grid](http://ngageoint.github.io/grid-java/) - Common geospatial reference system grid library.
  - [![GitHub](https://img.shields.io/github/release/ngageoint/grid-java.svg?label=GitHub&sort=semver)](https://github.com/ngageoint/grid-java) [![Build & Test](https://github.com/ngageoint/grid-java/workflows/Build%20&%20Test/badge.svg)](https://github.com/ngageoint/grid-java/actions/workflows/build-test.yml)
  - [![Javadoc](https://img.shields.io/maven-central/v/mil.nga/grid.svg?label=Javadoc&colorB=39be00)](http://ngageoint.github.io/grid-java/docs/api/)
  - [![The Central Repository](https://img.shields.io/maven-central/v/mil.nga/grid.svg?label=The%20Central%20Repository)](https://search.maven.org/artifact/mil.nga/grid)

- [MGRS](http://ngageoint.github.io/mgrs-java/) - Military Grid Reference System library. Relies on [Grid](https://github.com/ngageoint/grid-java).
  - [![GitHub](https://img.shields.io/github/release/ngageoint/mgrs-java.svg?label=GitHub&sort=semver)](https://github.com/ngageoint/mgrs-java) [![Build & Test](https://github.com/ngageoint/mgrs-java/workflows/Build%20&%20Test/badge.svg)](https://github.com/ngageoint/mgrs-java/actions/workflows/build-test.yml)
  - [![Javadoc](https://img.shields.io/maven-central/v/mil.nga/mgrs.svg?label=Javadoc&colorB=39be00)](http://ngageoint.github.io/mgrs-java/docs/api/)
  - [![The Central Repository](https://img.shields.io/maven-central/v/mil.nga/mgrs.svg?label=The%20Central%20Repository)](https://search.maven.org/artifact/mil.nga/mgrs)

- [GARS](http://ngageoint.github.io/gars-java/) - Global Area Reference System library. Relies on [Grid](https://github.com/ngageoint/grid-java).
  - [![GitHub](https://img.shields.io/github/release/ngageoint/gars-java.svg?label=GitHub&sort=semver)](https://github.com/ngageoint/gars-java) [![Build & Test](https://github.com/ngageoint/gars-java/workflows/Build%20&%20Test/badge.svg)](https://github.com/ngageoint/gars-java/actions/workflows/build-test.yml)
  - [![Javadoc](https://img.shields.io/maven-central/v/mil.nga/gars.svg?label=Javadoc&colorB=39be00)](http://ngageoint.github.io/gars-java/docs/api/)
  - [![The Central Repository](https://img.shields.io/maven-central/v/mil.nga/gars.svg?label=The%20Central%20Repository)](https://search.maven.org/artifact/mil.nga/gars)

### Android

- [MGRS](http://ngageoint.github.io/mgrs-android/) - Military Grid Reference System library. Relies on [MGRS Java](https://github.com/ngageoint/mgrs-java).
  - [![GitHub](https://img.shields.io/github/release/ngageoint/mgrs-android.svg?label=GitHub&sort=semver)](https://github.com/ngageoint/mgrs-android) [![Build Artifacts](https://github.com/ngageoint/mgrs-android/workflows/Build%20Artifacts/badge.svg)](https://github.com/ngageoint/mgrs-android/actions/workflows/build-artifacts.yml)
[![Test](https://github.com/ngageoint/mgrs-android/workflows/Test/badge.svg)](https://github.com/ngageoint/mgrs-android/actions/workflows/test.yml)
  - [![Javadoc](https://img.shields.io/maven-central/v/mil.nga.mgrs/mgrs-android.svg?label=Javadoc&colorB=39be00)](http://ngageoint.github.io/mgrs-android/docs/api/)
  - [![The Central Repository](https://img.shields.io/maven-central/v/mil.nga.mgrs/mgrs-android.svg?label=The%20Central%20Repository)](https://search.maven.org/artifact/mil.nga.mgrs/mgrs-android)
  - [![App](https://img.shields.io/static/v1?label=&logo=Android&color=informational&message=App)](https://github.com/ngageoint/mgrs-android/tree/master/app) [![APK](https://img.shields.io/static/v1?label=&logo=Android&color=informational&message=APK)](https://github.com/ngageoint/mgrs-android/releases/latest/download/mgrs.apk)

- [GARS](http://ngageoint.github.io/gars-android/) - Global Area Reference System library. Relies on [GARS Java](https://github.com/ngageoint/gars-java).
  - [![GitHub](https://img.shields.io/github/release/ngageoint/gars-android.svg?label=GitHub&sort=semver)](https://github.com/ngageoint/gars-android) [![Build Artifacts](https://github.com/ngageoint/gars-android/workflows/Build%20Artifacts/badge.svg)](https://github.com/ngageoint/gars-android/actions/workflows/build-artifacts.yml)
[![Test](https://github.com/ngageoint/gars-android/workflows/Test/badge.svg)](https://github.com/ngageoint/gars-android/actions/workflows/test.yml)
  - [![Javadoc](https://img.shields.io/maven-central/v/mil.nga.gars/gars-android.svg?label=Javadoc&colorB=39be00)](http://ngageoint.github.io/gars-android/docs/api/)
  - [![The Central Repository](https://img.shields.io/maven-central/v/mil.nga.gars/gars-android.svg?label=The%20Central%20Repository)](https://search.maven.org/artifact/mil.nga.gars/gars-android)
  - [![App](https://img.shields.io/static/v1?label=&logo=Android&color=informational&message=App)](https://github.com/ngageoint/gars-android/tree/master/app) [![APK](https://img.shields.io/static/v1?label=&logo=Android&color=informational&message=APK)](https://github.com/ngageoint/gars-android/releases/latest/download/gars.apk)

### iOS

- [Grid](http://ngageoint.github.io/grid-ios/) - Common geospatial reference system grid library.
  - [![GitHub](https://img.shields.io/github/release/ngageoint/grid-ios.svg?label=GitHub&sort=semver)](https://github.com/ngageoint/grid-ios) [![Build & Test](https://github.com/ngageoint/grid-ios/workflows/Build%20&%20Test/badge.svg)](https://github.com/ngageoint/grid-ios/actions/workflows/build-test.yml)
  - [![Appledoc](https://img.shields.io/github/release/ngageoint/grid-ios.svg?label=Appledoc&colorB=39be00)](http://ngageoint.github.io/grid-ios/docs/api)
  - [![CocoaPods](https://img.shields.io/cocoapods/v/grid-ios.svg?label=CocoaPods)](https://cocoapods.org/pods/grid-ios)

- [MGRS](http://ngageoint.github.io/mgrs-ios/) - Military Grid Reference System library. Relies on [Grid](https://github.com/ngageoint/grid-ios).
  - [![GitHub](https://img.shields.io/github/release/ngageoint/mgrs-ios.svg?label=GitHub&sort=semver)](https://github.com/ngageoint/mgrs-ios) [![Build & Test](https://github.com/ngageoint/mgrs-ios/workflows/Build%20&%20Test/badge.svg)](https://github.com/ngageoint/mgrs-ios/actions/workflows/build-test.yml)
  - [![Appledoc](https://img.shields.io/github/release/ngageoint/mgrs-ios.svg?label=Appledoc&colorB=39be00)](http://ngageoint.github.io/mgrs-ios/docs/api)
  - [![CocoaPods](https://img.shields.io/cocoapods/v/mgrs-ios.svg?label=CocoaPods)](https://cocoapods.org/pods/mgrs-ios)
  - [![App](https://img.shields.io/static/v1?label=&logo=Apple&color=informational&message=App)](https://github.com/ngageoint/mgrs-ios/tree/master/app)

- [GARS](http://ngageoint.github.io/gars-ios/) - Global Area Reference System library. Relies on [Grid](https://github.com/ngageoint/grid-ios).
  - [![GitHub](https://img.shields.io/github/release/ngageoint/gars-ios.svg?label=GitHub&sort=semver)](https://github.com/ngageoint/gars-ios) [![Build & Test](https://github.com/ngageoint/gars-ios/workflows/Build%20&%20Test/badge.svg)](https://github.com/ngageoint/gars-ios/actions/workflows/build-test.yml)
  - [![Appledoc](https://img.shields.io/github/release/ngageoint/gars-ios.svg?label=Appledoc&colorB=39be00)](http://ngageoint.github.io/gars-ios/docs/api)
  - [![CocoaPods](https://img.shields.io/cocoapods/v/gars-ios.svg?label=CocoaPods)](https://cocoapods.org/pods/gars-ios)
  - [![App](https://img.shields.io/static/v1?label=&logo=Apple&color=informational&message=App)](https://github.com/ngageoint/gars-ios/tree/master/app)

### JavaScript

- [Grid](http://ngageoint.github.io/grid-js/) - Common geospatial reference system grid library.
  - [![GitHub](https://img.shields.io/github/release/ngageoint/grid-js.svg?label=GitHub&sort=semver)](https://github.com/ngageoint/grid-js) [![Build & Test](https://github.com/ngageoint/grid-js/workflows/Build%20&%20Test/badge.svg)](https://github.com/ngageoint/grid-js/actions/workflows/build-test.yml)
  - [![API](https://img.shields.io/github/release/ngageoint/grid-js.svg?label=API&colorB=39be00)](http://ngageoint.github.io/grid-js/api/)
  - [![NPM](https://img.shields.io/npm/v/@ngageoint/grid-js.svg)](https://www.npmjs.com/package/@ngageoint/grid-js)

- [MGRS](http://ngageoint.github.io/mgrs-js/) - Military Grid Reference System library. Relies on [Grid](https://github.com/ngageoint/grid-js).
  - [![GitHub](https://img.shields.io/github/release/ngageoint/mgrs-js.svg?label=GitHub&sort=semver)](https://github.com/ngageoint/mgrs-js) [![Build & Test](https://github.com/ngageoint/mgrs-js/workflows/Build%20&%20Test/badge.svg)](https://github.com/ngageoint/mgrs-js/actions/workflows/build-test.yml)
  - [![API](https://img.shields.io/github/release/ngageoint/mgrs-js.svg?label=API&colorB=39be00)](http://ngageoint.github.io/mgrs-js/api/)
  - [![NPM](https://img.shields.io/npm/v/@ngageoint/mgrs-js.svg)](https://www.npmjs.com/package/@ngageoint/mgrs-js)

- [GARS](http://ngageoint.github.io/gars-js/) - Global Area Reference System library. Relies on [Grid](https://github.com/ngageoint/grid-js).
  - [![GitHub](https://img.shields.io/github/release/ngageoint/gars-js.svg?label=GitHub&sort=semver)](https://github.com/ngageoint/gars-js) [![Build & Test](https://github.com/ngageoint/gars-js/workflows/Build%20&%20Test/badge.svg)](https://github.com/ngageoint/gars-js/actions/workflows/build-test.yml)
  - [![API](https://img.shields.io/github/release/ngageoint/gars-js.svg?label=API&colorB=39be00)](http://ngageoint.github.io/gars-js/api/)
  - [![NPM](https://img.shields.io/npm/v/@ngageoint/gars-js.svg)](https://www.npmjs.com/package/@ngageoint/gars-js)
