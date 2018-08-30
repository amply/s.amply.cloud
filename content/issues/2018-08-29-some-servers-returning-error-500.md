---
title: Some servers returning error 500 (application server error)
date: 2018-08-29 14:40:00
resolved: true
resolvedWhen: 2018-08-29 15:00:00
# down, disrupted, notice
severity: disrupted
affected:
  - r.status.cloud
section: issue
---

*Resolved* - Fixed the problem and done deploy, solving 100% of the problem. {{< track "2018-09-29 15:00:00" >}}

*Monitoring* - Conflict in the name of the internal library to run renderer in multithreading. {{< track "2018-09-29 14:47:00" >}}

*Investigating* - After deploy for performance improvement was identified that some servers started returning error 500. {{< track "2018-09-29 14:40:00" >}}
