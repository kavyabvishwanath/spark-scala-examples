# spark-scala-examples

The spark examples run on Standalone mode with configs as below :

URL: spark://Kavyas-MacBook-Pro.local:7077
REST URL: spark://Kavyas-MacBook-Pro.local:6066 (cluster mode)
Alive Workers: 1
Cores in use: 2 Total, 2 Used
Memory in use: 7.0 GB Total, 1024.0 MB Used
Applications: 1 Running, 0 Completed
Drivers: 0 Running, 0 Completed
Status: ALIVE

Setup instructions :

1. Download spark latest version from https://spark.apache.org/downloads.html and install
2. cd to sbin and run the script : ./start-master.sh (starts the master, can be seen in action by going to http://localhost:8080/), 
   run ./start-slave.sh spark://Kavyas-MacBook-Pro.local:7077 -c 2 (this sets number of cores to be used by slave to 2 and specifies master node)
3. Checkout the code to your intellij, build and make sure to place the jar where master can access it.    
