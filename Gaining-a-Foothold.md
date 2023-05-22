<ul>
  <li>Gaining-a-Foothold</li>
  <ol>
    <li>Enumeration:</li>
    <ul>
      <li>Identify the target system and gather information about it using tools like Nmap or manual techniques.</li>
      <li>Example command: <code>nmap -A -T4 [target IP]</code></li>
    </ul>
    <li>Exploitation:</li>
    <ul>
      <li>Identify vulnerabilities or weaknesses in the target system that can be exploited.</li>
      <li>Exploit the vulnerabilities using suitable tools or techniques.</li>
      <li>Example command: <code>exploit.exe [vulnerability]</code></li>
    </ul>
    <li>Initial Access:</li>
    <ul>
      <li>Gain initial access to the target system by utilizing the exploited vulnerability.</li>
      <li>Establish a foothold on the system to maintain access.</li>
      <li>Example command: <code>shell.exe [target IP]</code></li>
    </ul>
  </ol>
</ul>
<br>
<h1>Examples: </h1>

File Edit View Search Terminal 
root@kali:-# nmap -A 
Starting Nmap 7.80 ( 
Nmap scan report for 
root@kali: — 
Help 
_T4 -p- 10.10.10.5 
https://nmap.org ) at 2020-04-13 10:21 EDT 
10.10.10.5 
Host is up (0.032s latency) . 
Not shown: 65533 filtered ports 
PORT STATE SERVICE VERSION 
21/tcp open ftp 
Microsoft ftpd 
I ftp-anon: Anonymous FTP login al awed (FTP code 230) 
| 03-18-17 02:06AM 
| 03-17-17 05:37PM 
1_03-17-17 05:37PM 
I ftp-syst: 
SYST: Windows NT 
aspnet_client 
689 iisstart.htm 
184946 welcome. png 
80/tcp open http 
Microsoft IIS httpd 7.5 
I http-methods: 
Potentially risky methods: TRACE 
l_http-server-header: Microsoft-IIS/ 7.5 
l_http-title: IIS7 
Warning: OSScan results may be unreliable because we could not find at least 1 open and 1 closed port 
Device type: phone I general purposel specialized 
Running (JUST GUESSING): Microsoft Windows Phone120081718.11Vista12012 (92%) 
OS CPE: cpe:/o:microsoft:windows cpe:/o:microsoft:windows_server_2008:r2 cpe:/o:microsoft:windows_7 cpe:/o:microsoft:windows_8.1 cpe:/o:micros 
oft:windows_8 cpe:/o:microsoft:windows_vista::- cpe:/o:microsoft:windows_vista: : spl cpe:/o:microsoft:windows_server_2012 
Aggressive OS guesses: Microsoft Windows Phone 7.5 or 8.0 (92%), Microsoft Windows 7 or Windows Server 2008 R2 (91%), Microsoft Windows Server 
2008 R2 (91%), Microsoft Windows Server 2008 R2 or Windows 8.1 (91%), Microsoft Windows Server 2008 R2 SPI or Windows 8 (91%), Microsoft Wind 
ows 7 Professional or Windows 8 (91%), Microsoft Windows 7 SPI or Windows Server 2008 SP2 or 2008 R2 SPI (91%), Microsoft Windows Vista SPO or 
SPI, Windows Server 2008 SPI, or Windows 7 (91%), Microsoft Windows Vista SP2 (91%), Microsoft Windows Vista SP2, Windows 7 SPI, or Windows S 
erver 2008 (90%) 
No exact OS matches for host (test conditions non-ideal) . 
Network Distance: 2 hops 
Service Info: OS: Windows; CPE: cpe:/o:microsoft:windows 
TRACE-ROUTE (using port 21/tcp) 
HOP RTT 
ADDRESS 
1 
40.14 ms 10.10.14.1 
40.17 ms 10.10.10.5 
OS and Service detection performed. Please report any incorrect results at https://nmap.org/submit/ 
Nmap done: I IP address (I host up) scanned in 100.33 seconds 

<br>
<br>
<br>

echo "this is a test" 
root@kali 
ftp 10.10.10.5 
Connected to 10.10.10.5. 
220 Microsoft FTP Service 
Name (10.10.10.5: root): anonymous 
> test. txt 
331 Anonymous access allowed, send identity (e-mail name) as password. 
Password: 
230 User logged in. 
Remote system type is Windows NT. 
ftP> put test. txt 
local: test . txt remote: test. txt 
200 PORT command successful. 
125 Data connection already open; Transfer starting. 
226 Transfer complete. 
16 bytes sent in 0.00 secs (88.7784 kB/s) 
ftp 


<br>
<br>
<br>

Mozilla Firefox
10.10.10.5/test.txt 
G) 10.10.10.5/test.txt 

<br>
<br>
<br>

Wappalyzer 
lido 
Web franEworks 
Bem- vindo 
Microsoft ASP.NET 
Vite 
Web servers 
IIS IIS 
VE 
Operating systems 
Windows Server 

<br>
<br>
<br>
