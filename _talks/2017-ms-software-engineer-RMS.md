---
title: "Reporting Microservice"
collection: talks
type: "Full-time job"
permalink: /workexp/20/10/2017-RMS
venue: "Microsoft India Development Center"
date: 20/03/2017
enddate: 01/08/2018
location: "Bangalore, Karnataka"
---

[MileIq](https://www.mileiq.com/) is the mileage tracking app which captures drives taken by users to help them reporting their miles and expenses for tax saving during year end.

I am currently Working on reporting microservice which aggregates data we collect via product and generate reports for filing tax.

* Highly Robust, Scalable and reliable service written in Python 3.x, Django, Azure SQL Server.
* Using Redis queue as a producer and celery workers to carry out the task asynchronously.
* Retry Mechanism for handling reports failures.
* Integrated Reporting Microservice with accounting software XERO.
* Service runs inside Docker images which are deployed on Kubernetes. Service is hosted on Azure Container Services.
* 4 million active users.
