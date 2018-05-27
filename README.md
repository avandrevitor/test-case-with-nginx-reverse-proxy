# Test Case with Nginx Reverse Proxy

### Get Started
````
$ docker-compose up -d
````

### Add Domains in your Host
````
$ echo '127.0.0.1   domain-nginx.com' >> /etc/hosts
$ echo '127.0.0.1   domain-apache.com' >> /etc/hosts
````

### Test

1. Open containers logs with [terminator](https://www.tecmint.com/terminator-a-linux-terminal-emulator-to-manage-multiple-terminal-windows/)
2. Access in your browser domain-nginx.com
3. Access in your browser domain-apache.com
