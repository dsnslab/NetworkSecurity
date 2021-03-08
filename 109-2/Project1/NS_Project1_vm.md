# VM Document for Project 1

## Usage
Startup:
1. Launch two VMs
2. In general, you will not need to log in to the Ubuntu VM to do anything.
3. You can now start your work on the Windows VM.

Connect to Kibana:
- To connect to Kibana, go to http://192.168.66.1:5601/ on the Endpoint.
- Notice that the ELK stack will take about 7 minutes to initialize after boot. 
- If you see "Kibana server is not ready yet", you may only need to wait for a while patiently.

## Software Version
ELK: 
- Ubuntu Server x64 20.04.2
- ELK Stack: https://drive.google.com/file/d/1Yp0n3JQ29xL-21XgF2XvFF_JrvWUvosi
Endpoint: 
- Windows 10 x64 Professional 20H2 (Build 19042.508)
- The OS image was downloaded from ftp://ca.nctu.edu.tw

## Credential
Ubuntu (ELK)
- Username: elk
- Password: elk
Windows (Endpoint)
- Username: Endpoint
- Password: Endpoint
Kibana
- Username: admin
- Password: admin

## Networking
IP
- ELK: 192.168.66.1
- Endpoint: 192.168.66.2
Port
- Kibana: 5601
- Logstash: 5044

