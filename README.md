
#Hive Load Testing with JMeter (Hortonworks Data Platform 2.4.2)

* Download JMeter: http://mirror.symnds.com/software/Apache//jmeter/binaries/apache-jmeter-3.0.tgz
* Unzip it to your preferred location
* Start jmeter from bin directory running ```jmeter``` for unix-like systems
* Add the required Hadoop/Hive and logging jars from this repo to ```/lib/ext```
* Set ```AutoCommit=true``` in JMeter configuration (Hive does not support ```AutoCommit=false```)



