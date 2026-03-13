# HTTPS / SSL Configuration with HAProxy

This project focuses on configuring DNS records, setting up SSL termination using HAProxy, and enforcing secure HTTPS traffic for a web infrastructure composed of multiple servers.

## Project Overview

The infrastructure contains three servers:

* **web-01** – Web server running Nginx
* **web-02** – Web server running Nginx
* **lb-01** – Load balancer running HAProxy

HAProxy distributes incoming traffic to the web servers using a **round-robin algorithm**. SSL termination is configured on the load balancer so that encrypted traffic is handled by HAProxy before being forwarded to the backend servers.

---

##
