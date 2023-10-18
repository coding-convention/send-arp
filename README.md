# ARP Spoofing Attack Program

This program is a C++ program that performs an ARP Spoofing attack. ARP Spoofing is a type of network attack that allows an attacker to impersonate other devices on the network and conduct man-in-the-middle attacks.

## Usage

To run the program, follow these instructions:

syntax: send-arp-test <interface> <sender ip> <target ip>
sample: send-arp-test wlan0 10.1.1.2 10.1.1.3


- `<interface>`: Specify the name of the network interface on which you want to perform ARP Spoofing.
- `<sender ip>`: Specify the IP address of the sender you want to impersonate.
- `<target ip>`: Specify the IP address of the target device (victim) whose traffic you want to intercept.

## Execution Example

Here's an example of running the program:

$ send-arp-test wlan0 10.1.1.2 10.1.1.3

This command will perform an ARP Spoofing attack on the `wlan0` interface, with 10.1.1.2 as the sender's IP address and 10.1.1.3 as the target.


**This program is intended for educational or security testing purposes. It should not be used for illegal activities or unauthorized network intrusions.**
