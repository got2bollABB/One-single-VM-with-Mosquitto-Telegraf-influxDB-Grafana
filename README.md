# One-single-VM-with-Mosquitto-Telegraf-influxDB-Grafana
One single VM with Mosquitto+Telegraf+influxDB+Grafana


Hello, 
I am currentling building up a PoC on a single Windows 10 virtal machine, hosted on Azure. 
I have installed a mosquitto mqtt broker instance, a telegraf instance, and influx DB instance and a grafana-server instance. 

Currently, I am using MQTT.fx to check what data the mqtt mosquitto broker is receiving ==> fine, it works
Now I am stuck as I can go forward with data collection and storage in the influxDB database using telegraph and its mqtt plugin. 

Can anyone help with numbers following wuestion I have: 
What are the steps to follow and what I could have done wrong ? 
What influx fonction should I use to check if the data base is rightly populated ? i have tried "show measurements" but I have no result. 
What can affect the right functionnement (like the port openning, main important setups to configure in diffrent files.conf etc..)

As you can see, I am not very familiar with these technologies, I am only a biginner...

Thank for your help. 
I will update this document on a weekly basis I hope ! 
Have a good day ! 
