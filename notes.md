# What happens when I visit https://example.com?

1. I type https://example.com in the browser.
2. The browser checks if the IP is cached; if not, it asks DNS to resolve the domain into an IP address.
3. DNS returns the IP address of the server hosting example.com.
4. The browser connects to the server’s IP using TCP (Transmission Control Protocol), then upgrades the connection with TLS (Transport Layer Security) encryption (HTTPS) on port 443.
5. The browser sends an HTTPS request (GET /) and the server responds with an HTTP response (status, headers, HTML).
6. The browser processes the response, loads extra resources (CSS, JS, images), and renders the web page.

#Who created Git and when, and why?


- Git was created by **Linus Torvalds** in **2005**
- Replacement for **BitKeeper** after license issues.  
- Designed to be **distributed, fast, secure, and flexible**.  
- Ideal for large projects like the **Linux kernel**.

