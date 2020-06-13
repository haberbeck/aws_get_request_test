# aws_get_request_test
Teste no Arduino UNO R3 para enviar um GET numa API do API Gateway utilizando o protocolo HTTP (porta 80). 

## Retorno da AWS
```sh
[WiFiEsp] Initializing ESP module
[WiFiEsp] Initilization successful - 1.5.4
Attempting to connect to WPA SSID: Mansao Haberbeck
[WiFiEsp] Connected to Mansao Haberbeck
You're connected to the network
SSID: Mansao Haberbeck
IP Address: 192.168.1.100
Signal strength (RSSI):-592 dBm

Starting connection to server...
[WiFiEsp] Connecting to d2vwdz22kcz9cl.cloudfront.net
Connected to server
HTTP/1.1 200 OK
Content-Type: application/json
Content-Length: 31
Connection: close
Date: Sat, 13 Jun 2020 03:46:26 GMT
x-amzn-RequestId: 1bc10a2d-99a5-4d0b-ae00-beca2ff3f58e
x-amz-apigw-id: ODDS8EGbmjQFYeA=
X-Amzn-Trace-Id: Root=1-5ee44c12-91b27b6e977f1b06632590d7;Sampled=0
X-Cache: Hit from cloudfront
Via: 1.1 01d14353bc8d6740e5432d2175f3b858.cloudfront.net (CloudFront)
X-Amz-Cf-Pop: GRU50
X-Amz-Cf-Id: AeGZIRC4sS3vfhu6YUqdF2Kd1W4oacF2otxjOyCDieyN0uLyz7mplg==
Age: 419

"Hello from Haberbecks Lambda!"
Disconnecting from server...
```
