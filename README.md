# totalcloud-assignment
To run the hello world site on AWS, execute the below mentioned commands:

1. git clone https://github.com/vishwasms121/totalcloud-assignment.git
2. cd totalcloud-assignment
3. docker build -t flask-kubernetes .
4. docker images | grep flask-kubernetes
5. kubectl apply -f deployment.yaml
6. on browser enter http://nodeIP:31000 to view the Hello World application
