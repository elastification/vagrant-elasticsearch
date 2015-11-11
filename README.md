Vagrant Elastichsearch Test Evironments
=======================================

This vagrant box is based on ansible provisioning

---

Requirements
============

- Virtual Box (min: 4.3.6)
- Vagrant (min: 1.4.3)
- Ansible (min: 1.4.4)

---

Virtual Boxes (Servers)
=======================

There are some boxes available:

| Vagrant Box Name | Elasticsearch Version | Ip Address when started |
| ---------------- | :-------------------: | ----------------------: |
| elastic_0_90_13 | 0.90.13 | 192.168.33.109 |
| elastic_1_0_2 | 1.0.2 | 192.168.33.102 |
| elastic_1_0_3 | 1.0.3 | 192.168.33.103 |
| elastic_1_1_0 | 1.1.0 | 192.168.33.110 |
| elastic_1_1_1 | 1.1.1 | 192.168.33.111 |
| elastic_1_1_2 | 1.1.2 | 192.168.33.112 |
| elastic_1_2_1 | 1.2.1 | 192.168.33.121 |
| elastic_1_2_2 | 1.2.2 | 192.168.33.122 |
| elastic_1_2_3 | 1.2.3 | 192.168.33.123 |
| elastic_1_3_0 | 1.3.0 | 192.168.33.130 |
| elastic_1_3_1 | 1.3.1 | 192.168.33.131 |
| elastic_1_3_2 | 1.3.2 | 192.168.33.132 |
| elastic_1_3_3 | 1.3.3 | 192.168.33.133 |
| elastic_1_3_4 | 1.3.4 | 192.168.33.134 |
| elastic_1_3_5 | 1.3.5 | 192.168.33.135 |
| elastic_1_3_6 | 1.3.6 | 192.168.33.136 |
| elastic_1_3_7 | 1.3.7 | 192.168.33.137 |
| elastic_1_3_8 | 1.3.8 | 192.168.33.138 |
| elastic_1_3_9 | 1.3.9 | 192.168.33.139 |
| elastic_1_4_0 | 1.4.0 | 192.168.33.140 |
| elastic_1_4_1 | 1.4.1 | 192.168.33.141 |
| elastic_1_4_2 | 1.4.2 | 192.168.33.142 |
| elastic_1_4_3 | 1.4.3 | 192.168.33.143 |
| elastic_1_4_4 | 1.4.4 | 192.168.33.144 |
| elastic_1_4_5 | 1.4.5 | 192.168.33.145 |
| elastic_1_5_0 | 1.5.0 | 192.168.33.150 |
| elastic_1_5_1 | 1.5.1 | 192.168.33.151 |
| elastic_1_5_2 | 1.5.2 | 192.168.33.152 |
| elastic_1_6_0 | 1.6.0 | 192.168.33.160 |
| elastic_1_6_1 | 1.6.1 | 192.168.33.161 |
| elastic_1_6_2 | 1.6.2 | 192.168.33.162 |
| elastic_1_7_0 | 1.7.0 | 192.168.33.170 |
| elastic_1_7_1 | 1.7.1 | 192.168.33.171 |
| elastic_1_7_2 | 1.7.2 | 192.168.33.172 |
| elastic_1_7_3 | 1.7.3 | 192.168.33.173 |

---

Start the Boxes
===============
Every command is from within this project folder.

If you want to have an short overview of available boxes
```
vagrant status
```

Starting a specific box
```
vargant up elastic_0_90_13
```

SSH into specific Box
```
vargant ssh elastic_0_90_13
```

Starting all boxes (be carefull. there are many boxes):
```
vargant up
```
