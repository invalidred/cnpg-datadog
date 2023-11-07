# CNPG Datadog Dashboard

This repo contains `cnpg-dashboard.json` that should work with default metrics emitted from [CNPG](https://cloudnative-pg.io/documentation/1.20/monitoring/)

Note the dashboard leverages _template variables_ that you might need to update in `cnpg-dashboard` by doing a find and replace operation.

_template variables_

`kube_cluster_name`: the name of your kubernetes cluster

`service`: the name of your service
