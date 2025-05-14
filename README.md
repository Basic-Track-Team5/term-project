# CUAI Basic Track Team 5


## About the Dataset


> The RT-IoT2022, a proprietary dataset derived from a **real-time IoT infrastructure**, is introduced as a comprehensive resource integrating a diverse range of IoT devices and **sophisticated network attack methodologies**. This dataset encompasses both **normal** and **adversarial** network behaviours, providing a general representation of real-world scenarios. Incorporating data from IoT devices such as ThingSpeak-LED, Wipro-Bulb, and MQTT-Temp, as well as simulated attack scenarios involving Brute-Force SSH attacks, DDoS attacks using Hping and Slowloris, and Nmap patterns, RT-IoT2022 offers a **detailed perspective on the complex nature of network traffic**. The bidirectional attributes of network traffic are meticulously captured using the Zeek network monitoring tool and the Flowmeter plugin. Researchers can leverage the RT-IoT2022 dataset to advance the capabilities of Intrusion Detection Systems (IDS), fostering the development of robust and adaptive security solutions for real-time IoT networks.


| Characteristic | Value/Description |
|------------------------|---------------------------------------------------|
| Dataset Characteristics| Tabular, Sequential, Multivariate |
| Subject Area | Engineering |
| Associated Tasks | Classification, Regression, Clustering |
| Feature Type | Real, Categorical |
| # Instances | 123117 |
| # Features | 83 |



### Class Labels

The Dataset contains both Attack patterns and Normal Patterns. 

**Attacks patterns Details:**

1.	DOS_SYN_Hping------------------------94659
2.	ARP_poisioning--------------------------7750
3.	NMAP_UDP_SCAN--------------------2590
4.	NMAP_XMAS_TREE_SCAN--------2010
5.	NMAP_OS_DETECTION-------------2000
6.	NMAP_TCP_scan-----------------------1002
7.	DDOS_Slowloris------------------------534
8.	Metasploit_Brute_Force_SSH---------37
9.	NMAP_FIN_SCAN---------------------28

<br>

**Normal Patterns Details:**
1.	MQTT -----------------------------------8108
2.	Thing_speak-----------------------------4146
3.	Wipro_bulb_Dataset-------------------253 
4. Amazon-Alexa -----------------------86842 (Amazon Alexa is **missing** in the current dataset)



## License

The RT-IoT2022 dataset used in this project is licensed under the Creative Commons Attribution 4.0 International (CC BY 4.0) License.

You can find the original dataset at the [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/942/rt-iot2022).

The full text of the CC BY 4.0 License is available in the [LICENSE](LICENSE.md) file in this repository.