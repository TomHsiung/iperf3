# network.performance.iperf3
Some useful network performance testing methods by iperf3

# Contents
1) iperf3.bandwidth.udp is the useful commands to launch a UDP transfer test. 

# How to use
Exceute the command syntax based on your need(s).

# Command syntax interpretation
--server: run in server mode  

--bind <host>: bind to a specific interface (IP address)  

--client <host>: run in client mode, connecting to <host>  

--time: time in seconds to transmit for (default 10 secs)  

--set-mss: set TCP/SCTP maximum segment size (MTU - 40 bytes)  

--length: data size in bytes for UDP packets  

--bandwidth: target bandwidth in bits/sec (0 for unlimited)  
                            (default 1 Mbit/sec for UDP, unlimited for TCP)  
                            (optional slash and packet count for burst mode)  

--format: format to report: Kbits, Mbits, KBytes, MBytes [kmgKMG]  

--udp: use UDP rather than TCP  

--reverse: run in reverse mode (server sends, client receives)  

--help: show the help information of iperf3
