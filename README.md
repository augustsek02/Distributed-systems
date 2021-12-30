GROUP MEMBERS

Name
Student Number
Registration Number
SEKEBA AUGUSTINE
1800723426
18/U/23426/EVE
ARINAITWE DERRICK
1800721137
18/U/21137/PS
MWIYIKINWA ISAAC
1800723445
18/U/23445/EVE
KUKUNDAKWE DIANA
217002273
17/U/5454/PS




PEER TO PEER SYSTEM
This is a peer to peer design with multi-cluster system which is able to perform a given functionality;

Three clusters
    • mpologoma(kampala)
    • simba(Dar-es-salaam)
    • mkango(lusaka)
Each cluster has an API and a public IP address for omicron and the users.
The cluster joins and leaves the network and resources can move from one cluster to another and a new cluster can be added to the network,users can provide details of a clusters.

How the code works
    • The code from .jar files is opened in the eclipse ide within the file located at p2p/src/myapp/myapp.java.
    • The gui for the java swing opens to fill in the different information: Name,T-port,key,R-port and the information to send. The R-port acts as the incoming port which is supposed to be between 1024-65535 and the T-port which is between 1024-65535 which is the outgoing port and the Key which is between -15 to 5.if the appropriate key is inserted the clusters are able to communicate.
    • The R-port of one app will be the T-port of the other app and vice versa.
      
The code is accessed at the repository for the link below:


# Distributed-systems
java peer to peer
