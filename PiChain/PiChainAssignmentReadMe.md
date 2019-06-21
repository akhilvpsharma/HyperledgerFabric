Assignment:

Docker Compose
Created a Hyperledger Fabric network for 2 Organizations, 2CAs and 1 Orderer.
Org1 has 2 peers: peer0 and peer1.
Org2 has 2 peers: peer0 and peer1.
There is a default channel called pichainchannel for org1 and org2.
Docker-Compose:
To bring the network up and running on the local machine, run the command: docker-compose up -d.
To bring the network down, run the command: docker-compose down.
To see the active container, run the command: docker ps.

Docker Swarm
Created a Hyperledger Fabric network for 2 Organizations, 2CAs and 1 Orderer.
Org1 has 1 peer, 1 CA and Orderer deployed on VM: 52.66.135.195 (Manager)
Org2 has 1 peer and 1 CA deployed on VM: 13.233.48.31 (Worker)
To check the services running, run the command: docker service ls.
