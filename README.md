
# VictoriaMetrics customized Helm-charts

This repo is customized to deploy cost-effective, redundant, dynamic-scalability and high-performance monitoring platform using VictoriaMetrics on spot nodes.

### we can find all the details in this Medium article I wrote: [all-at-once-monster-multi-site-monitoring-platform-with-victoriametrics, A practical guide!](https://medium.com/everything-full-stack/what-makes-victoriametrics-the-new-de-facto-standard-choice-for-open-source-monitoring-5d2b66b6e292)

The repo contains the VictoriaMetrics-k8s-stack official helm charts in 2 folders with customized values.

1.VictoriaMetrics-cluster-k8s-stack for installing multi-site VictoriaMetrics cluster on K8S:

    In this folder we can find values-main-cluster.yaml file to deploy the main VictoriaMetrics cluster.
    &
    values-2nd-cluster.yaml file to deploy the additional cluster on different site.

2.VMagent-only-k8s-stack for installing VMoperator & VMagent on any required workload to send metrics to the VictoriaMetrics clusters using RemoteWrite.url .

## Related

[What makes VictoriaMetrics the new de-facto standard choice for open source monitoring](https://medium.com/everything-full-stack/what-makes-victoriametrics-the-new-de-facto-standard-choice-for-open-source-monitoring-5d2b66b6e292)

[all-at-once-monster-multi-site-monitoring-platform-with-victoriametrics, A practical guide!](https://medium.com/everything-full-stack/what-makes-victoriametrics-the-new-de-facto-standard-choice-for-open-source-monitoring-5d2b66b6e292)


## Authors 

- [@Amitk3293 ](https://github.com/Amitk3293) (https://www.linkedin.com/in/amit-karni/)
