# ![LOGO](logo.png) Top Stories **flow**ground Connector

## Description

A generated **flow**ground connector for the Top Stories API (version 2.0.0).

Generated from: https://api.apis.guru/v2/specs/nytimes.com/top_stories/2.0.0/swagger.json<br/>
Generated at: 2019-05-07T17:43:21+03:00

## API Description

The Top Stories API provides lists of articles and associated images by section.

## Authorization

Supported authorization schemes:
- API Key
## Actions

### Top Stories

> The Top Stories API returns a list of articles and associated images currently on the specified section.  Support JSON and JSONP.

*Tags:* `Stories`

#### Input Parameters
* `section` - _required_ - The section the story appears in.
    Possible values: home, opinion, world, national, politics, upshot, nyregion, business, technology, science, health, sports, arts, books, movies, theater, sundayreview, fashion, tmagazine, food, travel, magazine, realestate, automobiles, obituaries, insider.
* `format` - _required_ - if this is JSONP or JSON
    Possible values: json, jsonp.
* `callback` - _optional_ - The name of the function the API call results will be passed to. Required when using JSONP. This parameter has only one valid value per section. The format is {section_name}TopStoriesCallback.


## License

**flow**ground :- Telekom iPaaS / nytimes-com-top-stories-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
