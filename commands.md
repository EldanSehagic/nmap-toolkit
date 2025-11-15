Scan mreze -- nmap -sn [default gateway]/[24 ako je subnet 255.255.255.0] -- nmap -sn 192.168.0.1/24 
Scan odredzenog uredzaja na mrezi pinganjem -- nmap -A [IP uredzaja] -- nmap -A 192.168.0.3 
Scan odredzenog uredzaja na mrezi bez pinganja(IoT uredzaji) -- nmap -Pn [IP uredzaja] -- nmap -Pn 192.168.0.3
Scan odredzenog porta na mrezi -- nmap -p [port] [default gateway]/[24 ako je subnet 255.255.255.0] -- 
nmap -p 80 192.168.0.1/24
Scan odredzenih portova na mrezi -- nmap -p [port,port] [default gateway]/[24 ako je subnet 255.255.255.0] -- 
nmap -p 80,8080 192.168.0.1/24
Scan svih portova na mrezi -- nmap -p- [default gateway]/[24 ako je subnet 255.255.255.0] -- nmap -p- 192.168.0.1/24
Test ranjivosti mreze -- nmap --script vuln [default gateway]/[24 ako je subnet 255.255.255.0] -- 
nmap --script vuln 192.168.0.1/24
Test ranjivosti odredzenog uredzaja na mrezi -- nmap --script vuln [IP uredzaja] -- nmap --script vuln 192.168.0.3

