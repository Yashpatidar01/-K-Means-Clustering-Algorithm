# K-Means-Clustering-Algorithm
An implementation of K-Means Clustering Algorithm to identify diiferent kinds of SSH Attacks. The project first involved finding the optimal value of K used in K Means by comparing the results and looking at the variation in the squared sum of errors. Attribute 15 is the file name of the pcap file corresponding to that instance. So after clustering pcap files are copied from the root directory to the corresponding cluster number. Now we have all the files belonging to the same cluster in the same directory. Now we analyze each pcap file using jNetPcap Java library and look ahead to find some useful patterns.


