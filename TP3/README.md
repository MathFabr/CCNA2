Lab 1
--------


Le Client2 ne peut pas Ping le client1 ni le client3

	[altins@client2 ~]$ ping 10.1.1.1
	PING 10.1.1.1 (10.1.1.1) 56(84) bytes of data.
	^C
	--- 10.1.1.1 ping statistics ---
	3 packets transmitted, 0 received, 100% packet loss, time 2004ms


	[altins@client2 ~]$ ping 10.1.1.3
	PING 10.1.1.3 (10.1.1.3) 56(84) bytes of data.
	^C
	--- 10.1.1.3 ping statistics ---
	2 packets transmitted, 0 received, 100% packet loss, time 999ms



Par contre le client1 et le client3 peuvent se ping

![ping entre client 1 et client 3](https://github.com/MathFabr/CCNA2/blob/master/TP3/image/ping_client1_client3_tp3_lab1.jpg)