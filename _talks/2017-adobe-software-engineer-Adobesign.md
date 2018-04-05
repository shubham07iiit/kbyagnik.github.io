---
title: "Adobe Sign"
collection: talks
type: "Full-time job"
permalink: /workexp/28/07/2014-AdobeSign
venue: "Adobe India Pvt. Ltd."
date: 28/07/2014
enddate: 17/03/2017
location: "Noida"
---

Adobe Sign is an another product which allowed documents to be signed digitally. I integrated Adobe Sign with Adobe Experience Manager forms via workitem to make it the part of AEM workflows.

* A workitem accepting relevant fields for Adobe Sign from user and invoking Adobe Sign flow.
* Asynchronous call to Adobe Sign to support multiple workflows in multi threaded environment.
* Call back mechanism to resume workflows which have strict dependency on Adobe Sign.
* Cron Job to fetch the status from Adobe Sign server and update the state of each workflow.
* Persisting workflows in database to resume it, if AEM Forms server goes down between paused state.

