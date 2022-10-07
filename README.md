# brief_6
az aks create -g gabriel_brief6 -n kuber --ssh-key-value C:\Users\gabriel\.ssh\id_rsa.pub --node-count 4 --enable-managed-identity -a ingress-appgw --appgw-name myApplicationGateway --appgw-subnet-cidr "10.225.0.0/16"
