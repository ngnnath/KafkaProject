

## Project Kafka Consumer/Producer

It's  a simple python3 app that you can run by an command line interface using cli lib, and confluent kafka lib.
The project template is from cookiecutter framework.

To install it :

    sudo python3 setup install

Nb : if  the install fails it maybe caused by the wrong installation of required lib.
(Normally the setup.py specifies all the requirements )

 The cmds are as follows:

 Producer :

    nathproject produce --topic test --message  "message envoyé"

Consumer:

     nathproject consume --topic test --group  grp1

Run a server kafka Locally
[https://kafka.apache.org/quickstart](https://kafka.apache.org/quickstart)

 We run here the Kafka Server and the Zookeeper separately, but we can use a docker image to run it and also to create a cluster by setting the zookeeper.properties and zookeeper.properties to define the addresses of the different brokers.
 
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTg0ODMwODUyMywyODMyOTE1MDZdfQ==
-->