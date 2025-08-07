Description
History has failed us, but no matter. Server source There are two flags in this challenge. Submit flag one here, and flag two in Pachinko Revisited.

Additional details will be available after launching your challenge instance.

we are provided with a server source link and website link.
1. wget https://challenge-files.picoctf.net/c_activist_birds/7eac27979c12e4bd449f03e40a8492044221b7d2a96ac85f1150e30983c56eac/server.tar.gz

2. wget http://activist-birds.picoctf.net:59823/


ok what is pachinko? 
so opening the website reveals a NAND simulator which is a bitwise operator. Still lost...

research led me to a Race Condition vulnerability. 
- simulations are processed simultaneously causing time based bugs.

so basically i need to flood many requests until I get the flag.
- initially it seemed i needed burp and repeater but i researched and it seemed just clicking play animation and submitting many times does the job, at first i get error output, then wrong flag... I knew i was on the right track, until i finally got the flag. interesting.

 picoCTF{p4ch1nk0_f146_0n3_e947b9d7}
