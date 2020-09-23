## Nodeport
- buat service nodeport (kubectl create -f nodeport.yaml)
- untuk mengecek semua service gunakan (kubectl get all --show-labels)
- lalu running di app http://172.17.0.1:30001

## LoadBalancer
- buat service load balancer (kubectl create -f loadbalancer.yaml)
- untuk mengecek semua service gunakan (kubectl get all --show-labels)
- ketik di command (minikube cv-service-loadbalancer --url) maka akan menghasilkan ip
- ketikan ip di browser 

## ingress
- aktifkan ingress (minikube addons enable ingress)
- buat service ingress (kubectl create -f ingress.yaml)
- untuk mengecek semua service gunakan (kubectl get all --show-labels)
- cek info lengkap dari ingress (kubectl get ingresses)
- jika masih kosong ip serta hostnya bisa menggukanan nano untuk mengubahnya
- buka alamat host yang sudah dimasukkan tadi diawali dengan http://
