```
docker pull sonarqube
```
or 
```
docker pull sonarqube:9.9.0
```
```
docker run -d --name sonarqube -p 9000:9000 sonarqube
```
```
docker ps
```
```
http://localhost:9000
```
```
```
Username: admin
Password: admin
```
```
docker run -d --name sonarqube-db -e POSTGRES_PASSWORD=yourpassword -e POSTGRES_USER=sonar -e POSTGRES_DB=sonar -p 5432:5432 postgres:alpine
```
```
 docker run -d --name sonarqube -p 9000:9000 -v sonarqube_data:/opt/sonarqube/data -v sonarqube_extensions:/opt/sonarqube/extensions sonarqube
```
```
sudo snap install --classic code
```
```
cd Downloads
```
```
mkdir sample
```
```
git clone https://github.com/pknowledge/sample.gi
```
Change : 
```
sonar-scanner \
  -Dsonar.projectKey=sample \
  -Dsonar.sources=. \
  -Dsonar.host.url=http://localhost:9000 \
  -Dsonar.token=sqp_0ce28a37da7f2fd6c1dfcc901910eded3e3392e8
```
```
/home/devsecops/Downloads/sonar-scanner-6.2.1.4610-linux-x64/bin/sonar-scanner \
  -Dsonar.projectKey=sample \
  -Dsonar.sources=. \
  -Dsonar.host.url=http://localhost:9000 \
  -Dsonar.token=sqp_0ce28a37da7f2fd6c1dfcc901910eded3e3392e8
```

