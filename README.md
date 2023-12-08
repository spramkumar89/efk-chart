helm install efk-helm .
kubectl port-forward es-cluster-0 9200:9200
kubectl port-forward kibana-7b96b979cf-p9stj 5601:5601
