UDPChat
=======

command line P2P chat over UDP

## Description
This is a simple chat client over UDP. It uses the principal known as UDP hole punching to get past NATs.

##Usage
1. Find the jar file in /jar
2. Get your friend to download the same file
3. Exchange IP address information with the friend (type my ip into google)
4. Pick a port (e.g 6004)
5. Execute the jar as follows:
```java -jar UDPChat.jar RemoteIP Port Name```

RemoteIP: The remote IP address
Port: The port number you want to connect on
Name: The name you want to appear by your chat text

##Details
This uses UDP hole punching to get through any NATs you and your friend may be behind. Normally you would discover
eachother's IP addresses through some external server, but in this simple example we just exchange that information manually.
