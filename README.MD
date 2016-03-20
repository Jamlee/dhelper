# a helpful tool for creating machine and selecting the  machine

 refrence: https://docs.docker.com/swarm/provision-with-machine/


        dhelper create hostA 62                               # create a host with static ip 192.168.62.100 and name `hostA`
        dhelper select-machine hostA                          # select `hostA` machine
        dhelper create-with-swarm hostA 62                    # create a swarm node  `hostA`
        dhelper create-with-swarm hostA 62  master_node_name  # create a swarm node and master node is  `master_node_name`
        dhelper stats                                         # show all contianer stat
        dhelper clean-none                                    # clean all none contianer
        dhelper clean-all-container                           # rm all container

        # there only one valid method i have tried to assign a static ip for bootdocker. it is assign
        a whole network to per machine.
