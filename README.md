docker-htcpcp_server
==========================
dockerfile for https://github.com/madmaze/HTCPCP

Usage
==========================
```
docker build -t htcpcp_server .  
docker run -ti -p 8080:8080 htcpcp_server #Ctrl+pq  
telnet localhost 8080
WHEN /pot-1 HTCPCP/1.0

```

Note
===========================
If you miss the HTCPCP on this server and crash them,  
you have to restart the container to overall.
