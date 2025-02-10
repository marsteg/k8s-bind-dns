# Authorative Bind9 Nameserver Helm Chart

This is a helm chart for running a Bind Nameserver on a Kubernetes Cluster

## Installation

Copy the Repo
from within the dns directoy:
```
    helm install <name> ./
```

## Modification

All configurations for Bind are done via configmaps. See the values.yaml to configure additional zones.
