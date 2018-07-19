# Python
# script to get the host name
import socket
host_name=socket.gethostname()
host_ip = socket.gethostbyname(host_name)

print ("hostname:", host_name)
print ("hostip:",host_ip)
