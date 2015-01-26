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
| elastic_1_3_2 | 1.3.2 | 192.168.33.132 |
| elastic_1_4_1 | 1.4.1 | 192.168.33.141 |


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

Starting all boxes:
```
vargant up
```
