Steps to execute producer and consumer application.
For Kafka
==============================================================
    1. Run Zookeeper
    2. Run Kafka Server (broker)
    3. Create topic - kafka-topics --zookeeper 127.0.0.1:2181 --topic api_topic --create --partitions 3 --replication-factor 1

On Virtual Machine 
===============================================================

 1. Setup a VM with Linux OS. The VM machine can be selected with default resource capacity.
  
 2. Connect with SSH to the Linux VM.

 3. If Amazon Linux, then follow the link -https://tecadmin.net/install-java-on-amazon-linux/

 4. If  sudo apt-get update
        sudo apt-get install -y openjdk-8*    

 5. Copy the Java app jar files to the VM

 6. Run the app on the VM
     java -jar *.jar 
   
