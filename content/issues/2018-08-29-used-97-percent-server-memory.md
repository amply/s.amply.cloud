---
title: Excessive memory usage after multithreaded deploy (97%)
date: 2018-08-29 18:50:00
resolved: true
resolvedWhen: 2018-08-29 20:00:00
# down, disrupted, notice
severity: notice
affected:
  - r.status.cloud
section: issue
---

*Resolved* - Fixed problem with applied path. {{< track "2018-09-29 20:00:00" >}}

*Monitoring* - Identified the memory leak and applied path correction, we are monitoring whether the problem has been solved with production traffic. {{< track "2018-09-29 19:20:00" >}}

*Investigating* - After deploy was identified excessive memory consumption on the servers generating restart of the application when it reached *100% of memory*. Not generating impact on the delivery of the AMP sites, some deliveries got some **ms slower**. {{< track "2018-09-29 18:50:00" >}}
