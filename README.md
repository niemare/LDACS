# Proof of Security of Mutual Authentication and Key Exchange in the L-band Digital Aeronautical Communication System LDACS

Aeronautical communications systems are currently undergoing a modernization process. Analogue legacy systems shall be replaced with modern digital alternatives, offering higher bandwidth, increasing capacity and paving the way for Unmanned Aeronautical Vehicles (UAVs). One modern candidate technology is the L-band Digital Aeronautical Communications System (LDACS), enabling long-range safety-critical digital communications between aircraft and ground. As with any modern wireless communications system, LDACS is prone to cyber-attacks. These issues were addressed in former research, where a secure cell-attachment procedure for LDACS, based on a modified Station to Station (STS) Mutual Authentication and Key Establishment (MAKE) protocol, was proposed. However, as of now, its security has not been proven. The contribution of this paper is the formal verification of the executability and security of the LDACS cell-attachment procedure using the symbolic model checker Tamarin. The achieved results proved that the suggested cell-attachment procedure for LDACS is workable and enables secure communication between aircraft and ground.

## Authors: 

Nils Mäurer, Thomas Gräupl: Institute of Communication and Navigation, German Aerospace Center (DLR), Wessling, Germany

Christoph Gentsch: Institute of Data Science, German Aerospace Center (DLR), Jena, Germany

Corinna Schmitt: Research Institute CODE, Universität der Bundeswehr München, Neubiberg, Germany

## **Paper**

- Mäurer, N., Gentsch, C., Gräupl, T. and Schmitt, C. "Formal Security Verification of the Station-to-Station based Cell-attachment Procedure of LDACS.", In Proceedings of the 18th International Conference on Security and Cryptography (SECRYPT 2021) 

## **File structure:**

- `ldacs_auth_gsc_as.spthy`

  - contains a formal analysis of the proposed mutual authentication and key agreement protocols of LDACS and to prove their security.
  
- `tamarin.png`

  - contains a grpahical output of the proof of MAKE protocol 
  

## The Tamarin prover repository

For installation and usage instructions of the Tamarin prover see chapter 2 of the manual:

https://tamarin-prover.github.io/manual/book/002_installation.html

## Build environment

Tamarin prover: v1.4.1

OS: Linux based Ubuntu 18.04 Laptop

Configuration: Intel(R) Core(TM) i7-8650U CPU 16GB of RAM

Verification time: 20.158s  

