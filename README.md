# Anonymous-authentication-of-vehicles-in-v2x-environment-and-encryption-of-CAM-messages

This project focuses on ensuring **anonymous authentication of vehicles** in a V2X (Vehicle-to-Everything) environment and **securing CAM (Cooperative Awareness Messages)** through encryption, using simulation tools such as **SUMO**, **OMNeT++**, and **Veins 5.3.1**.

## 🚗 Overview

With the rapid development of V2X communication, it's crucial to preserve driver privacy while maintaining data integrity and safety. This project implements a secure, anonymous communication system for transmitting CAM messages among vehicles.

## 🛠 Tools Used

- **SUMO** – Traffic simulation
- **OMNeT++** – Network simulation
- **Veins 5.3.1** – Framework to integrate SUMO and OMNeT++

## 🎯 Features

- Anonymous authentication of vehicle nodes
- End-to-end CAM message encryption
- Security and privacy layer integration in Veins
- Analysis of transmission delays and packet security

## 📊 Results

- Improved anonymity with negligible delay overhead
- Encrypted CAMs showed enhanced privacy
- Graphs and logs provided in `/Results`

## 📂 Folder Structure

- `/SUMO`: Simulation setup for urban mobility
- `/OMNeT++`: Network modules and configurations
- `/Veins`: Custom modules integrated for secure CAM handling
- `/Results`: Screenshots and metrics
- `/Docs`: Presentation and additional documents

## 👨‍💻 Authors

- Anirudh Bansal – RA2211003011208  
- Adittya Sengupta – RA2211003011215  
- Rushil Ghetiya – RA2211003011217  
under the guidance -  Dr. Pavithra Guru


Implementation plan:
--------------------------------

 
 Step 1: Initially, Construct the network with 100- Vehicle nodes,4-Rsu and 1-Enrolment authority. The placement of RSU and Vehicles depends on the sumo configuration.

 Step 2: Next, the Enrolment authority registers the Vehicles with certificates based on the decisional Diffie–Hellman (DDH) assumption.
 
 Step 3: Next, in RSU authenticate the Vehicles .

 Step 4: Next, After that authentication of the vehicle , the vehicle derives a symmetric key from the RSU zone.

 Step 5: Next, Encrypt the Cooperative Awareness Message (CAM) by using chosen-plaintext attack (CPA)  secure encryption scheme.
 
 Step 6: Next, Perform the encrypted message transmission in v2X.

 [The process based on your requirement]
 
 Step 7: Finally, Generate the graph for Packet Delivery Ratio, Message Overhead, Delay, Throughput and Energy Consumption
