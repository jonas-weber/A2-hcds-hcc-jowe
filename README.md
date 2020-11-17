# A2-hcds-hcc-jowe

## Goal of the project
A visualization of views of the english Wikipedia from January 2008 to October 2020.

## Data acquisition
### Source
1. The [Legacy Pagecounts API](https://wikitech.wikimedia.org/wiki/Analytics/AQS/Legacy_Pagecounts) provides access to desktop and mobile traffic data from December 2007 through July 2016.
2. The [Pageviews API](https://wikitech.wikimedia.org/wiki/Analytics/AQS/Pageviews) provides access to desktop, mobile web, and mobile app traffic data from July 2015 through last month.


#### License
[License](https://creativecommons.org/publicdomain/zero/1.0/)

#### Terms and conditions
* [Wikimedia Foundation REST API terms and conditions](https://www.mediawiki.org/wiki/Wikimedia_REST_API#Terms_and_conditions)

## Description of data fields
* **year** - the year in which the views took place
* **month** - the month in which the views took place
* **pagecount_all_views** - all views counted by the Pagecount API in this timeframe
* **pagecount_desktop_views** - all desktop views counted by the Pagecount API in this timeframe
* **pagecount_mobile_views** - all mobile views counted by the Pagecount API in this timeframe
* **pageview_all_views** - all views counted by the Pageview API in this timeframe
* **pageview_desktop_views** - all desktop views counted by the Pageview API in this timeframe
* **pageview_mobile_views** - all mobile views counted by the Pageview API in this timeframe
  
## Considerations
* The Pageview API data only includes human (organic) traffic.