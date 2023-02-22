# IoT-Project-22-23
 
How to use:

1 - Clone the project from GitHub  
2 - Type "docker compose up" in terminal, inside the main folder  
3 - Go on "http://localhost:8086/" for Influx DB (Credentials: matteo/matteopass)  
4 - Go on "http://localhost:1880/" for Node-RED  
5 - Go on "http://localhost:3000/" for Grafana (Credentials: admin/adminpass)  

IMPORTANT: when node-RED is started, the following libraries must be installed from the interface:
- node-red-contrib-influxdb
- node-red-dashboard
