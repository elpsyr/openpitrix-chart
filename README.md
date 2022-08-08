# openpitrix-chart
helm chart for openpitrix （available for k8s v1.21.* +）

### Use
```shell
git clone https://github.com/elpsyr/openpitrix-chart.git
cd openpitrix-chart/
helm install  openpitrix --namespace openpitrix-system openpitrix/
```


### What change
- deployment gv
- deployment selector
- pvc & pv

### Test
this chart version has tested in kubernetes(version 1.21.13)