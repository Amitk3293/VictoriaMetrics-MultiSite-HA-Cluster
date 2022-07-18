
# VictoriaMetrics customized Helm-charts

This repo contains the VictoriaMetrics-k8s-stack helm charts in 2 folders.

1.VictoriaMetrics-cluster-k8s-stack for installing multi-site VictoriaMetrics cluster on K8S:

    In this folder we can find values-main-cluster.yaml to deploy the main VictoriaMetrics cluster,
    and values-2nd-cluster to deploy the additional cluster on different site.

2.VMagent-only-k8s-stack for installing VMoperator & VMagent on any required workload to send metrics to the VictoriaMetrics clusters using RemoteWrite.url .


## Authors 

- [@Amitk3293 ](https://github.com/Amitk3293)
