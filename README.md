# everpeace's helm charts

## How to
```
$ helm repo add everpeace https://everpeace.github.io/helm-charts
```
## Installation
```
helm install -n kube-localstack2-release -f values.yaml . --wait
```
## Clean Up
```
helm del --purge kube-localstack2-release
```
## License
MIT License.
