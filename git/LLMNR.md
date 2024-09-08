# LLMNR
**LLMNR Poisoning – Link Local Multicast Name Resolution**

Previously known as NBT-NS – Its just DNS

Key flaw: services utilise a user's username and NTLMv2 hash, username and password when a relevant request is sent over the respective service. 

This is a MITM Attack, (Man in the middle attack). When victim computers are unable to connect to a server, other computers in the network can aid in the connection, by forwarding their NTLM hash and username to aid in connection. Thus, hackers are able to intercept the precious hash keys.

Relevant python key: Responder; mpacket

python Responder.py -I eth0 -w -d --verbose

**Hashcat**

Hashcat allows for the cracking of hashes generated from responder, utilising 

*   Wordlist (rockyou.txt)
*   \-m 5600 (Designating specific hashes)
*   \--force (to force the command to go through)
    
    hashcat -m 5600 ntlmhash.txt rockypu.txt – force