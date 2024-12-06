# Firewalls
 Firewalls work by filtering incoming and outgoing network traffic on a device or website. They are governed by a set of rules and are configured to match user needs. Here is a simple breakdown of how firewalls work. They act almost like a bouncer at a bar, only allowing those who can be in the bar to go in or out. There are two main types of firewalls, Hardware and software firewalls, but they both provide the same function of protecting your data. 
## Hardware Firewalls 
Hardware firewalls are physical and installed onto devices like your internet router. These work to protect the devices on your network from threats coming from the internet at large. 
## Software Firewalls
Software firewalls are firewalls that are installed directly on your device and work to ensure that the data you're getting from the internet is safe. It is possible to run both hardware and software firewalls simultaneously. 

## What are Firewalls protecting you from? 
Firewalls protect you from a variety of threats such as viruses, spam, and denial-of-service attacks that could be harmful to you. 
1. Viruses are just like how they sound, they're a type of bad code (often called malware) that can be spread from computer to computer, similar to a cold. It attempts to copy itself by gaining access to your hard drive and spreading it to other computers or devices. They can be disguised as links, attachments, files, etc. Firewalls act to stop viruses by scanning these data packets to make sure that a virus is not hitching a ride along and attempting to gain access to your device.
2. Spam: Just like spam emails, spam is an annoying amount of requests or messages that may start to slow down your network or overwhelm your computer or yourself. Firewalls work to stop these spams from reaching your devices or networks so that you can keep surfing the web in peace.
3. Denial-of-service: Denial-of-service attacks are when bots or hackers attempt to slow down networks by submitting lots and lots of access requests to the point that the network might shut down. Often, these sorts of attacks are more targeted towards larger networks like that of a company, but firewalls still work to address these floods of requests before it becomes critical. 

## How Firewalls Work
As we've stated before, firewalls act as the bouncers for data coming onto your computer to keep you safe, but how exactly do they identify what data is a threat and what is not? 
1. Packet Filtering: The oldest and most basic type of firewall, it is used to asses small pieces of data attempting to come through the firewall. It does this by looking at the header of the data packet, which contains information about IP addresses, data sources, and the transfer protocols that that specific packet of data is using. Often these firewalls will have set rules for what a data packet needs to gain entry, and if a data packet does not meet these rules, it is not allowed through.
2. Circuit-level Gateways: This type of firewall system works by only analyzing the [transfer protocol](Encryption.md) handshakes to ensure that the data has had a secure journey on its way to the firewall. If the firewall finds that the data did not use a safe transfer method, it will not be allowed through.
3. Stateful Inspection: This is similar to the Packet Filtering firewall, except this one is a lot more in-depth. If Packet Filtering were you going through the metal detectors at TSA, Stateful Inspection is you getting a full-on pat down and inspection from a TSA agent. This firewall inspects every single packet that is attempting to enter the network, rather than just the packet header.


[Home](README.md)
   




