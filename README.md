Kubernetes Integration Beta on Newrelic
=======================================

This contains a patched version of kubestate metrics that the autodiscover works.
If not used you should consider to set KUBE_STATE_METRICS_URL in the chart according to your url.

The License_id and the cluster_id needs to be specified in the values yaml or on the cli.

´helm upgrade --install infrastructure newrelic-infrastructure´

To install use the command above.
This is a proof of concept setup !

