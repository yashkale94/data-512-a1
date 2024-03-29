# data-512-a1
Assignment A1: Data Curation

# GOAL
The goal of the project is to understand the right steps and correct methods to clean data and display the data, so that the end user understands the message that needs to be conveyed.

# Data Source and terms of use:
The Wikimedia Foundation REST API terms of use: https://www.mediawiki.org/wiki/REST_API#Terms_and_conditions

# API Documentation:
Legacy API: https://wikitech.wikimedia.org/wiki/Analytics/AQS/Legacy_Pagecounts

Pageviews API: https://wikitech.wikimedia.org/wiki/Analytics/AQS/Pageviews

# Data Fields and their values in the CSV file
pagecount_all_views: This represents the views across both mobile and desktop access through pagecount API
pagecount_desktop_views: This represents the views across desktop access through pagecount API
pagecount_mobile_views: This represents the views across mobile access through pagecount API
pageview_all_views: This represents the views across both mobile and desktop access through pageview API
pageview_desktop_views: This represents the views across desktop access through pageview API
pageview_mobile_views: This represents the views across mobile access through pageview API

# Special Considerations

1) The data from Pageview API excludes spiders/crawlers, while data from the Pagecounts API does not.
2) There is an overlap on the data in a specific time period in both the APIs.
3) The Pageview API allows you to filter by agent=user while the Pagecount API does not.
