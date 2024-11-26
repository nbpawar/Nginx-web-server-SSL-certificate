# Nginx-web-server-SSL-certificate
Host the website on nginx server and SSL certification on it .


Static Content  :    Static Content is pre-created, unchanging content that is served as-is to users without requiring real-time server-side processing.

Dynamic Content :    Dynamic Content is generated in real-time based on user interactions, preferences, or data, often using server-side or client-side processing.

NGINX (pronounced "Engine-X")  :  IT is a high-performance, open-source web server and reverse proxy server designed for speed, scalability, and efficient resource usage. It’s widely used for web hosting, load balancing, and caching.

WEBSERVER :

server {
         listen 80;
         servername nbpawar.com;
         location /{
                     root/var/www/html;
                     index index.html;
                     }
        }

Reverse Proxy Server :  A reverse proxy server is an intermediary server that sits between client devices and backend servers. It forwards client requests to the appropriate backend servers and returns the server's response to the clients. This is in contrast to a forward proxy, which acts on behalf of clients to access external resources.

Load Balancer : A load balancer is a system that distributes incoming network or application traffic across multiple servers to ensure high availability, reliability, and optimal resource utilization. It acts as a single point of access for users while balancing the workload among servers in the backend.

cache  :  A cache is a high-speed storage layer that stores copies of frequently accessed data. This allows faster data retrieval compared to fetching the data from the original source, such as a database or a remote server.

.
      
                 
