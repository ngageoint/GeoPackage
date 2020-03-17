Table of Contents
=================

* [MapCache](#mapcache)
* [GeoPackage](#geopackage)
* [Simple Features](#simple-features)
* [TIFF](#tiff)
* [OGC API](#ogc-api)

# MapCache

An app that utilizes and demonstrates the functionality in the GeoPackage Mobile Libraries.

- [Android](http://ngageoint.github.io/geopackage-mapcache-android) - An Android app that can be built and installed from Android Studio or directly from the APK.
  - [![GitHub](https://img.shields.io/github/release/ngageoint/geopackage-mapcache-android.svg?label=GitHub)](https://github.com/ngageoint/geopackage-mapcache-android) [![Build](https://github.com/ngageoint/geopackage-mapcache-android/workflows/Build/badge.svg)](https://github.com/ngageoint/geopackage-mapcache-android/actions?query=workflow%3ABuild)
  - [![Google Play](https://img.shields.io/static/v1?label=&logo=Google-Play&color=informational&message=Google%20Play)](https://play.google.com/store/apps/details?id=mil.nga.mapcache)
  - [![Legacy APK](https://img.shields.io/static/v1?label=&logo=Android&color=informational&message=Legacy%20APK)](https://github.com/ngageoint/geopackage-mapcache-android/releases/download/1.26/mapcache-1.26.apk)

- [iOS](http://ngageoint.github.io/geopackage-mapcache-ios) - An iOS app that can be built and installed from Xcode.
  - [![GitHub](https://img.shields.io/github/release/ngageoint/geopackage-mapcache-ios.svg?label=GitHub)](https://github.com/ngageoint/geopackage-mapcache-ios) [![Build Archive](https://github.com/ngageoint/geopackage-mapcache-ios/workflows/Build%20Archive/badge.svg)](https://github.com/ngageoint/geopackage-mapcache-ios/actions?query=workflow%3A%22Build+Archive%22)
  - [![App Store](https://img.shields.io/static/v1?label=&logo=Apple&color=informational&message=App%20Store)](https://apps.apple.com/us/app/mapcache-by-nga/id1477252454)
  - [![Legacy Movie](https://img.shields.io/static/v1?label=&logo=iOS&color=informational&message=Legacy%20Movie)](https://owncloud.devops.geointservices.io/index.php/s/Qh2pYaoo9ge1Ei0)

# GeoPackage

Main Page for the NGA [GeoPackage Libraries](http://ngageoint.github.io/GeoPackage/) providing [OGC GeoPackage](http://www.geopackage.org/) [spec](http://www.geopackage.org/spec) [implementations](http://www.geopackage.org/implementations.html)

An [OGC Certified](http://www.opengeospatial.org/resource/products?org_match=US+National+Geospatial-Intelligence+Agency) SDK that provides the ability to manage GeoPackage files providing read, write, import, export, share, and open support. Open GeoPackage files provide read and write access to features and tiles.

- [Java](http://ngageoint.github.io/geopackage-java/) – A Java library providing GeoPackage functionality and command line tools. Relies on [Core Java](https://github.com/ngageoint/geopackage-core-java).
  - [![GitHub](https://img.shields.io/github/release/ngageoint/geopackage-java.svg?label=GitHub)](https://github.com/ngageoint/geopackage-java) [![Build & Test](https://github.com/ngageoint/geopackage-java/workflows/Build%20&%20Test/badge.svg)](https://github.com/ngageoint/geopackage-java/actions?query=workflow%3A%22Build+%26+Test%22)
  - [![Javadoc](https://img.shields.io/maven-central/v/mil.nga.geopackage/geopackage.svg?label=Javadoc&colorB=39be00)](http://ngageoint.github.io/geopackage-java/docs/api/)
  - [![The Central Repository](https://img.shields.io/maven-central/v/mil.nga.geopackage/geopackage.svg?label=The%20Central%20Repository)](https://search.maven.org/artifact/mil.nga.geopackage/geopackage)
  - [![OGC](https://img.shields.io/badge/OGC-v3.2-blue)](http://www.opengeospatial.org/resource/products/details/?pid=1550)

- [Android](http://ngageoint.github.io/geopackage-android/) - An Android SDK providing GeoPackage functionality and utilities to Android apps. Relies on [Core Java](https://github.com/ngageoint/geopackage-core-java).
  - [![GitHub](https://img.shields.io/github/release/ngageoint/geopackage-android.svg?label=GitHub)](https://github.com/ngageoint/geopackage-android) [![Build Artifacts](https://github.com/ngageoint/geopackage-android/workflows/Build%20Artifacts/badge.svg)](https://github.com/ngageoint/geopackage-android/actions?query=workflow%3A%22Build+Artifacts%22)
[![Test](https://github.com/ngageoint/geopackage-android/workflows/Test/badge.svg)](https://github.com/ngageoint/geopackage-android/actions?query=workflow%3ATest)
  - [![Javadoc](https://img.shields.io/maven-central/v/mil.nga.geopackage/geopackage-android.svg?label=Javadoc&colorB=39be00)](http://ngageoint.github.io/geopackage-android/docs/api/)
  - [![The Central Repository](https://img.shields.io/maven-central/v/mil.nga.geopackage/geopackage-android.svg?label=The%20Central%20Repository)](https://search.maven.org/artifact/mil.nga.geopackage/geopackage-android)
  - [![OGC](https://img.shields.io/badge/OGC-v3.2-blue)](http://www.opengeospatial.org/resource/products/details/?pid=1551)

- [Android Map](http://ngageoint.github.io/geopackage-android-map/) - An Android Map SDK providing Google Map library implementations in addition to the inherited base [GeoPackage Android](https://github.com/ngageoint/geopackage-android/) functionality.
  - [![GitHub](https://img.shields.io/github/release/ngageoint/geopackage-android-map.svg?label=GitHub)](https://github.com/ngageoint/geopackage-android-map) [![Build Artifacts](https://github.com/ngageoint/geopackage-android-map/workflows/Build%20Artifacts/badge.svg)](https://github.com/ngageoint/geopackage-android-map/actions?query=workflow%3A%22Build+Artifacts%22)
[![Test](https://github.com/ngageoint/geopackage-android-map/workflows/Test/badge.svg)](https://github.com/ngageoint/geopackage-android-map/actions?query=workflow%3ATest)
  - [![Javadoc](https://img.shields.io/maven-central/v/mil.nga.geopackage.map/geopackage-android-map.svg?label=Javadoc&colorB=39be00)](http://ngageoint.github.io/geopackage-android-map/docs/api/)
  - [![The Central Repository](https://img.shields.io/maven-central/v/mil.nga.geopackage.map/geopackage-android-map.svg?label=The%20Central%20Repository)](https://search.maven.org/artifact/mil.nga.geopackage.map/geopackage-android-map)
  - [Examples](https://github.com/ngageoint/geopackage-android-map/tree/master/docs/examples)

- [iOS](http://ngageoint.github.io/geopackage-ios/) - An iOS SDK providing GeoPackage functionality and utilities to iOS apps.
  - [![GitHub](https://img.shields.io/github/release/ngageoint/geopackage-ios.svg?label=GitHub)](https://github.com/ngageoint/geopackage-ios) [![Build & Test](https://github.com/ngageoint/geopackage-ios/workflows/Build%20&%20Test/badge.svg)](https://github.com/ngageoint/geopackage-ios/actions?query=workflow%3A%22Build+%26+Test%22)
  - [![Appledoc](https://img.shields.io/github/release/ngageoint/geopackage-ios.svg?label=Appledoc&colorB=39be00)](http://ngageoint.github.io/geopackage-ios/docs/api)
  - [![CocoaPods](https://img.shields.io/cocoapods/v/geopackage-ios.svg?label=CocoaPods)](https://cocoapods.org/pods/geopackage-ios)
  - [![OGC](https://img.shields.io/badge/OGC-v3.2-blue)](http://www.opengeospatial.org/resource/products/details/?pid=1552)
  - [Examples](https://github.com/ngageoint/geopackage-ios/tree/master/docs/examples)

- [JS](http://ngageoint.github.io/geopackage-js/) - A JavaScript library providing GeoPackage functionality and utilities to node and web applications.
  - [![GitHub](https://img.shields.io/github/release/ngageoint/geopackage-js.svg?label=GitHub)](https://github.com/ngageoint/geopackage-js) [![Build and Run Tests](https://github.com/ngageoint/geopackage-js/workflows/Build%20and%20Run%20Tests/badge.svg)](https://github.com/ngageoint/geopackage-js/actions?query=workflow%3A%22Build+and+Run+Tests%22)
  - [GeoPackage Viewer](http://ngageoint.github.io/geopackage-js/)
  - [![NPM](https://img.shields.io/npm/v/@ngageoint/geopackage.svg)](https://www.npmjs.com/package/@ngageoint/geopackage)
  - [![OGC](https://img.shields.io/badge/OGC-v2-blue)](http://www.opengeospatial.org/resource/products/details/?pid=1549)
  - [Examples](https://github.com/ngageoint/geopackage-js/tree/master/docs/examples)

- [Core Java](http://ngageoint.github.io/geopackage-core-java/) - A non-standalone library providing core GeoPackage functionality to the Java and Android libraries.
  - [![GitHub](https://img.shields.io/github/release/ngageoint/geopackage-core-java.svg?label=GitHub)](https://github.com/ngageoint/geopackage-core-java) [![Build & Test](https://github.com/ngageoint/geopackage-core-java/workflows/Build%20&%20Test/badge.svg)](https://github.com/ngageoint/geopackage-core-java/actions?query=workflow%3A%22Build+%26+Test%22)
  - [![Javadoc](https://img.shields.io/maven-central/v/mil.nga.geopackage/geopackage-core.svg?label=Javadoc&colorB=39be00)](http://ngageoint.github.io/geopackage-core-java/docs/api/)
  - [![The Central Repository](https://img.shields.io/maven-central/v/mil.nga.geopackage/geopackage-core.svg?label=The%20Central%20Repository)](https://search.maven.org/artifact/mil.nga.geopackage/geopackage-core)

- [NGA Extensions](http://ngageoint.github.io/GeoPackage/docs/extensions/) - NGA extensions to the GeoPackage spec as defined by the OGC GeoPackage [extension mechanism](http://www.geopackage.org/spec/#_extension_mechanism) and defined using the [extension template](http://www.geopackage.org/spec/#extension_template).
  - [Contents Id](http://ngageoint.github.io/GeoPackage/docs/extensions/contents-id.html)
  - [Feature Style](http://ngageoint.github.io/GeoPackage/docs/extensions/feature-style.html)
  - [Feature Tile Link](http://ngageoint.github.io/GeoPackage/docs/extensions/feature-tile-link.html)
  - [Geometry Index](http://ngageoint.github.io/GeoPackage/docs/extensions/geometry-index.html)
  - [Properties](http://ngageoint.github.io/GeoPackage/docs/extensions/properties.html)
  - [Tile Scaling](http://ngageoint.github.io/GeoPackage/docs/extensions/tile-scaling.html)

- [SQLite Exec](http://github.com/ngageoint/geopackage-java/tree/master/script/sqlite-exec) - Command utility that executes SQL statements on a SQLite database, including GeoPackages.
  - [![sqlite-exec.zip](https://img.shields.io/github/release/ngageoint/geopackage-java.svg?label=sqlite-exec.zip)](https://github.com/ngageoint/geopackage-java/releases/latest/download/sqlite-exec.zip)

# Simple Features

Libraries based upon the [OGC Simple Feature Access](http://www.opengeospatial.org/standards/sfa) standard (not GeoPackage specific).

### Java

- [Simple Features Java](http://ngageoint.github.io/simple-features-java/) - Base library of geometry objects and utilities.
  - [![GitHub](https://img.shields.io/github/release/ngageoint/simple-features-java.svg?label=GitHub)](https://github.com/ngageoint/simple-features-java) [![Build & Test](https://github.com/ngageoint/simple-features-java/workflows/Build%20&%20Test/badge.svg)](https://github.com/ngageoint/simple-features-java/actions?query=workflow%3A%22Build+%26+Test%22)
  - [![Javadoc](https://img.shields.io/maven-central/v/mil.nga/sf.svg?label=Javadoc&colorB=39be00)](http://ngageoint.github.io/simple-features-java/docs/api/)
  - [![The Central Repository](https://img.shields.io/maven-central/v/mil.nga/sf.svg?label=The%20Central%20Repository)](https://search.maven.org/artifact/mil.nga/sf)

- [Simple Features Well Known Binary Java](http://ngageoint.github.io/simple-features-wkb-java/) - Library for writing and reading Simple Feature Geometries to and from Well-Known Binary.
  - [![GitHub](https://img.shields.io/github/release/ngageoint/simple-features-wkb-java.svg?label=GitHub)](https://github.com/ngageoint/simple-features-wkb-java) [![Build & Test](https://github.com/ngageoint/simple-features-wkb-java/workflows/Build%20&%20Test/badge.svg)](https://github.com/ngageoint/simple-features-wkb-java/actions?query=workflow%3A%22Build+%26+Test%22)
  - [![Javadoc](https://img.shields.io/maven-central/v/mil.nga.sf/sf-wkb.svg?label=Javadoc&colorB=39be00)](http://ngageoint.github.io/simple-features-wkb-java/docs/api/)
  - [![The Central Repository](https://img.shields.io/maven-central/v/mil.nga.sf/sf-wkb.svg?label=The%20Central%20Repository)](https://search.maven.org/artifact/mil.nga.sf/sf-wkb)

- [Simple Features GeoJSON Java](http://ngageoint.github.io/simple-features-geojson-java/) - Library for writing and reading Simple Feature Geometries to and from GeoJSON.
  - [![GitHub](https://img.shields.io/github/release/ngageoint/simple-features-geojson-java.svg?label=GitHub)](https://github.com/ngageoint/simple-features-geojson-java) [![Build & Test](https://github.com/ngageoint/simple-features-geojson-java/workflows/Build%20&%20Test/badge.svg)](https://github.com/ngageoint/simple-features-geojson-java/actions?query=workflow%3A%22Build+%26+Test%22)
  - [![Javadoc](https://img.shields.io/maven-central/v/mil.nga.sf/sf-geojson.svg?label=Javadoc&colorB=39be00)](http://ngageoint.github.io/simple-features-geojson-java/docs/api/)
  - [![The Central Repository](https://img.shields.io/maven-central/v/mil.nga.sf/sf-geojson.svg?label=The%20Central%20Repository)](https://search.maven.org/artifact/mil.nga.sf/sf-geojson)

- [Simple Features Projection Java](http://ngageoint.github.io/simple-features-proj-java/) - Library for performing projection conversions between Simple Feature Geometries.
  - [![GitHub](https://img.shields.io/github/release/ngageoint/simple-features-proj-java.svg?label=GitHub)](https://github.com/ngageoint/simple-features-proj-java) [![Build & Test](https://github.com/ngageoint/simple-features-proj-java/workflows/Build%20&%20Test/badge.svg)](https://github.com/ngageoint/simple-features-proj-java/actions?query=workflow%3A%22Build+%26+Test%22)
  - [![Javadoc](https://img.shields.io/maven-central/v/mil.nga.sf/sf-proj.svg?label=Javadoc&colorB=39be00)](http://ngageoint.github.io/simple-features-proj-java/docs/api/)
  - [![The Central Repository](https://img.shields.io/maven-central/v/mil.nga.sf/sf-proj.svg?label=The%20Central%20Repository)](https://search.maven.org/artifact/mil.nga.sf/sf-proj)

### iOS

- [Simple Features iOS](http://ngageoint.github.io/simple-features-ios/) - Base library of geometry objects and utilities.
  - [![GitHub](https://img.shields.io/github/release/ngageoint/simple-features-ios.svg?label=GitHub)](https://github.com/ngageoint/simple-features-ios) [![Build & Test](https://github.com/ngageoint/simple-features-ios/workflows/Build%20&%20Test/badge.svg)](https://github.com/ngageoint/simple-features-ios/actions?query=workflow%3A%22Build+%26+Test%22)
  - [![Appledoc](https://img.shields.io/github/release/ngageoint/simple-features-ios.svg?label=Appledoc&colorB=39be00)](http://ngageoint.github.io/simple-features-ios/docs/api)
  - [![CocoaPods](https://img.shields.io/cocoapods/v/sf-ios.svg?label=CocoaPods)](https://cocoapods.org/pods/sf-ios)

- [Simple Features Well Known Binary iOS](http://ngageoint.github.io/simple-features-wkb-ios/) - Library for writing and reading Simple Feature Geometries to and from Well-Known Binary.
  - [![GitHub](https://img.shields.io/github/release/ngageoint/simple-features-wkb-ios.svg?label=GitHub)](https://github.com/ngageoint/simple-features-wkb-ios) [![Build & Test](https://github.com/ngageoint/simple-features-wkb-ios/workflows/Build%20&%20Test/badge.svg)](https://github.com/ngageoint/simple-features-wkb-ios/actions?query=workflow%3A%22Build+%26+Test%22)
  - [![Appledoc](https://img.shields.io/github/release/ngageoint/simple-features-wkb-ios.svg?label=Appledoc&colorB=39be00)](http://ngageoint.github.io/simple-features-wkb-ios/docs/api)
  - [![CocoaPods](https://img.shields.io/cocoapods/v/sf-wkb-ios.svg?label=CocoaPods)](https://cocoapods.org/pods/sf-wkb-ios)

- [Simple Features GeoJSON iOS](http://ngageoint.github.io/simple-features-geojson-ios/) - Library for writing and reading Simple Feature Geometries to and from GeoJSON.
  - [![GitHub](https://img.shields.io/github/release/ngageoint/simple-features-geojson-ios.svg?label=GitHub)](https://github.com/ngageoint/simple-features-geojson-ios) [![Build & Test](https://github.com/ngageoint/simple-features-geojson-ios/workflows/Build%20&%20Test/badge.svg)](https://github.com/ngageoint/simple-features-geojson-ios/actions?query=workflow%3A%22Build+%26+Test%22)
  - [![Appledoc](https://img.shields.io/github/release/ngageoint/simple-features-geojson-ios.svg?label=Appledoc&colorB=39be00)](http://ngageoint.github.io/simple-features-geojson-ios/docs/api)
  - [![CocoaPods](https://img.shields.io/cocoapods/v/sf-geojson-ios.svg?label=CocoaPods)](https://cocoapods.org/pods/sf-geojson-ios)

- [Simple Features Projection iOS](http://ngageoint.github.io/simple-features-proj-ios/) - Library for performing projection conversions between Simple Feature Geometries.
  - [![GitHub](https://img.shields.io/github/release/ngageoint/simple-features-proj-ios.svg?label=GitHub)](https://github.com/ngageoint/simple-features-proj-ios) [![Build & Test](https://github.com/ngageoint/simple-features-proj-ios/workflows/Build%20&%20Test/badge.svg)](https://github.com/ngageoint/simple-features-proj-ios/actions?query=workflow%3A%22Build+%26+Test%22)
  - [![Appledoc](https://img.shields.io/github/release/ngageoint/simple-features-proj-ios.svg?label=Appledoc&colorB=39be00)](http://ngageoint.github.io/simple-features-proj-ios/docs/api)
  - [![CocoaPods](https://img.shields.io/cocoapods/v/sf-proj-ios.svg?label=CocoaPods)](https://cocoapods.org/pods/sf-proj-ios)

# TIFF

Library for reading and writing Tagged Image File Format files (not GeoPackage specific).

- [Java](http://ngageoint.github.io/tiff-java/) - A Java library providing Tagged Image File Format functionality.
  - [![GitHub](https://img.shields.io/github/release/ngageoint/tiff-java.svg?label=GitHub)](https://github.com/ngageoint/tiff-java) [![Build & Test](https://github.com/ngageoint/tiff-java/workflows/Build%20&%20Test/badge.svg)](https://github.com/ngageoint/tiff-java/actions?query=workflow%3A%22Build+%26+Test%22)
  - [![Javadoc](https://img.shields.io/maven-central/v/mil.nga/tiff.svg?label=Javadoc&colorB=39be00)](http://ngageoint.github.io/tiff-java/docs/api/)
  - [![The Central Repository](https://img.shields.io/maven-central/v/mil.nga/tiff.svg?label=The%20Central%20Repository)](https://search.maven.org/artifact/mil.nga/tiff)

- [iOS](http://ngageoint.github.io/tiff-ios/) - An iOS library providing Tagged Image File Format functionality.
  - [![GitHub](https://img.shields.io/github/release/ngageoint/tiff-ios.svg?label=GitHub)](https://github.com/ngageoint/tiff-ios) [![Build & Test](https://github.com/ngageoint/tiff-ios/workflows/Build%20&%20Test/badge.svg)](https://github.com/ngageoint/tiff-ios/actions?query=workflow%3A%22Build+%26+Test%22)
  - [![Appledoc](https://img.shields.io/github/release/ngageoint/tiff-ios.svg?label=Appledoc&colorB=39be00)](http://ngageoint.github.io/tiff-ios/docs/api)
  - [![CocoaPods](https://img.shields.io/cocoapods/v/tiff-ios.svg?label=CocoaPods)](https://cocoapods.org/pods/tiff-ios)

# OGC API

Libraries based upon the [OGC API Specification](https://github.com/opengeospatial/oapi_common) (not GeoPackage specific).

- [Features JSON Java](http://ngageoint.github.io/ogc-api-features-json-java/) - A Java library for writing and reading [OGC API - Features](https://github.com/opengeospatial/WFS_FES) to and from JSON.
  - [![GitHub](https://img.shields.io/github/release/ngageoint/ogc-api-features-json-java.svg?label=GitHub)](https://github.com/ngageoint/ogc-api-features-json-java) [![Build & Test](https://github.com/ngageoint/ogc-api-features-json-java/workflows/Build%20&%20Test/badge.svg)](https://github.com/ngageoint/ogc-api-features-json-java/actions?query=workflow%3A%22Build+%26+Test%22)
  - [![Javadoc](https://img.shields.io/maven-central/v/mil.nga.oapi.features/oapi-features-json.svg?label=Javadoc&colorB=39be00)](http://ngageoint.github.io/ogc-api-features-json-java/docs/api/)
  - [![The Central Repository](https://img.shields.io/maven-central/v/mil.nga.oapi.features/oapi-features-json.svg?label=The%20Central%20Repository)](https://search.maven.org/artifact/mil.nga.oapi.features/oapi-features-json)

- [Features JSON iOS](http://ngageoint.github.io/ogc-api-features-json-ios/) - An iOS library for writing and reading [OGC API - Features](https://github.com/opengeospatial/WFS_FES) to and from JSON.
  - [![GitHub](https://img.shields.io/github/release/ngageoint/ogc-api-features-json-ios.svg?label=GitHub)](https://github.com/ngageoint/ogc-api-features-json-ios) [![Build & Test](https://github.com/ngageoint/ogc-api-features-json-ios/workflows/Build%20&%20Test/badge.svg)](https://github.com/ngageoint/ogc-api-features-json-ios/actions?query=workflow%3A%22Build+%26+Test%22)
  - [![Appledoc](https://img.shields.io/github/release/ngageoint/ogc-api-features-json-ios.svg?label=Appledoc&colorB=39be00)](http://ngageoint.github.io/ogc-api-features-json-ios/docs/api)
  - [![CocoaPods](https://img.shields.io/cocoapods/v/ogc-api-features-json-ios.svg?label=CocoaPods)](https://cocoapods.org/pods/ogc-api-features-json-ios)
