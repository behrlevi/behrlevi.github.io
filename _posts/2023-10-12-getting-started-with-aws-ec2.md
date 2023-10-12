---
date: 2023-10-12 20:00:24
layout: post
title: "Getting started with AWS EC2"
subtitle:
description:
image: /assets/img/OIP.jpg
optimized_image:
category: cloud
tags:
author: Béhr
paginate: false
---
Getting started with EC2 can be pretty straightforward ... unless you have not deleted your default VPC.

I want to record some of my early experiences setting up an EC2 instance.

I could not figure out what I was doing wrong when I tried to connect to my newly created instances.
The firewall is allowing port 22 TCP for SSH.
Public IPV4 address is auto-generated.
Also checked that the VPC had a default gateway associated with it, had a correct CIDR setup and a subnet for the availability zone.

After some digging, I found the missing piece: You need to set routing to the default gateway.
