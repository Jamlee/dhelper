# a helpful tool for creating machine and selecting the  machine

 refrence: https://docs.docker.com/swarm/provision-with-machine/


        dhelper create hostA 62                               # create a host with ip 192.168.62.100
        dhelper select-machine hostA                          #select current machine
        dhelper create-with-swarm hostA 62                    # create a swarm node
        dhelper create-with-swarm hostA 62  master_node_name  # create a swarm node and master node is  master_node_name


