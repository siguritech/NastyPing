# NastyPing

komputer pierwszy wysyła pinga:

$ nping --icmp -c 1 --data-string 'wiadomosc' 192.168.0.10

komputer drugi słucha nadchodzącego pakietu

$ sudo python3 icmpListner.py
