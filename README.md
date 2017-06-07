gitdoc
======

[![Greenkeeper badge](https://badges.greenkeeper.io/ayxos/gitdoc.svg)](https://greenkeeper.io/)

in order to change listen port, it is neccessary create an iptables rule 


iptables -t nat -A PREROUTING -p tcp --dport 80 -j REDIRECT --to-port YOUR_CUSTOM_PORT
