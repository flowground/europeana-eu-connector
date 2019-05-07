# ![LOGO](logo.png) Europeana **flow**ground Connector

## Description

A generated **flow**ground connector for the Europeana API (version 2.3.0).

Generated from: https://api.apis.guru/v2/specs/europeana.eu/2.3.0/swagger.json<br/>
Generated at: 2019-05-07T17:40:26+03:00

## API Description

This Swagger API console provides an overview of an interface to the Europeana REST API. You can build and test anything from the simplest search to a complex query using facetList such as dates, geotags and permissions. For more help and information, head to our comprehensive <a href="http://labs.europeana.eu/api/">online documentation</a>.

## Authorization

This API does not require authorization.

## Actions

### get information about a specific dataset

*Tags:* `Providers and Datasets`

#### Input Parameters
* `id` - _required_ - id
* `wskey` - _optional_ - wskey
* `callback` - _optional_ - callback

### get the list of Europeana datasets

*Tags:* `Providers and Datasets`

#### Input Parameters
* `wskey` - _optional_ - wskey
* `callback` - _optional_ - callback
* `edmDatasetName` - _optional_ - edmDatasetName
* `countryCode` - _optional_ - countryCode
* `status` - _optional_ - status
* `offset` - _optional_ - offset
* `pagesize` - _optional_ - pagesize

### basic search function following the OpenSearch specification

*Tags:* `Search`

#### Input Parameters
* `searchTerms` - _required_ - searchTerms
* `startIndex` - _optional_ - startIndex
* `count` - _optional_ - count

### get information about a specific Europeana provider

*Tags:* `Providers and Datasets`

#### Input Parameters
* `id` - _required_ - id
* `wskey` - _optional_ - wskey
* `callback` - _optional_ - callback

### get the list of datasets provided by a specific provider

*Tags:* `Providers and Datasets`

#### Input Parameters
* `id` - _required_ - id
* `wskey` - _optional_ - wskey
* `callback` - _optional_ - callback

### get the list of Europeana data providers

*Tags:* `Providers and Datasets`

#### Input Parameters
* `wskey` - _optional_ - wskey
* `callback` - _optional_ - callback
* `countryCode` - _optional_ - countryCode
* `offset` - _optional_ - offset
* `pagesize` - _optional_ - pagesize

### get a single record in JSON format

*Tags:* `Record`

#### Input Parameters
* `collectionId` - _required_ - collectionId
* `recordId` - _required_ - recordId
* `profile` - _optional_ - profile
* `wskey` - _required_ - wskey
* `callback` - _optional_ - callback
* `hierarchytimeout` - _optional_ - hierarchytimeout

### get single record in JSON LD format

*Tags:* `Record`

#### Input Parameters
* `collectionId` - _required_ - collectionId
* `recordId` - _required_ - recordId
* `wskey` - _required_ - wskey
* `format` - _optional_ - format
* `callback` - _optional_ - callback

### get single record in RDF format)

*Tags:* `Record`

#### Input Parameters
* `collectionId` - _required_ - collectionId
* `recordId` - _required_ - recordId
* `wskey` - _required_ - wskey

### search for records

*Tags:* `Search`

#### Input Parameters
* `wskey` - _required_ - wskey
* `query` - _optional_ - query
* `qf` - _optional_ - qf
* `reusability` - _optional_ - reusability
* `profile` - _optional_ - profile
* `start` - _optional_ - start
* `rows` - _optional_ - rows
* `facet` - _optional_ - facet
* `sort` - _optional_ - sort
* `colourpalette` - _optional_ - colourpalette
* `thumbnail` - _optional_ - thumbnail
* `media` - _optional_ - media
* `text_fulltext` - _optional_ - text_fulltext
* `landingpage` - _optional_ - landingpage
* `cursor` - _optional_ - cursor
* `callback` - _optional_ - callback

### Google Fieldtrip formatted RSS of selected collections

*Tags:* `Search`

#### Input Parameters
* `query` - _required_ - query
* `offset` - _optional_ - offset
* `limit` - _optional_ - limit
* `profile` - _optional_ - profile
* `language` - _optional_ - language

### get autocompletion recommendations for search queries

*Tags:* `Search`

#### Input Parameters
* `query` - _required_ - query
* `rows` - _optional_ - rows
* `phrases` - _optional_ - phrases
* `callback` - _optional_ - callback

### translate a term to different languages

*Tags:* `Search`

#### Input Parameters
* `term` - _required_ - term
* `languageCodes` - _required_ - languageCodes
* `wskey` - _required_ - wskey
* `profile` - _optional_ - profile
* `callback` - _optional_ - callback

## License

**flow**ground :- Telekom iPaaS / europeana-eu-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
