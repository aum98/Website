---
title: Things I've been working on
author: Aum Mhapankar
date: '2019-12-15'
slug: things-i-ve-been-working-on
categories: []
tags: []
description: ''
---

# RStudio
Here are links to projects I have worked on that involved using RStudio to combine datasets, run biostatistical tests, and generate plots to model data and determine trends between variables.


[http://127.0.0.1:7240/Project1/](/Project1)



[http://127.0.0.1:5046/projects/](/Project2)

![](/blog/2015-07-23-r-rmarkdown_files/cancer.jpg)

# Python

Some of the Python material I have worked recently on has involved basic statistical analysis of datasets such as faithful in which our input code was:

import pandas as pd
faithful=pd.read_csv("https://vincentarelbundock.github.io/Rdatasets/csv/datasets/faithful.csv")

type(faithful)
faithful.head()

print("Max eruptions: ")
max(faithful.eruptions)

print("Min eruptions: ")
min(faithful.eruptions)

print("Max waiting: ")
max(faithful.waiting)

min(faithful.waiting)






which outputted:

pandas.core.frame.DataFrame

![](/blog/2019-12-15-things-i-ve-been-working-on_files/pic.jpg)

Max eruptions: 
5.1
Min eruptions: 
1.6
Max waiting: 
96
Min waiting: 
43






I have also graphed data to visualize different relationships between variables, such as the eruption times and waiting times of the faithful geyser:

I inputted:

plt.hist(faithful['eruptions'])

print("eruptions")

plt.show();

plt.hist(faithful['waiting'])

print("waiting")

plt.show();






and python outputted:

![](/blog/2019-12-15-things-i-ve-been-working-on_files/pic3.jpg)



I also worked with strings of text using findall functions to extract IP addresses.

In this example, I inputted:

string2="Jan 13 00:48:59: DROP service 68->67(udp) from 213.92.153.167 to 69.43.107.219, prefix: \"spoof iana-0/8\" \
(in: eth0 69.43.112.233(38:f8:b7:90:45:92):68 -> 217.70.100.113(00:21:87:79:9c:d9):67 UDP len:576 ttl:64) \
Jan 13 12:02:48: ACCEPT service dns from 74.125.186.208 to firewall(pub-nic-dns), prefix: \"none\" \
(in: eth0 74.125.186.208(00:1a:e3:52:5d:8e):36008 -> 140.105.63.158(00:1a:9a:86:2e:62):53 UDP len:82 ttl:38) \
Jan 13 17:44:52: DROP service 68->67(udp) from 172.45.240.237 to 217.70.177.60, prefix: \"spoof iana-0/8\" \
(in: eth0 216.34.90.16(00:21:91:fe:a2:6f):68 -> 69.43.85.253(00:07:e1:7c:53:db):67 UDP len:328 ttl:64) \
Jan 13 17:52:08: ACCEPT service http from 213.121.184.130 to firewall(pub-nic), prefix: \"none\" \
(in: eth0 213.121.184.130(00:05:2e:6a:a4:14):8504 -> 140.105.63.164(00:60:11:92:ed:1b):80 TCP flags: ****S* len:52 ttl:109)"


re.findall(r'\d{2,3}\.\d{2,3}\.\d{2,3}\.\d{2,3}',string2)




And Python outputted the relevant IP addresses from the text:

['213.92.153.167',
 '69.43.107.219',
 '69.43.112.233',
 '217.70.100.113',
 '74.125.186.208',
 '74.125.186.208',
 '140.105.63.158',
 '172.45.240.237',
 '217.70.177.60',
 '216.34.90.16',
 '69.43.85.253',
 '213.121.184.130',
 '213.121.184.130',
 '140.105.63.164']
 
 
 
 
These are just a few examples of the useful Python coding I did in Computational Biology to conduct statistical analysis, graph and model data, and extract pertinent information from data.




