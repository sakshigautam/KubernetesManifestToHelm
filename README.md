helm install demo-release myapp-chart -n demo

# verify
kubectl -n demo get all

# upgrade after change
helm upgrade demo-release myapp-chart -n demo

# uninstall
helm uninstall demo-release -n demo
