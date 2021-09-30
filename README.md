CSC-641 - Lab 1 - EnzeXu
===========================
This document is used to show the detailed description of each part in assignment1.

****
 
| Project Name | Operating Systems - Lab1 |
| ---- | ---- |
| Author | Enze Xu |
| Due | 09/30/2021 |

****
# Catalog

* [1 Authentication Protocols in IoT](#1-authentication-protocols-in-iot)
  * [1.1 Why is authentication so important in IoT](#11-why-is-authentication-so-important-in-iot)
  * [1.2 IoT device authentication methods](#12-iot-device-authentication-methods)
  * [1.3 IoT device authentication protocols](#13-iot-device-authentication-protocols)
    * [1.3.1 Protocols](#131-protocols)
      * [TLS](#1-tls)
      * [HTTPS](#2-https)
      * [SSH](#3-ssh)
      * [IMAP](#4-imap)
      * [3-D Secure](#5-3-d-secure)
      * [RFID](#6-rfid)
      * [BioAPI](#7-bioapi)
    * [1.3.2 Protocol table](#132-protocol-table)
* [2 Possible Attacks against Protocols](#2-possible-attacks-against-protocols)
  * [2.1 Man-in-the-middle attack to the HTTPS protocol](#21-man-in-the-middle-attack-to-the-https-protocol)
  * [2.2 Multiple attacks to the RFID protocol](#22-multiple-attacks-to-the-rfid-protocol)
  * [2.3 Password recovery attack to the TLS protocol](#23-password-recovery-attack-to-the-tls-protocol)
  * [2.4 Spoofing attack to the 3-D Secure protocol](#24-spoofing-attack-to-the-3-d-secure-protocol)
  * [2.5 Hill-climbing attack to the BioAPI protocol](#25-hill-climbing-attack-to-the-bioapi-protocol)
* [3 References](#3-references)

****


# 1 Purpose of Lab
Today, IoT applications span almost all sectors from medical to home automation and many more, carrying critical and sensitive data. There are different IoT device authentication methods, and each authentication method has its corresponding authentication protocols.


# 2 Compile & Execution Instructions
```shell
$ cd xxx/Operating_Systems_Enze_Xu_lab2
$ cc 
```



