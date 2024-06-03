In this exmplae of ReplicaSet,
- namespace is created in namespace.yml
- Limit ranges are defined in limitrange.yml
- Probes are defined in rs.yml
- Volumes are defined in rs.yml

Apply configuration in below order

1. kubectl apply -f namespace.yaml
2. kubectl apply -f limitrange.yml
3. kubectl apply -f rs.yml
