
### Name:
wyu324

### Task 1: 

####  Nmap Network Scan (Step 1):
(1) IP address of my Kali VM is 10.0.2.4
(2) 10.0.2.5 might be the Shellshock VM

Nmap scan report for 10.0.2.4
Host is up (0.00010s latency).
Nmap scan report for 10.0.2.5
Host is up (0.00015s latency).


####  Port Scan (Step 2):
(1)port 80 is handling HTTP traffic, which is the port to submit for the task

Starting Nmap 7.91 ( https://nmap.org ) at 2024-09-16 17:00
Nmap scan report for 10.0.2.5
Host is up (0.00014s latency).
PORT      STATE SERVICE
22/tcp    open  ssh
80/tcp    open  http
443/tcp   open  https


### Task 2: 
