kubectl apply -f k8s/

#applies the configuration of all the #config  files in the directory k8s

imperative way of creating a secret
kubectl create secret generic [or tls] <secret_name> --from-literal key=value