---
title: "监控告警"
description: 
draft: false
collapsible: true
weight: 31
---

监控告警功能是基于资源层面的监控数据，设置告警条件和通知列表， 有助于及时了解资源使用情况和处理突发事件。

AlarmPolicy:

监控告警策略，包括设置告警条件和告警行为。 当告警策略跟资源关联后，会为每个关联的资源生成针对此资源的监控告警实体，即 Alarm 。

Alarm:

具体某个资源的监控告警实体，会根据告警策略中设置的检查周期，定期获取资源监控数据， 判断是否满足告警条件，满足则出发告警行为，并记录到告警历史中。
