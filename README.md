# persistentgrafanaprom
In this task i shows how to Persist the data of Grafana And Prometheus

There are three file in this repository
1. grafancfg.yaml
2. prometheuscfg.yaml
3. kustomization.yaml

In grafancfg.yaml file all the resoursces like service,pvc,deployment are created for Grafana

In prometheuscfg.yaml file all the resoursces like configmap,service,pvc,deployment are created for Prometheus

In kustomization.yaml file another  two files are added as resources to provide Infrastructure as a code
