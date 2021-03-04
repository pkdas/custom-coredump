# custom-coredump
Custom Linux systemd core_pattern and coredump utility 

# To apply custom-coredump on the workernodes in your K8S cluster

Copy custom-coredump-01.tar.gz to the K8S master node
and do the following

#tar -zxvf custom-coredump-01.tar.gz

#cd scripts

#./nodes

# Optional
To mount systemd coredump folder as /tmp/coredump, run the following
#./ippecoredump

# To restore systemd coredump
#./snodes 

