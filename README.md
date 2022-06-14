# Algofut
FIFA Ultimate Team - Algorithmic Trading



## The purpose of this repo is to showcase trading strategies that were developed in Python and tested on FIFA ULTIMATE TEAM 22.

The following is the data infrastructure used to run the strategies.
Data for players is gathered 24/7 from FutBin.com using a scraper that runs on an E2 instance on GCP.
Player data (or assets) is relatively static so it is stored in a MySQL database hosted on GCP.
Price data is stored on an InfluxDB database as it is easier to manage and query timeseries using InfluxDB.



