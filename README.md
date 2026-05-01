# 4.Execution_of_NetworkCommands
## AIM :Use of Network commands in Real Time environment
## Software : Command Prompt And Network Protocol Analyzer
## Procedure: To do this EXPERIMENT- follows these steps:
<BR>
In this EXPERIMENT- students have to understand basic networking commands e.g cpdump, netstat, ifconfig, nslookup ,traceroute and also Capture ping and traceroute PDUs using a network protocol analyzer 
<BR>
All commands related to Network configuration which includes how to switch to privilege mode
<BR>
and normal mode and how to configure router interface and how to save this configuration to
<BR>
flash memory or permanent memory.
<BR>
This commands includes
<BR>
• Configuring the Router commands
<BR>
• General Commands to configure network
<BR>
• Privileged Mode commands of a router 
<BR>
• Router Processes & Statistics
<BR>
• IP Commands
<BR>
• Other IP Commands e.g. show ip route etc.
<BR>

## Output
Microsoft Windows [Version 10.0.26200.8246]
(c) Microsoft Corporation. All rights reserved.

C:\Users\Sushmitha>ipconfig

Windows IP Configuration


Wireless LAN adapter Wi-Fi 2:

   Media State . . . . . . . . . . . : Media disconnected
   Connection-specific DNS Suffix  . :

Wireless LAN adapter Wi-Fi 4:

   Media State . . . . . . . . . . . : Media disconnected
   Connection-specific DNS Suffix  . :

Wireless LAN adapter Wi-Fi:

   Connection-specific DNS Suffix  . :
   IPv6 Address. . . . . . . . . . . : 2401:4900:7b80:2ba8:df9c:c40:1499:c0b3
   Temporary IPv6 Address. . . . . . : 2401:4900:7b80:2ba8:19b2:f76e:f435:eee8
   Link-local IPv6 Address . . . . . : fe80::8103:ddef:625a:16f0%14
   IPv4 Address. . . . . . . . . . . : 10.24.244.102
   Subnet Mask . . . . . . . . . . . : 255.255.255.0
   Default Gateway . . . . . . . . . : fe80::60b6:56ff:fe1f:310e%14
                                       10.24.244.230

Ethernet adapter Bluetooth Network Connection:

   Media State . . . . . . . . . . . : Media disconnected
   Connection-specific DNS Suffix  . :

C:\Users\Sushmitha>netstat

Active Connections

  Proto  Local Address          Foreign Address        State
  TCP    10.24.244.102:52005    151.101.157.55:https   ESTABLISHED
  TCP    10.24.244.102:52006    23.100.109.78:https    ESTABLISHED
  TCP    10.24.244.102:52487    20.189.173.11:https    ESTABLISHED
  TCP    10.24.244.102:52488    20.189.173.2:https     ESTABLISHED
  TCP    10.24.244.102:52587    204.79.197.254:https   ESTABLISHED
  TCP    10.24.244.102:55800    204.79.197.222:https   ESTABLISHED
  TCP    10.24.244.102:59262    172.188.155.25:https   ESTABLISHED
  TCP    10.24.244.102:60919    168.62.7.82:https      TIME_WAIT
  TCP    10.24.244.102:60920    57.150.85.1:https      TIME_WAIT
  TCP    10.24.244.102:60921    20.189.173.11:https    FIN_WAIT_1
  TCP    10.24.244.102:62717    relay-29350d34:https   ESTABLISHED
  TCP    127.0.0.1:49676        LAPTOP-BGUKI0IM:49677  ESTABLISHED
  TCP    127.0.0.1:49677        LAPTOP-BGUKI0IM:49676  ESTABLISHED
  TCP    127.0.0.1:49678        LAPTOP-BGUKI0IM:49679  ESTABLISHED
  TCP    127.0.0.1:49679        LAPTOP-BGUKI0IM:49678  ESTABLISHED
  TCP    127.0.0.1:49937        LAPTOP-BGUKI0IM:49938  ESTABLISHED
  TCP    127.0.0.1:49938        LAPTOP-BGUKI0IM:49937  ESTABLISHED
  TCP    [2401:4900:7b80:2ba8:19b2:f76e:f435:eee8]:49310  whatsapp-cdn6-shv-02-maa3:https  CLOSE_WAIT
  TCP    [2401:4900:7b80:2ba8:19b2:f76e:f435:eee8]:49784  [2603:1040:a06:6::2]:https  ESTABLISHED
  TCP    [2401:4900:7b80:2ba8:19b2:f76e:f435:eee8]:49785  [2603:1040:a06:6::2]:https  ESTABLISHED
  TCP    [2401:4900:7b80:2ba8:19b2:f76e:f435:eee8]:52486  [2620:1ec:33::11]:https  ESTABLISHED
  TCP    [2401:4900:7b80:2ba8:19b2:f76e:f435:eee8]:56994  whatsapp-cdn6-shv-01-maa5:5222  ESTABLISHED
  TCP    [2401:4900:7b80:2ba8:19b2:f76e:f435:eee8]:57041  [2606:4700:83b1:d8b7:9aa5:627:ccf5:ac50]:https  ESTABLISHED
  TCP    [2401:4900:7b80:2ba8:19b2:f76e:f435:eee8]:60254  [2606:4700:83b2:7cbc:c2fd:627:5ff2:75c4]:https  ESTABLISHED
  TCP    [2401:4900:7b80:2ba8:19b2:f76e:f435:eee8]:61778  sg-in-f188:https       ESTABLISHED
  TCP    [2401:4900:7b80:2ba8:19b2:f76e:f435:eee8]:62714  [2603:1040:a06:6::2]:https  ESTABLISHED
  TCP    [2401:4900:7b80:2ba8:19b2:f76e:f435:eee8]:65137  [2600:1901:0:47fc::]:https  ESTABLISHED

C:\Users\Sushmitha>nslookup
Default Server:  UnKnown
Address:  10.24.244.230

> traceroute
Server:  UnKnown
Address:  10.24.244.230

*** UnKnown can't find traceroute: Non-existent domain
> exit

C:\Users\Sushmitha>tracert google.com

Tracing route to google.com [2404:6800:4007:815::200e]
over a maximum of 30 hops:

  1     *      100 ms     2 ms  2401:4900:7b80:2ba8::45
  2     *        *        *     Request timed out.
  3   100 ms    95 ms    99 ms  2401:4900:0:fdf::1
  4   115 ms    98 ms   105 ms  2401:4900:0:6fc::4
  5   116 ms    98 ms    99 ms  2401:4900:0:6f5::1
  6     *        *        *     Request timed out.
  7   576 ms   302 ms    38 ms  2404:a800:3a00:1::7d9
  8     *     1151 ms   197 ms  2404:a800::92
  9     *        *        *     Request timed out.
 10    87 ms   256 ms   503 ms  2404:6800:8202:1c0::1
 11   403 ms    99 ms   105 ms  2001:4860:0:1::56e
 12     *      109 ms  1217 ms  2001:4860:0:1::40e8
 13   375 ms   612 ms   304 ms  2001:4860:0:1::8809
 14   746 ms   278 ms   100 ms  2001:4860:0:1::55cd
 15   163 ms   101 ms   103 ms  lcmaaa-ar-in-x0e.1e100.net [2404:6800:4007:815::200e]

Trace complete.

C:\Users\Sushmitha>nslookup google.com
Server:  UnKnown
Address:  10.24.244.230

Non-authoritative answer:
DNS request timed out.
    timeout was 2 seconds.
Name:    google.com
Address:  142.250.67.46


C:\Users\Sushmitha>ping google.com

Pinging google.com [2404:6800:4007:805::200e] with 32 bytes of data:
Reply from 2404:6800:4007:805::200e: time=284ms
Reply from 2404:6800:4007:805::200e: time=79ms
Reply from 2404:6800:4007:805::200e: time=595ms
Reply from 2404:6800:4007:805::200e: time=130ms

Ping statistics for 2404:6800:4007:805::200e:
    Packets: Sent = 4, Received = 4, Lost = 0 (0% loss),
Approximate round trip times in milli-seconds:
    Minimum = 79ms, Maximum = 595ms, Average = 272ms

C:\Users\Sushmitha>getmac

Physical Address    Transport Name
=================== ==========================================================
28-2E-89-73-4E-C7   Media disconnected

C:\Users\Sushmitha>username
'username' is not recognized as an internal or external command,
operable program or batch file.

C:\Users\Sushmitha>whoami
laptop-bguki0im\sushmitha

C:\Users\Sushmitha>hostname
LAPTOP-BGUKI0IM

C:\Users\Sushmitha>date
The current date is: 01-05-2026
Enter the new date: (dd-mm-yy) 01-05-2026
A required privilege is not held by the client.

C:\Users\Sushmitha>time
The current time is: 21:16:56.05
Enter the new time: 09:17:55.00
A required privilege is not held by the client.

C:\Users\Sushmitha>systeminfo
                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        
Host Name:                     LAPTOP-BGUKI0IM
OS Name:                       Microsoft Windows 11 Home Single Language
OS Version:                    10.0.26200 N/A Build 26200
OS Manufacturer:               Microsoft Corporation
OS Configuration:              Standalone Workstation
OS Build Type:                 Multiprocessor Free
Registered Owner:              Sushmitha
Registered Organization:       HP
Product ID:                    00342-42727-75788-AAOEM
Original Install Date:         06-08-2025, 20:13:29
System Boot Time:              25-04-2026, 06:01:20
System Manufacturer:           HP
System Model:                  HP Laptop 15-fd0xxx
System Type:                   x64-based PC
Processor(s):                  1 Processor(s) Installed.
                               [01]: Intel64 Family 6 Model 186 Stepping 3 GenuineIntel ~1300 Mhz
BIOS Version:                  AMI F.12, 20-08-2024
Windows Directory:             C:\windows
System Directory:              C:\windows\system32
Boot Device:                   \Device\HarddiskVolume1
System Locale:                 en-us;English (United States)
Input Locale:                  00004009
Time Zone:                     (UTC+05:30) Chennai, Kolkata, Mumbai, New Delhi
Total Physical Memory:         16,028 MB
Available Physical Memory:     6,453 MB
Virtual Memory: Max Size:      17,052 MB
Virtual Memory: Available:     5,075 MB
Virtual Memory: In Use:        11,977 MB
Page File Location(s):         C:\pagefile.sys
Domain:                        WORKGROUP
Logon Server:                  \\LAPTOP-BGUKI0IM
Hotfix(s):                     4 Hotfix(s) Installed.
                               [01]: KB5082417
                               [02]: KB5054156
                               [03]: KB5083769
                               [04]: KB5088467
Network Card(s):               1 NIC(s) Installed.
                               [01]: Bluetooth Device (Personal Area Network)
                                     Connection Name: Bluetooth Network Connection
                                     Status:          Media disconnected
Virtualization-based security: Status: Running
                               Required Security Properties:
                                     Base Virtualization Support
                               Available Security Properties:
                                     Base Virtualization Support
                                     Secure Boot
                                     DMA Protection
                                     UEFI Code Readonly
                                     SMM Security Mitigations 1.0
                                     Mode Based Execution Control
                                     APIC Virtualization
                               Services Configured:
                                     Hypervisor enforced Code Integrity
                               Services Running:
                                     Hypervisor enforced Code Integrity
                               App Control for Business policy: Enforced
                               App Control for Business user mode policy: Off
                               Security Features Enabled:
Hyper-V Requirements:          A hypervisor has been detected. Features required for Hyper-V will not be displayed.

C:\Users\Sushmitha>dir
 Volume in drive C is Windows
 Volume Serial Number is 7C67-6D4D

 Directory of C:\Users\Sushmitha

01-05-2026  20:31    <DIR>          .
24-03-2026  20:53    <DIR>          ..
17-11-2025  16:18    <DIR>          .anaconda
17-11-2025  16:23                25 .condarc
17-11-2025  16:18    <DIR>          .continuum
19-09-2025  18:25                48 .gitconfig
04-09-2025  06:09    <DIR>          .idlerc
30-04-2026  13:03    <DIR>          .ipynb_checkpoints
17-11-2025  17:27    <DIR>          .ipython
17-11-2025  17:35    <DIR>          .jupyter
17-11-2025  17:27    <DIR>          .matplotlib
17-11-2025  17:28    <DIR>          .spyder-py3
06-09-2025  03:44    <DIR>          .vscode
17-11-2025  16:25    <DIR>          anaconda3
01-05-2026  20:31                 0 date
08-12-2025  12:16    <DIR>          Documents
01-05-2026  20:20    <DIR>          Downloads
01-05-2026  20:31                 0 getmac
01-05-2026  20:31                 0 hostname
06-08-2025  20:16    <DIR>          Links
26-04-2026  18:30            21,146 ML EX- 1.ipynb
27-04-2026  14:35            48,509 ML EX-2.ipynb
06-08-2025  20:16    <DIR>          Music
01-05-2026  20:31                 0 netstat
22-11-2025  18:11    <DIR>          New folder
01-05-2026  20:31                 0 nslookup
01-05-2026  20:07    <DIR>          OneDrive
08-12-2025  12:16    <DIR>          Pictures
01-05-2026  20:31                 0 ping
06-08-2025  20:16    <DIR>          Saved Games
06-08-2025  20:33    <DIR>          Searches
15-09-2025  13:46    <DIR>          student
17-11-2025  17:20    <DIR>          susi
01-05-2026  20:31                 0 systeminfo
01-05-2026  20:31                 0 time
01-05-2026  20:31                 0 tracert
30-04-2026  13:05            29,414 Untitled.ipynb
27-04-2026  20:44            57,280 Untitled2.ipynb
27-04-2026  21:03            52,066 Untitled3.ipynb
30-04-2026  12:31            25,720 Untitled5.ipynb
01-05-2026  20:31                 0 username
18-03-2026  22:25    <DIR>          Videos
01-05-2026  20:31                 0 whoami
              19 File(s)        234,208 bytes
              24 Dir(s)  357,943,369,728 bytes free

C:\Users\Sushmitha>cd
C:\Users\Sushmitha

C:\Users\Sushmitha>arp -a

Interface: 10.24.244.102 --- 0xe
  Internet Address      Physical Address      Type
  10.24.244.230         62-b6-56-1f-31-0e     dynamic
  10.24.244.255         ff-ff-ff-ff-ff-ff     static
  224.0.0.22            01-00-5e-00-00-16     static
  224.0.0.251           01-00-5e-00-00-fb     static
  224.0.0.252           01-00-5e-00-00-fc     static
  239.255.102.18        01-00-5e-7f-66-12     static
  239.255.255.250       01-00-5e-7f-ff-fa     static
  255.255.255.255       ff-ff-ff-ff-ff-ff     static

C:\Users\Sushmitha>pathping google.com

Tracing route to google.com [2404:6800:4007:805::200e]
over a maximum of 30 hops:
  0  LAPTOP-BGUKI0IM [2401:4900:7b80:2ba8:19b2:f76e:f435:eee8]
  1  2401:4900:7b80:2ba8::45
  2     *        *        *
Computing statistics for 25 seconds...
            Source to Here   This Node/Link
Hop  RTT    Lost/Sent = Pct  Lost/Sent = Pct  Address
  0                                           LAPTOP-BGUKI0IM [2401:4900:7b80:2ba8:19b2:f76e:f435:eee8]
                                2/ 100 =  2%   |
  1   35ms     2/ 100 =  2%     0/ 100 =  0%  2401:4900:7b80:2ba8::45

Trace complete.

C:\Users\Sushmitha>
## Result
Thus Execution of Network commands Performed 
