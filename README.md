# splunk-demo-counterfeitassets

## Background

## Prerequisites

1.	Open each .csv file (3) and make the following modifications:
    1. Change the dates to something recent (5-7 days ago works best)
    2.	OPTIONAL: In snow_cmdb.csv, change datacenter(s) to your customer’s datacenter(s), if known
    3.	OPTIONAL: In snow_cmdb.csv, change lat and lon to the latitude and longitude of your customer’s datacenter(s), if known
2.	OPTIONAL: Change hostnames

## Instructions

1.	Install Splunk
2.	Install this app (latest version will always be on my Github: github.com/moksha-io)
3.	Verify that the index “ca-demo” exists (will be created by app)
4.	Upload the 3 .csv files (sc_assets, macaddr_verification, snow_cmdb) into index “ca-demo” and use the filename as the host value (ex. sc_assets hostname for sc_assets.csv file)
5.	Start demo at CMDB dashboard 
6.	Pivot to Counterfeit Assets Detection 
