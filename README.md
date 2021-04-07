# totalcloud-assignment
To run the hello world site on AWS execute the below mentioned commands:

git clone https://github.com/vishwasms121/totalcloud-assignment.git
cd totalcloud-assignment
docker build -t flask-kubernetes .
docker images | grep flask-kubernetes
kubectl apply -f deployment.yaml
on browser enter http://nodeIP:31000 to view the Hello World application
