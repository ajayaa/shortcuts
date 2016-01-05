ccm create cluster1 --cassandra-version 1.2.15
#cluster1 becomes the default cluster.
ccm list
#lists the cluster
ccm populate --node 3
ccm start
ccm status

#execute a file containing cql statements
ccm node1 cqlsh -f contrib/cql_samples.txt

#switch to a different cluster. Stop all the nodes in the other cluster before
# starting up nodes in a cluster.
ccm switch <cluster_name>

ccm create cluster2 -v 2.0.1 -n 1 -s -d
# start a cluster named cluster2 with a node and start it.
.ccm directory contains all nodes and all available installations of cassandra.
ccm node1 show
ccm add node3 -i 127.0.0.3 -j 7300
-j is jmx port
There are three protocols cassandra speaks.
Thrift
Binary(cql)
JMX
explore the settings
--------------------
~/.ccm/cluster1/node1/conf/cassandra.yaml
