Hostname to IP Tool
Purpose of this program is for an automated way to get the IP addresses of a list of hostnames. Then after the hostnames are translated to IP addresses with the text document IPaddress.txt, it will then ping these addresses to see if they are alive or not. The results of the pings are placed in IPaddress2.txt.
All you have to do is input all the hostnames in the hostname.txt, one line per hostname. The program will do the rest of the work.
Make sure the last line on hostname.txt DOES NOT HAVE A EMPTY LINE, otherwise you'll get a 0.0.0.0 entry, not really a big deal however.
Why might you want to use this program? I had a ticket where they included a lot of hostnames but no IP address information was given about these hostname. This will save you a lot of time translating the hostnames and pinging them to see if these nodes are alive.
Required Python Virtual Environment: socket, platform, subprocess