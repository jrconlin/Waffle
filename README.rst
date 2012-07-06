Waffle
======

A 20% project to build a one page sync client.

Sigh,
So this project probably won't see the light of day. Turns out that there's a
significant crypto issue between how sync and the sjcl support AES 
encryption. Sync does CBC style blocks, where sjcl does ECL style. This means
that the libraries are incompatible, unless I were to add CBC functions to 
the sjcl. I'm not a crypto guy and the golden rule about this stuff is 
"Don't". If I get some time to beat on things, or I see that the sjcl
implemented CBC blocks, then I'll pick up from where I left off.

argh.

