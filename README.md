# Copper-hub

This repository contains source code for copper-hub which is the alerting, monitoring and update handling system for Copper

Please check README.md file inside the premetheus-master directory for configurations.

After installing, it is must to create a datasource in grafana as "prometheus" and local URL would be "http://prometheus.monitoring.svc.cluster.local:9090/".

Then create a "Notification channel" to make sure that alert mails will receive for the right address.