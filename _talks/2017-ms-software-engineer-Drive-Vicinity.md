---
title: "Drive Vicinity"
collection: talks
type: "Full-time job"
permalink: /workexp/20/03/2017-DV
venue: "Microsoft India Development Center"
date: 20/03/2017
location: "Bangalore, Karnataka"
project_name: "Drive Vicinity"
---

In the product [MileIq](https://www.mileiq.com/), I wrote a Job which aggregates last 1 month data of a user to determine the location visited a maximum number of times by the user. This location is set on the map when a user comes to miles dashboard.

* Data Aggregation Job running on AWS RedShift.
* The resulted analysis is uploaded to S3 in text files.
* From S3 data moved to Postgres database.
* Exposed API's to fetch the most frequent location for each user.
* When a user visits MilqIQ dashboard, they see map loaded with relevant location personalized to their use case.
