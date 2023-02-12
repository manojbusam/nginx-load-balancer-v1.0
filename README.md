# nginx-load-balancer-v1.0

1. Pages route to upstream servers:

127.0.0.1:9001;
127.0.0.1:9002;
127.0.0.1:9003;

2. These 3 servers are clustered together as load balancer: http://backend_servers/

3. When any request coming to www.example.com it gets routed to the load balancer above.
