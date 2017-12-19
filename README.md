### Completion & Defects

Currently, the system is capable of connecting via TCP/IP through sockets, obtaining transactions from clients, sharing contact information with other peers, as well as mining.

Due to difficulties with certain parts of the system, we did not reach full completion of the system. Currently, when a block is mined, it is not properly broadcast throughout the system to other peers, such that they add them to their own chains.

### Execution

To run the whole system easily, execute the `run_all.sh` script. This will open four servers, as well as a client for communicating with them.

`run_client_search_ports.sh` will open a client that searches on a range of ports to find available peers. This is not recommended as it takes a long time to complete this process. 



### Sources & Dependencies

- https://github.com/davecan/easychain

Used as a reference part for the required parts of a blockchain system.

- https://stuvel.eu/rsa

RSA library used for creating public/private keypairs.