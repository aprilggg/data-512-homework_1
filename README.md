# data-512-homework_1

## Goal
The goal for this project is to analyze the monthly article traffic for Oscar winning movies pages from Wikipedia from July 1, 2015 to September 30, 2023.

## License and Reference
Source data and a link to the Wikimedia Foundation REST API terms of use: https://www.mediawiki.org/wiki/REST_API#Terms_and_conditions
Link to API documentation: https://wikitech.wikimedia.org/wiki/Analytics/AQS/Pageviews


## Output
The output of this project consist with 3 dataset files as following:
* academy_monthly_mobile_<201507>-<202309>.json: monthly article traffic for mobile user from July 2015 to September 2023
* academy_monthly_desktop_<201507>-<202309>.json: monthly article traffic for desktop user from July 2015 to September 2023
* academy_monthly_cumulative_<201507>-<202309>.json: Monthly cumulative data is the sum of all mobile, and all desktop traffic per article

It also includes 3 analysis as following:
* Maximum Average and Minimum Average: shows the articles that have the highest average monthly page requests and the lowest average monthly page requests for desktop access and mobile access.
* Top 10 Peak Page Views: contains time series for the top 10 article pages by largest (peak) page views over the entire time by access type.
* Fewest Months of Data: shows pages that have the fewest months of available data.
