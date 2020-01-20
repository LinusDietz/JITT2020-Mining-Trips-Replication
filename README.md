# Replication Pack for "Mining Trips from Location-Based Social Networks for Clustering Travelers and Destinations"

`trips.csv` contains the information about the trips used in _"Dietz, Linus W.; Sen, Avradip; Roy, Rinita. & Wörndl, Wolfgang.: Mining Trips from Location-Based Social Networks for Clustering Travelers and Destinations. Information Technology & Tourism (to appear)_


## Underlying Data

This dataset contains trips derived from three location-based social networks.

* __Foursquare__ via a dataset published by [Dingqi Yang](https://sites.google.com/site/yangdingqi/home/foursquare-dataset)
* __Flickr__ via the [Yahoo Flickr Creative Commons 100 Million Dataset]
* __Twitter__ via a self-crawled dataset from 2011-2019

## Data Processing and Anonymization

For the details of processing check-ins to trips using the Python [tripmining] library please check the aforementioned article.

The published trips were anonymized by hashing the `travelers_id` and converting the exact time of the `first_checkin` and `last_checkin` columns into dates.


[Yahoo Flickr Creative Commons 100 Million Dataset]: https://cacm.acm.org/magazines/2016/2/197425-yfcc100m/fulltext
[tripmining]: https://github.com/linusdietz/tripmining
