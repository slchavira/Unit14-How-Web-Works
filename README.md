# How Web Works Exercise

- **What is HTTP?** 
  - Hypertext Transfer Protocol. Facilitates communication between the web browser and web server.
- **What is a URL?**
  - Uniform Resource Locator. The hostname/address for a website.
- **What is DNS?**
  - Domain Name System. Can be thought of as the "phonebook of the Internet." Can take a URL, easier for humans to read and remember, and converts that into the appropriate IP address.
- **What is a query string?**
  - A way to provide more information with a URL. Such as with searching within a site. Multiple arguments can be separated by "&".
- **What are two HTTP verbs and how are they different?** 
  - GET: requests without side effects (doesn't change server data)
  - POST: requests with side effects (changes server data)
- **What is an HTTP request?** 
  - A request from a client to a server using the HTTP protocol. 
- **What is an HTTP response?** 
  - The response from the server to a client request using the HTTP protocol.
- **What is an HTTP header? Give a couple examples of request and response headers you have seen.**
  - An HTTP header is additional information sent by the client or server along with an HTTP request or response.
  - Request Headers:
    - HOST
    - User-Agent
    - Accept-Language
    - Cache-Control
  - Response Headers:
    - Date
    - Content-Type
    - Server
    - Set-Cookie
- **What are the processes that happen when you type “http://somesite.com/some/page.html” into a browser?**
  1. The web browser sends URL and DNS will attempt to translate it to a valid IP address.
  2. The request is then sent to the server using the IP address. 
  3. The server will repond back with HTML. 
  4. The browser uses the received data/info to construct the web page and retrieve any other required resources.
