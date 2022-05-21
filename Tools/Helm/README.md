---
icon: gear
expanded: false
order: 2000
---

# Helm

# Helm commands

### Basic

| Command | Description |
|----------------|----------|
| helm repo add simon https://simonmisencik.github.io/helm-charts | Add repository named simon |
| helm repo list | Shows all of the repositories installed  for Helm |
| helm search repo nginx | Simple search in local repositories |
| helm search repo nginx --versions | Shows all versions as well |
| helm install mysite bitnami/drupal | Install chart |
| ... --namespace first mysite bitnami/drupal | Specify namespace |
| ... --values values.yaml | Specify values |
| ... --set username=admin | Specify value manualy |
| helm list | Shows intallations |
| ... --all-namespaces | This will query all namespaces |
| helm upgrade mysite bitnami/drupal | Load the chart and upgrade config |
| ... --version 6.2.22 | Specify version for update |

#### Example of chart update:
 $ helm repo update
 $ helm upgrade mysite bitnami/drupal
 
 **NOTE: Always supply values in upgrade becouse default values will be used!**
 
| Command | Description |
|----------------|----------|
| helm uninstall | Uninstall chart |
| .. --namespace first | Uninstall in specific namespace |
 
 TODO: Strana 37
 
 
