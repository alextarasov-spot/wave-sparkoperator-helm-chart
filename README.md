
kubectl create namespace wave-sparkoperator

helm dependency update ./wave-sparkoperator-helm-chart

helm install wave-sparkoperator  --namespace wave-sparkoperator ./wave-sparkoperator-helm-chart
