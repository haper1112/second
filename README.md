# second

## Install DHT11 sensor
```
git clone https://github.com/adafruit/Adafruit_python_DHT.git
cd Adafruit_python_DHT
sudo python setup.py install
cd examples
```

- run
```
python AdafruitDHT.py 11 4
```

# InfluxDB installation

## 1.Repository의 GPG key를 더하기
```
curl -sL https://repos.influxdata.com/influxdb.key | sudo apt-key add -
```
## 2.Repository 구하기
```
echo "deb https://repos.influxdata.com/debian stretch stable" | sudo tee /etc/apt/sources.list.d/influxdb.list 
```
## 3. 프로그램 설치
```
sudo apt update
sudo apt install influxdb
```
## 4. 프로그램 실행
```
sudo service influxdb start
```

## 5. 데이터베이스 만들기 
``` 
>create database <데이터베이스이름>
```
```
확인 : show databases
```

## 1.Repository의 GPG key를 더하기 (GPG key : 라즈배리의 키와 레포지의 키 호환하게 설정하는 것)
```
curl https://bintray.com/user/downloadSubjectPublicKey?username=bintray | sudo apt-key add -
```

## 2. Repository를 더하기 
```
echo "deb https://dl.bintray.com/fg2it/deb stretch main" | sudo tee -a /etc/apt/sources.list.d/grafana.list
```

## 3. 프로그램 설치 
```
sudo apt update
sudo apt install grafana
```

## 4. 프로그램 실행
```
sudo service grafana-server start
```

### github 사용방법
 - Repository download 
 ``` 
 git clone gttps://github.com/<user name>/<repository name>
 ```
 
 ### vim 설정 
 
- set n // 숫자 라인 

- set cindent // c 언어 

- set ts=4 // tab size 4

- if has("Syntax") // syntax on 

- syntax on

- endif 
 


