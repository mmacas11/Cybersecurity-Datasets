# Cybersecurity datasets
Herein, we can find a curated list of cybersecurity datasets.

## Table of contents
* Network Intrusion Detection
* Malware detection and analysis
* Botnet detection and Domain Generation Algorithms (DGAs)
* Cyber-Physical System (CPS) Security
* Spam filtering
* Fraud detection
* Encrypted traffic analysis

## Network Intrusion Detection
* [KDD Cup 1999:](https://kdd.ics.uci.edu/databases/kddcup99/kddcup99.html) was created based on the DARPA 1998 dataset and inherit the same problems. Nevertheless, it is one of the most employed datasets until now for network intrusion detection. KDDCup99 includes full-packet data, break into subsets for training and testing. The network traffic is labeled in five classes: Normal, Probe, User to Root attacks, Remote to Local attacks, and DoS attacks. 
* [NSL-KDD:](https://www.unb.ca/cic/datasets/nsl.html) is an improved version of KDD Cup 1999 built to alleviate the redundancy problems, another often used dataset for network intrusion detection. However, it should be regarded that the underlying network traffic of NSL-KDD dates back to the year 1998. The dataset is labeled following the same structure as KDDCup99 and comprises separate sets for training and testing. 
* [CTU-13:](https://www.stratosphereips.org/datasets-ctu13) is a dataset of botnet traffic captured in the CTU University, Czech Republic, in 2011. The dataset aimed to have a large capture of real botnet traffic mixed with normal and background traffic. The CTU-13 dataset includes thirteen captures (i.e., scenarios) of different botnet samples. In each scenario, we executed a specific malware, which employed several protocols and performed different actions. 
* [AWID:](https://icsdweb.aegean.gr/awid/) focuses on 802.11 networks. A small network environment with ten clients was designed to capture WLAN traffic in a packet-based format. In one hour, around 2 million packets were captured. 155 features were extracted from each packet. For generating malicious traffic, 15 specific attacks against the 802.11 network (e.g., Probe Request, and CTS Flooding) were executed. The dataset is labeled and divided into a training and a test subset.
* [CIC-IDS2017:](https://www.unb.ca/cic/datasets/ids-2017.html) consists of labeled network flows, including full packet payloads in PCAP format, the corresponding profiles and the labeled flows and CSV files.
* [CSE-CIC-IDS2018:](https://www.unb.ca/cic/datasets/ids-2018.html) includes seven different attack scenarios, namely Brute-force, Heartbleed, Botnet, DoS, DDoS, Web attacks, and infiltration of the network from inside. The attacking infrastructure includes 50 machines, and the victim organization has five departments includes 420 PCs and 30 servers. This dataset includes each machine's network traffic and logs files from the victim side, along with 80 network traffic features extracted from captured traffic using CICFlowMeter-V3.
* [CIC-DDoS2019:](https://www.unb.ca/cic/datasets/ddos-2019.html) contains many different DDoS attacks that can be carried out through application layer protocols using TCP/UDP. The taxonomy of attacks in the dataset is performed in terms of exploitation-based and reflection-based attacks. The dataset was collected in two separate days for training and testing evaluation. The training set was captured on January 12th, 2019, and contains 12 different kinds of DDoS attacks, each attack type in a separated PCAP file. The attack types in the training day include UDP, SNMP, NetBIOS, LDAP, TFTP, NTP, SYN, WebDDoS, MSSQL, UDP-Lag, DNS, and SSDP DDoS based attacks. The testing data was created on March 11th, 2019, and contains 7 DDoS attacks SYN, MSSQL, UDP-Lag, LDAP, UDP, PortScan, and NetBIOS.
* [LITNET-2020:](https://dataset.litnet.lt/) comprises real network attacks in Lithuanian-wide network with servers in four geographic locations within the country. The breakdown of the traffic types is: Smurf (0.13%), ICMP-Flood (0.03%), UDP-Flood (0.21%), TCP SYN-flood (8.22%), HTTP flood (0.05%), LAND Attack (0.12%), Blaster Worm (0.05%), Code Red Worm (2.77%), Spam Bot Detection (0.002%), Reaper Worm (0.003%), Scanning/Spread (0.01%), Packet Fragmentation Attack (0.001%), Normal (88.24%). The entropy across attack classes is lower at 0.333 than between normal and anomalous traffic at 0.522.
* TON_IoT: 
* IoT-23:

## Malware detection and analysis
* N-BaIoT: 
* IoTPOT: 
* Genome: 
* Contagio-Mobile:
* AndroZoo:

## Botnet detection and Domain Generation Algorithms (DGAs)
Alexa Internet: dynamic lists such as the global Top sites.
* OSINT: 
* DGArchive: 
* 360netlab:
* AmritaDGA:
* UMUDGA:

## Cyber-Physical System (CPS) Security
* BATADAL:
* SWaT:
* WADI:
* Industrial Control System (ICS): https://sites.google.com/a/uah.edu/tommy-morris-uah/ics-data-sets
* HAI

## Spam filtering
* WEBSPAM-UK2007:
* UtkMI:
* Social honeypot:
* SMS Spam Collection v.1:

## Encrypted traffic analysis
* ISCX VPN-nonVPN
* ISCX Tor-nonTor
* Open HTTPS
* QUIC




