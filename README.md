
# VictoriaMetrics customized Helm-charts

In this repo we are going to deploy cost-effective, redundant, dynamic-scalability and high-performance monitoring platform using VictoriaMetrics on spot nodes.

This repo contains the VictoriaMetrics-k8s-stack helm charts in 2 folders.

1.VictoriaMetrics-cluster-k8s-stack for installing multi-site VictoriaMetrics cluster on K8S:

    In this folder we can find values-main-cluster.yaml file to deploy the main VictoriaMetrics cluster.
    &
    values-2nd-cluster.yaml file to deploy the additional cluster on different site.

2.VMagent-only-k8s-stack for installing VMoperator & VMagent on any required workload to send metrics to the VictoriaMetrics clusters using RemoteWrite.url .



# My goal is to present a practical example of my Medium articles in this repo.

1.https://medium.com/everything-full-stack/what-makes-victoriametrics-the-new-de-facto-standard-choice-for-open-source-monitoring-5d2b66b6e292

2.2nd article will be announced soon


## Authors 

- [@Amitk3293 ](https://github.com/Amitk3293)
