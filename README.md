# NetNeedle

We believe that hiding a needle in a haystack is easier if the needle looks like hay.

NetNeedle is a network steganography tool. It allows users to set up an encrypted control channels or chat with each other in
a ways that resist detection. By default, both ends will look like they are pinging each other. Examinations of the
"payload" section will show a data that is identical to a normal ICMP ping. All of the usable data is hidden in the IP
headers in values that will be random. 

There is also a "TCP" mode. The communication will look like an HTTP GET request, by default. However, users can configure the software to masquerade as other protocols, if they wish.

The chat client allows two way communication, but it is a control channel, by default.
