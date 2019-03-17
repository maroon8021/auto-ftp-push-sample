# How to built this system
## 0. Architecture

## 1. Set up Jenkins
### 1-1. Build jenkins on docker
`docker build -t jenkins-ftp-image .`  
by `Dockerfile`

### 1-2. Run
`sudo docker run -d -p 50000:8080 --name jenkins-ftp jenkins-ftp-image`

### 1-3. Add setting of "publish-over-ftp"
https://qiita.com/kingpanda/items/763ff7c29cfd8f027720#publish-over-ftp-plugin%E3%81%AE%E8%A8%AD%E5%AE%9A


## 2. Set up Github
### 2-1. Base settings
https://qiita.com/tz2i5i_ebinuma/items/528ea5163bb2df379852

### 2-2. Connect local jenkins
https://parashuto.com/rriver/tools/secure-tunneling-service-ngrok