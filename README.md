
#What is this repository for?
Network Monitoring Tool enables one to log and monitor data flowing in and out of the 
network. The program runs as a local service. 
It helps administrator to check for congestion in the network and the root cause for it.
It can be useful in troubleshooting packet loss and latency.

#Mainly the following LINUX commands have been used:
1. grep: It searches for the specified phrase (e.g.
        ‘ARP’) in the output file provided by the
        tcpdump command. This output is stored into a
        new file.
2. cut: The required fields (e.g. Source IP) are cut
        and the unnecessary symbols and info is clipped
        away.
3. sed: Lines which have unwanted output are
        removed using this command.
4. Paste: To paste all the cut fields from their
        respective files into one so that they can be
        loaded directly into the database.
5. rm: To permanently remove a file.

