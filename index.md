Assignment 1.1 — How a Website Works

When we type a URL (Uniform Resource Locator) into a web browser like Google Chrome, the browser acts as a client and sends a request to the web server to access the website. First, DNS (Domain Name System) converts the domain name into an IP address so the browser can locate the server. The browser then sends an HTTP (Hypertext Transfer Protocol) or HTTPS (Hypertext Transfer Protocol Secure) request to the server. HTTPS is the secure version of HTTP because it encrypts the data exchanged between the browser and the server. The server processes the request and may retrieve or store information in a database if required. It then sends an HTTP response containing the requested resources, such as HTML, CSS, JavaScript, and images. The browser processes these resources and displays the website on the screen. This process is called the request-response cycle. A static website displays fixed content that usually remains the same for different visitors, while a dynamic website can generate or update content based on user interactions, database information, or other conditions. We can use Chrome DevTools and its Network tab to inspect website requests and responses, including resource types, status codes, and loading times.

Screenshot of the Network Tab

To complete the practical part of the assignment:

Open Google Chrome and visit any website, such as https://example.com.
Right-click anywhere on the page and select Inspect, or press F12.
Select the Network tab in DevTools.
Reload the page using Ctrl + R while the Network tab is open.
Observe the requests for HTML, CSS, JavaScript, images, and other resources.
Take a screenshot showing the Network tab and the list of requests.
Attach the screenshot below your paragraph when submitting the assignment.