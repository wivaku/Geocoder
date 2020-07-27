# Foursquare Geocoder provider
[![Build Status](https://travis-ci.org/geocoder-php/foursquare-provider.svg?branch=master)](http://travis-ci.org/geocoder-php/foursquare-provider)
[![Latest Stable Version](https://poser.pugx.org/geocoder-php/foursquare-provider/v/stable)](https://packagist.org/packages/geocoder-php/foursquare-provider)
[![Total Downloads](https://poser.pugx.org/geocoder-php/foursquare-provider/downloads)](https://packagist.org/packages/geocoder-php/foursquare-provider)
[![Monthly Downloads](https://poser.pugx.org/geocoder-php/foursquare-provider/d/monthly.png)](https://packagist.org/packages/geocoder-php/foursquare-provider)
[![Code Coverage](https://img.shields.io/scrutinizer/coverage/g/geocoder-php/foursquare-provider.svg?style=flat-square)](https://scrutinizer-ci.com/g/geocoder-php/foursquare-provider)
[![Quality Score](https://img.shields.io/scrutinizer/g/geocoder-php/foursquare-provider.svg?style=flat-square)](https://scrutinizer-ci.com/g/geocoder-php/foursquare-provider)
[![Software License](https://img.shields.io/badge/license-MIT-brightgreen.svg?style=flat-square)](LICENSE)

This is the Foursquare provider from the PHP Geocoder. This is a **READ ONLY** repository. See the
[main repo](https://github.com/geocoder-php/Geocoder) for information and documentation.

## Install

```bash
composer require geocoder-php/foursquare-provider
```

## Usage

The Foursquare Provider

### search for venue

- by latlon coordinates

- nearby place

```
$query = GeocodeQuery::create('foobar');
$query = $query->withData(MapQuest::DATA_KEY_ADDRESS, $address);
```


### get venue details



### get categories

### search parameters

radius
query
category

## Contribute

Contributions are very welcome! Send a pull request to the [main repository](https://github.com/geocoder-php/Geocoder) or
report any issues you find on the [issue tracker](https://github.com/geocoder-php/Geocoder/issues).
