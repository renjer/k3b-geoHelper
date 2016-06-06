#k3b-geoHelper library

A j2se geo support library that is compatible with Android

## Status

* Current Release 
  * [![GitHub release](https://img.shields.io/github/release/k3b/k3b-geoHelper.svg?maxAge=2592000)](https://github.com/k3b/k3b-geoHelper/wiki/History)
* Sourcecode 
  * https://github.com/k3b/k3b-geoHelper/
* Last Release build 
  * [![Build Status](https://travis-ci.org/k3b/k3b-geoHelper.svg?branch=master)](https://travis-ci.org/k3b/k3b-geoHelper)
* Automated Tests Code Coverage 
  * [![codecov](https://codecov.io/gh/k3b/k3b-geoHelper/branch/master/graph/badge.svg)](https://codecov.io/gh/k3b/k3b-geoHelper)
* Licence
  * [<img src="https://img.shields.io/github/license/k3b/k3b-geoHelper.svg"></img>](https://github.com/k3b/k3b-geoHelper/blob/master/LICENSE)

## Purpose

A j2se geo support library that is compatible with Android

* parse/format [geo-uri-s](https://github.com/k3b/k3b-geoHelper/wiki/data#geo) and geoarea-uri-s .
	* Example uri: geo:53,10?q=(Hamburg)&z=8
	* Java examples [GeoUriTests.java](https://github.com/k3b/k3b-geoHelper/blob/master/k3b-geoHelper/src/test/java/de/k3b/geo/io/GeoUriTests.java)
* read geo-points from these file formats
	* [gpx](https://github.com/k3b/k3b-geoHelper/wiki/data#gpx)
	* [kml](https://github.com/k3b/k3b-geoHelper/wiki/data#kml)
	* [poi](https://github.com/k3b/k3b-geoHelper/wiki/data#poi)
	* [wikimedia](https://github.com/k3b/k3b-geoHelper/wiki/data#wikimedia) that is used by web-apis of wikipedia and wikivoyage
	* [Example files](https://github.com/k3b/k3b-geoHelper/blob/master/k3b-geoHelper/src/test/resources/de/k3b/geo/io/regressionTests/)
* parse different flavours of [ISO_8601 Date Formats](https://en.wikipedia.org/wiki/ISO_8601). 
	* Java examples [IsoDateTimeParserTests.java](https://github.com/k3b/k3b-geoHelper/blob/master/k3b-geoHelper/src/test/java/de/k3b/util/IsoDateTimeParserTests.java)

For more details see [supported data formats](https://github.com/k3b/k3b-geoHelper/wiki/data)

##Usage (with gradle)##

Add repository to root build.gradle at the end of repositories:

	allprojects {
		repositories {
			...
			maven { url "https://jitpack.io" }
		}
	}

Add dependencies to local build.gradle

	dependencies {
		compile 'com.github.k3b:k3b-geoHelper:v1.1.3'
	}

for details see https://jitpack.io/

##Dependencies##

* org.slf4j:slf4j-api

## References ##

* [Changelog](https://github.com/k3b/k3b-geoHelper/wiki/History)
* [Other Projects using k3b-geoHelper lib](https://github.com/k3b/k3b-geoHelper/wiki/Projects)
