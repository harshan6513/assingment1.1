# Assignment 1.1: How a Website Works

## 1. Explanation: How a Website Works

When a user types a URL (Uniform Resource Locator) into a web browser like Google Chrome, the browser first finds the IP address of the website using DNS (Domain Name System). The browser then sends an HTTP or HTTPS request to the web server. The server receives the request, processes it, and may communicate with a database to retrieve the required information. The server sends an HTTP response containing data such as HTML, CSS, JavaScript, and images back to the browser. The browser interprets these files and displays the website on the screen. The browser acts as the client, the server processes requests, and the database stores and manages information. This complete process is called the request-response cycle.

## 2. Meaning of HTTP and HTTPS

**HTTP (Hypertext Transfer Protocol):** HTTP is a communication protocol used to transfer data between a web browser and a web server.

**HTTPS (Hypertext Transfer Protocol Secure):** HTTPS is the secure version of HTTP. It uses encryption through TLS to protect data exchanged between the browser and the server.

## 3. Request-Response Cycle

The request-response cycle is the process in which a client sends a request to a server and the server returns a response.

1. The user enters a URL in the browser.
2. The browser finds the server's IP address using DNS.
3. The browser sends an HTTP or HTTPS request to the server.
4. The server processes the request and may retrieve data from a database.
5. The server sends a response to the browser.
6. The browser displays the website to the user.

## 4. Difference Between Static and Dynamic Websites

| Static Website | Dynamic Website |
|---|---|
| Displays mostly fixed content. | Displays content that can change according to the user or data. |
| Usually uses HTML and CSS, with optional JavaScript. | Often uses JavaScript and may use server-side code and databases. |
| Content changes when files are manually updated. | Content can be generated or updated automatically. |
| Example: A simple personal portfolio page. | Example: An online shopping website with user accounts and live product information. |

## 5. Practical: Inspecting Requests Using Chrome DevTools

**Objective:** To inspect the network requests made when a website loads.

**Procedure:**

1. Open Google Chrome.
2. Visit a website, for example, https://example.com.
3. Press **F12** or **Ctrl + Shift + I** to open Chrome DevTools.
4. Select the **Network** tab.
5. Reload the webpage using **Ctrl + R**.
6. Observe the requests in the list.
7. Click the main document request and inspect its **Headers**, **Status Code**, and **Response**.
8. Take a screenshot showing the Network tab and the list of requests.

**Observation:** The Network tab shows the resources requested by the browser, such as HTML documents, CSS files, JavaScript files, and images. It also displays information such as request methods, status codes, and loading times.

**Result:** I learned how a browser communicates with a web server, how HTTP/HTTPS requests and responses work, and how to inspect website network activity using Chrome DevTools.