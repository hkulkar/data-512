# data-512-a1
This directory contains all the code, json, and CSV files required for assignment 1 of DATA 512 Autumn 2020.

# To re-run the analysis in jupyter notebook
For easiest setup, download [anaconda](https://www.anaconda.com/), then run

   jupyter notebook

from the directory. Once the notebook is loaded click "run all" cells.

# References
The jupyter notebook leverages two APIs from wikimedia:
<ol>
<li>The Legacy Pagecounts API [documentation](https://wikitech.wikimedia.org/wiki/Analytics/AQS/Legacy_Pagecounts), [endpoint](https://wikimedia.org/api/rest_v1/#!/Pagecounts_data_(legacy)/get_metrics_legacy_pagecounts_aggregate_project_access_site_granularity_start_end) provides access to desktop and mobile traffic data from December 2007 through July 2016.</li>
<li>The Pageviews API [documentation](https://wikitech.wikimedia.org/wiki/Analytics/AQS/Pageviews), [endpoint](https://wikimedia.org/api/rest_v1/#!/Pageviews_data/get_metrics_pageviews_aggregate_project_access_agent_granularity_start_end) provides access to desktop, mobile web, and mobile app traffic data from July 2015 through last month.</li>
</ol>
