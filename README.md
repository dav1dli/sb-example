# sb-example
Spring Boot REST App Example

Deploy:
oc create -f sb-example.yaml

Install helm chart: 
helm install ./helm/sb-app -n sb-app
Uninstall: helm delete --purge sb-app
