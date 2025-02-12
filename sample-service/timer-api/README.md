# helm-charts

Helm charts used to deploy kubernetes objects into argoCD. This repository holds the responsability to deliver all Necessary object to build a (future) end-to-end service.

## Core Services

For now, we aim to deliver a stardart timer-api that is named this way but the service just respond an API request with the pod hostname and the current time the call was done.

## Future iterations

Work on the log UI working with Grafana and Prometheus also deploying Operators and services in argo. The architecture still needs to be decided. But I swear that I'll try to make as simple as possible (and also add an image explainig the services coupling).
