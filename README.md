### Simple monitoring with IoT Database (RunABove) :v:

With this script, you can monitor basic information and send it to the IoT PaaS on RunAbove platform (OVH)
If you have ideas to enhance it, don't hesitate to make a pull request.


![alt tag](http://www.flotix.jp/wp-content/uploads/2015/12/Sélection_007.png)


## Tutoriel

IoT Runabove OVH : 	http://www.flotix.jp/tutoriel-iot-ovh-opentsdb/

Installation script : 	http://www.flotix.jp/tutoriel-monitoring-serveur-iot/

grafana installation :	http://www.flotix.jp/tutoriel-installer-grafana-donnees-iot-openstdb/


##### Prerequies

- curl
- vnstat
- python
- python-requests
- php5-cli
- php5-curl

####### apt-get install curl vnstat python python-requests php5-cli php5-curl


##### Configuration

You need to configure first part variables in 

- "monitoring.sh" 
- "bin/iot.py" API credentials
- "scripts/nginx_connections.php" Url of your nginx status



##### Grafana

http://www.flotix.jp/tutoriel-installer-grafana-donnees-iot-openstdb/


###### Contact

Email	: flotix@linux.com

Twitter : flotiix

GitHub	: ftx




