### Clone the project
```
git clone https://github.com/samarthdadhaniya/QR-Scanner.git
cd QR-Scanner
```
### Create DockerFile 
```
Create a Dockerfile
```
###  Build the Docker Image
```
docker build -t qr-scanner-app .
```

### Run the Docker Container
```
docker run -d -p 3000:3000 --name qr-scanner qr-scanner-app
```
