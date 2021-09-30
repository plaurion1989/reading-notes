# HTTP Request Lifecycle
1. Local Processing
Your browser extracts several things:
* protocol
* host
* optional port
* resource path
* query strings (if specified)

it then searches cache to resolve IP from a DNS server
2. Resolve an IP address
3. Establish a TCP Connection
4. Send and HTTP Request
5. Client sends a FIN(finish) packet at the TCP
6. Server responds with and ACK(acknowledgement) and FIN packet
7. finishes up the four way hand shake and POW! you have a simplified to the already simplified(in reading) HTTP request

## HTTP Request in Java
Start by using built-in Java class **HttpUrlConnection**. It allows us to perform HTTP requests without using any additional libraries.  This can not provide more advanced features and functionality.

Creating an **HttpUrlConnection** instance by using **openConnection()** method of the URL class.
Adding request parameters using a **DataOutputStream()**

Reading responses of Failed requests use the **getErrorStream()** method. While reading a general response uses **getResponseCode(), connect(), getInputStream()** or **getOutputStream()** methods

To close the connection, use the **disconnect()** method.



[Back to Main Page](../README.md)