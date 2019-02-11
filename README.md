# tcp-based-chatroom-socket
It a simple POC based on tcp socket connection :
i) It includs how to create a connection and connect using IP and port of server from client as chat room user.

# To run this application on your local system
* Get your system local IP and choose one port(5555)


# To run Server side script:
# python server.py local-ip port
# eg: python server.py 127.0.0.1 5555

# To run client side script:
# python client.py local-ip port
# eg: python client.py 127.0.0.1 5555


# This connection can handle 100 connection at a time:
This number can be increased as per convenience.
change this 100 to your requered number

server.listen(100)

