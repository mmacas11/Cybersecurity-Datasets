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
* [TON_IoT:](https://research.unsw.edu.au/projects/toniot-datasets) involves heterogeneous data sources collected from Telemetry datasets of IoT and IIoT sensors, operating systems datasets of Windows 7 and 10 as well as Ubuntu 14 and 18 TLS and Network traffic datasets. The datasets were collected from a realistic and large-scale network designed at the Cyber Range and IoT Labs, the School of Engineering and Information technology (SEIT), UNSW Canberra the Australian Defence Force Academy. A new testbed network was built for the industry 4.0 network, including the Internet of Things (IoT) and Industrial (IIoT) networks. The testbed was deployed employing multiple virtual machines and hosts of windows, Linux, and Kali operating systems to manage the interconnection between the three layers of IoT, Cloud, and Edge/Fog systems. Various attacking techniques, such as DoS, DDoS, and ransomware, against web applications, IoT gateways, and computer systems across the IoT/IIoT network. The datasets were gathered in parallel processing to collect several normal and cyber-attack events from network traffic, Windows audit traces, Linux audit traces, and telemetry data of IoT services.
* [IoT-23:](https://www.stratosphereips.org/datasets-iot23) consists of twenty-three captures (called scenarios) of different IoT network traffic. These scenarios are divided into twenty network captures (PCAP files) from infected IoT devices (which will have the name of the malware sample executed on each scenario), and three network captures of real IoT devices network traffic (that have the name of the devices where the traffic was captured). A specific malware sample in a Raspberry Pi that used several protocols and performed different actions was executed on each malicious scenario.

## Malware detection and analysis
* [N-BaIoT:](https://archive.ics.uci.edu/ml/datasets/detection_of_IoT_botnet_attacks_N_BaIoT) contains real traffic obtained from nine commercial IoT devices such as Danmini doorbell, Provision PT-737E security camera, and Ecobee thermostat. For each device, the data was collected under both normal operating conditions and several different attacks performed by BASHLITE (e.g., scan, junk, UDP, TCP, and COMBO) and Mirai botnets (e.g., scan, Ack, Syn, DP, and UDPplain). The dataset has 115 numerical features.
* [IoTPOT:](https://ipsr.ynu.ac.jp/iot/) is a publicly available dataset that contains IoT threat samples collected by an IoT honeypot. The dataset initially comprises 500 malware samples, where most of them are categorized into four major families, including Linux.Gafgyt, Linux.Gafgyt.1, Trojan.Linux.Fgt and Mirai. The rest of the samples belong to relatively rare families such as Hajime, Tsunami, and LightAidra.
* [Genome:](http://www.malgenomeproject.org/)  has around 1,242 malicious Android applications gathered in 2010 and 2011. The samples are divided into 49 malware families that comprise almost all malware categories, namely Rootkit, Botnet, SMS Trojans, Trojan, Installer, and Spyware. The majority of genome applications come from unofficial Chinese marketplaces.
* [Contagio-Mobile:](https://contagiominidump.blogspot.com/) is a part of [contagiodump.blogspot.com](https://contagiodump.blogspot.com/). It offers an upload dropbox for sharing the malware samples and downloading any samples individually or in one zip.
* [AndroZoo:](https://androzoo.uni.lu/) is a growing collection of Android Applications collected from several sources (e.g., Google Play app market). It currently contains 17M different APKs, each of which has been analyzed by tens of different Antivirus products to know which applications are detected as malware.  
* [VirusShare:](https://virusshare.com/) is a repository of malware samples to provide security researchers, incident responders, forensic analysts, and access to samples of live malicious code.

## Botnet detection and Domain Generation Algorithms (DGAs)
* [Alexa Internet:](https://www.alexa.com/topsites) Alexa Internet is often referred to simply as Alexa. It is a Web traffic information, metrics, and analytics provider. Alexa can provide to the visitors the following principal utilities:
  1. See data for Alexa Top Sites.
  2. Search for traffic data, such as ranking and bounce rate, for websites not included in the top-ranked sites.
  3. Download the Alexa toolbar, which allows them to see statistics for websites as they browse and records their browsing data for inclusion in Alexa statistics.
  4. Create a custom toolbar, which can be shared.
* OSINT: 
* DGArchive: 
* 360netlab:
* AmritaDGA:
* UMUDGA:

## Cyber-Physical System (CPS) Security
* [BATADAL:](https://www.batadal.net/data.html) represents a water distribution network comprised of seven storage tanks with eleven pumps and five valves, controlled via nine Programmable Logic Controllers (PLCs). The network was created using epanetCPA, an open-source, object-oriented Matlab toolbox that allows for the injections of cyber-physical attacks and simulates the response of the network to these attacks. The dataset contains 43 variables, representing the tank water levels (7 variables), the flow and status of all the pumps (24 variables), as well as the inlet and pressure for the pumping stations and valves (12 variables). All variables are continuous, except the status of valve and pumps, represented by binary variables. The training data simulates hourly measurements collected for 356 days, resulting in 8.761 records. The test set comprises 2.089 records, which were gathered for 90 days. There exist seven attacks present in the test data. The attacks involved malicious actuator activation, sensor measurement manipulation, and PLC setpoint changes. Besides, the attacks were concealed from the SCADA system by replacing the PLC-to-SCADA communication data with the data recorded at the same hour during normal operation. BATADAL can be download freely on the website. 
* [SWaT:](https://itrust.sutd.edu.sg/testbeds/secure-water-treatment-swat/) was built at the Singapore University of Technology and Design in 2016, which is available upon request. It is a scaled-down, fully operational water treatment plant and comprises a six-stage process. Each stage is equipped with several sensors and actuators. The sensors comprise water pumps, flow meters, valves that control inflow are the actuators, and chemical dosing pumps. The sensors and actuators of each stage are connected to the corresponding PLC, and the PLCs are connected to the SCADA systems. This dataset comprises seven days of recording under normal conditions and four days during which 36 attacks were conducted (e.g., false sensor readings, and false control signals). The entire dataset contains 946,722 records, labeled as either attacks or normal, with 51 attributes corresponding to the sensor and actuator data.
* [WADI:](https://itrust.sutd.edu.sg/testbeds/water-distribution-wadi/) was built by the authors of SWaT \cite{goh2016dataset} and contains several large water tanks that supply water to consumer tanks. The dataset contains 15 attacks whose goal is to stop the water supply to the consumer tanks. The attacks were conducted by opening valves and spoofing sensors readings, and partially concealed. WADI is significantly larger than the SWaT and BATADAL dataset, contains 1.221.372 data points (full dataset) and 126 features. WADI is available upon request. 
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




