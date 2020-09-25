# Anthos environ sample package

Anthos environ sample package to create GKE clusters on any Anthos platform, and manage the lifecycle of Anthos components on those clusters.
It relies on the Anthos Admin Service cluster to provide the functionality.

## Kpt Version <0.34.0

Older versions of `kpt` require setting these fields manually to satisfy `kpt fn run .` validation:

1. `kpt cfg set ./gke-cluster-1 gcloud.core.project ${PROJECT_ID}`
2. `kpt cfg set ./gke-cluster-1 gcloud.project.projectNumber ${PROJECT_NUMBER}`