# Scanning the Local Network for the Open Ports

Network is a Medium (Wireless)  through which all the Electronic gadgets like PC, Laptop, Mobile Phones & so on.. can share the Resources & Information. Internet is the Network of Networks.

Here we use the Port Scanning tools like Nmap which stands for the Network Mapper to identify the Open ports from the Local Network or Wifi & we can perform exploitation using the Tools like Wireshark.
We also have the UI tool for the Nmap i.e, Zenmap

With the help of these Open Ports a Intruder can easily get into Network & He/she can perform the Active & Passive Cyber Attacks on a Victim.

Now in order to see your Local Network IP range in the Terminal Emulator (Kali Linux):

``` bash
ip r
```
Then to perform the TCP SYN scan:
``` bash
Nmap -sS 192.168.1.0/24
```
Then we can see the IPv4 address of all the devices that are being connected to our local wifi Network along with the Port status like Open, Filtered,closed, Ignored.

Inorder to Capture the Packets using the Wireshark intially open it under the root mode.
Then Select the Interface if you are using the Wired connection then select eth0 i.e, Ethernet. As I was having the Wifi Adapter with me then I've selected wlan0 Interface. 

After this the Wireshark starts Capturing the Packets so just open the browser & search for something for eg. I searched for youtube & then come back Wireshark tab & select stop Capturing button.
```bash
www.youtube.com
```
Now we are able to see a lot of Packets transmitted from our device to the youtube's Network.

## Installation

If You are not having the Hyper Visior application then Install the Nmap from here   **https://nmap.org/download**

If You have the Hyper Visior application on your Host OS like the Virtual Box or the VM Ware then simply Install the Famous Linux Distribution that is Kali Linux from here **https://www.kali.org/**

## Tech Stack

Used the Hyper Visior Application that is Oracle Virtual Box

Used the Linux Distribution i.e, Kali Linux

## Screenshots

![Screenshot](https://github.com/PavanKumarCCB-001/ElevateLabs_Internship/tree/main/Assets/gateway_ip.png)

![Screenshot](Assets/packetCap.png)

![Screenshot](Assets/tcp_syn-scan.png)

![Screenshot](Assets/tcp_syn-scan_zenmap.png)
