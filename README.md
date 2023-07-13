
**OSWireless_G1**


**Instructions to generate algorithms:**


First, unzip OSWireless_v1.zip

Go to **OSW-G2\NeXT-OS** and execute 

1. **g2_demo1.py** to generate algorithms for Experiment 1: MSMH PowRate ThrptMax
2. **g2_delay.py** to generate algorithms for Experiment 2: MSMH PwrRate DlyMin
3.** g2_mobile.py** to generate algorithms for Experiment 3: MSMHMob Mov ThrptMax

All the generated algorithms will be stored in a separate repository

1. **NCP-g2_rate_power** - for Experiment 1: MSMH PowRate ThrptMax
2. **NCP-g2_min_delay** - for Experiment 2: MSMH PwrRate DlyMin
3. **NCP-g2_location** - for Experiment 3: MSMHMob Mov ThrptMax
 
**Instructions to execute the algorithms on SDR Testbed:**


Go to OSW-G2\NeXT-PPS

**netcfg_g2.py**
1. First configure the IP addresses of USRPs and Laptops - lines 373 - 417
2. Change the scheme based on the experiment - line 180

**pc_1.py and pc2.py**

These two files can be used to start two sessions with 4 nodes each

#####################################################

If you use this program for your work/research, please cite:
S. K. Moorthy, Z. Guan, N. Mastronarde, E. S. Bentley, M. Medley, "OSWireless: Enhancing Automation for Optimizing Intent-Driven Software-Defined Wireless Networks," in Proc. of IEEE International Conference on Mobile Ad-Hoc and Smart Systems (MASS), Denver, Colorado, October 2022. 

BibTex 
@inproceedings{oswireless,
author = "S. K. Moorthy and Z. Guan and N. Mastronarde and E. S. Bentley and M. Medley",
title = "{OSWireless: Enhancing Automation for Optimizing Intent-Driven Software-Defined Wireless Networks}",
booktitle = "Proc. of IEEE International Conference on Mobile Ad-Hoc and Smart Systems (MASS)",
address = "Denver, Colorado",
month = "October",
year = "2022"
}

