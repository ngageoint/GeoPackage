# Related Tables Extension Updates for SOFWERX Challenge

Unreleased [GeoPackage Android](https://github.com/ngageoint/geopackage-android) functionality in support of [Related Tables Extension](http://www.geopackage.org/18-000.html) that may be used for the [SOFWERX challenge](https://www.teamwerx.org/mobile/) (ends 6/30/2018).  These changes will be released in future versions, but until then you may include them manually in your own project (pre-built or manually built). After being released, the libraries can [easily be included within projects](https://github.com/ngageoint/geopackage-android-map#normal-build).

#### Source Projects with RTE branch changes
* [GeoPackage Core java](https://github.com/ngageoint/geopackage-core-java/tree/rte)
* [GeoPackage Android](https://github.com/ngageoint/geopackage-android/tree/rte)
* [GeoPackage Android Map](https://github.com/ngageoint/geopackage-android-map/tree/rte)
* [MapCache Android](https://github.com/ngageoint/geopackage-mapcache-android/tree/rte)

#### Example Usage
* [GeoPackage example creator](https://github.com/ngageoint/geopackage-android/blob/rte/geopackage-sdk/src/androidTest/java/mil/nga/geopackage/test/GeoPackageExample.java) which was used to produce [this GeoPackage](https://github.com/ngageoint/GeoPackage/blob/master/docs/examples/android/rte/example.gpkg) with Related Tables (features, simple attributes, and media table)
* [Related Features Tests](https://github.com/ngageoint/geopackage-android/tree/rte/geopackage-sdk/src/androidTest/java/mil/nga/geopackage/test/extension/related) - read & write
* [Related Simple Attributes Tests](https://github.com/ngageoint/geopackage-android/tree/rte/geopackage-sdk/src/androidTest/java/mil/nga/geopackage/test/extension/related/simple) - read & write
* [Related Media Tests](https://github.com/ngageoint/geopackage-android/tree/rte/geopackage-sdk/src/androidTest/java/mil/nga/geopackage/test/extension/related/media) - read & write

#### JARs and AARs

* [Zipped](https://github.com/ngageoint/GeoPackage/blob/master/docs/examples/sofwerx/GeoPackageRTE.zip)
* [Unzipped](https://github.com/ngageoint/GeoPackage/blob/master/docs/examples/sofwerx/GeoPackageRTE/)


## GeoPackage Android

### Use this if you plan to use your own map

* Import the *geopackage-core* **jar** and *geopackage-android* **aar** files into your project

From Android Studio:
File -> New -> New Module -> Import .JAR/.AAR Package

| File Name | Subproject Name |
| --- | --- |
| geopackage-core-3.0.1.jar | geopackage-core |
| geopackage-android-3.0.1.aar | geopackage-android |

* Update your project dependencies to include the 2 modules and their sub dependencies

*module/build.gradle* **dependencies**

```
api project(':geopackage-core')
api project(':geopackage-android')
api 'mil.nga.sf:sf-proj:2.0.0'
api 'mil.nga.sf:sf-wkb:2.0.0'
api 'mil.nga.sf:sf-geojson:2.0.0'
api 'mil.nga:tiff:2.0.0'
api 'com.j256.ormlite:ormlite-core:5.0'
api 'com.j256.ormlite:ormlite-android:5.0'
api 'ar.com.hjg:pngj:2.1.0'
```

## GeoPackage Android Map

### Use this if you plan use the Google Map or plan to modify and use [MapCache](https://github.com/ngageoint/geopackage-mapcache-android)

* Import the *geopackage-core* **jar**, *geopackage-android* **aar**, and *geopackage-android-map* **aar** files into your project

From Android Studio:
File -> New -> New Module -> Import .JAR/.AAR Package

| File Name | Subproject Name |
| --- | --- |
| geopackage-core-3.0.1.jar | geopackage-core |
| geopackage-android-3.0.1.aar | geopackage-android |
| geopackage-android-map-3.0.1.aar | geopackage-android-map |

* Update your project dependencies to include the 3 modules and their sub dependencies

*module/build.gradle* **dependencies**

```
api project(':geopackage-core')
api project(':geopackage-android')
api project(':geopackage-android-map')
api 'com.google.android.gms:play-services-maps:15.0.1'
api 'com.google.maps.android:android-maps-utils:0.5'
api 'mil.nga.sf:sf-proj:2.0.0'
api 'mil.nga.sf:sf-wkb:2.0.0'
api 'mil.nga.sf:sf-geojson:2.0.0'
api 'mil.nga:tiff:2.0.0'
api 'com.j256.ormlite:ormlite-core:5.0'
api 'com.j256.ormlite:ormlite-android:5.0'
api 'ar.com.hjg:pngj:2.1.0'
```

## Attaching Source

Although the code will build without the source code, you may want / need to reference source for any libraries containing classes you plan to use directly.

*module/build.gradle*

```
sourceSets {
    main {
        main.java.srcDirs += '/path/simple-features-java/src/main/java'
        main.java.srcDirs += '/path/simple-features-proj-java/src/main/java'
        main.java.srcDirs += '/path/simple-features-wkb-java/src/main/java'
        main.java.srcDirs += '/path/geopackage-core-java/src/main/java'
        main.java.srcDirs += '/path/geopackage-android/geopackage-sdk/src/main/java'
        main.java.srcDirs += '/path/geopackage-android-map/geopackage-sdk/src/main/java'
    }
}
```
