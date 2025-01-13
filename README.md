# ARCHIVE INFORMATION
> [!IMPORTANT]
> Due to lack of usage and maintenance, this repository has been archived.  
> Please read the [repository archival FAQ](https://docs.corp.spoton.sh/developer/undocumented-repositories-archival-faq/) for more information!
# codefresh-runtime-applications

This repository was created as part of the default Git Source added to your Hosted Codefresh Runtime.

Git Sources are how The Codefresh GitOps Platform syncs Kubernetes Resource Definitions from Git to your Clusters.

### Resources Definitions that should be stored in this Git Source
- CD
-- Argo CD Applications
-- Argo CD Projects
-- Application Sets
- Pipelines (for Hybrid runtimes only)
-- Workflow Templates
-- Cluster Templates
-- Sensors
-- Event Sources

### Application resources should not be stored in a Git Source, such as:
- Deployments
- Services
- Secrets
- Roles
