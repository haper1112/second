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

