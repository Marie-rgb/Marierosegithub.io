---
permalink: /challenges/
layout: single
author_profile: true
---

## Problem Statement
In this segment I was supposed to interrogate the network traffic with capture and display filters in order to find out what the ports numbers that were used in first full TCP three-way handshake was. Specifying the client and server port numbers. I was to used a file that was provided to figure all these out.

---

## Approach
I first download the file and looked through just trying to understand what was happening exactly while referring to the cheat sheet that was provided for the particular assignment. For instance identifying the symbols used to mean different instances, for example, S to mean SYN and S. to mean SYN and ACK, and . to mean ACK. Therefore, I looked for a bit that showed this in that particular way. I was also able to identify the different IPs associated with these activities.

---

## Tools Used
I used the terminal and run the command tcpdump -r (file name) port (specified the port number). I chose port 43806 particularly beacuse while scanning through the file I was able to find out that that is the prt  number associated with the first SYN.

---

## Screenshots

<div style="display: flex; justify-content: center; gap: 20px; flex-wrap: wrap; margin-top: 10px;">
  <img src="assets/images/img5.jpg" alt="Homepage Screenshot" width="400" style="border-radius: 8px;">
  <img src="assets/images/img6.jpg" alt="Homepage Screenshot" width="400" style="border-radius: 8px;">
</div>

---

## Key Lessons Learned
In this activity my take aways was the ability to identify key details in traffic passed through the network and in that way I will be able to spot irregularities in network traffic and prevent attacks in case of any that may be targeted.

---

