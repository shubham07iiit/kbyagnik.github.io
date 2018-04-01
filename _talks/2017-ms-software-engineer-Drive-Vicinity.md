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

Aggregating last 1 month locations of a user to determine which location is most visited by user. This location is set on map when an user comes to mileiq dashboard.

* Data Aggregation Job running on AWS RedShift.
* The resulted analysis is uploaded to S3 in text files.
* From S3 data moved to postgres database.
* Exposed API's to fetch the most frequent location for each user.
* When user visit MilqIQ dashboard, they see map loaded with relevant location personalized to their use case.
