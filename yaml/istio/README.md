kubectl apply -f install/kubernetes/helm/istio/templates/crds.yaml

kubectl apply -f install/kubernetes/istio-demo.yaml

wget http://192.168.99.100:31780/productreviewms/productreview/1
curl http://192.168.99.100:31380/productreviewms/productreview/1

curl http://192.168.99.100:31380/productms/product/catalogue
