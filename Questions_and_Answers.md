# Interview Questions and Answers

### 1. What is SSL/TLS, and why is it important in web security?

- **SSL (Secure Sockets Layer)** and **TLS (Transport Layer Security)** are cryptographic protocols that ensure secure communication over a computer network. SSL is the predecessor to TLS, but the terms are often used interchangeably.
- **Importance:** They provide data encryption, ensuring confidentiality, data integrity, and authentication in communications over the internet, especially for sensitive transactions (e.g., online banking, e-commerce).

---

### 2. What is the difference between HTTP and HTTPS?

- **HTTP (Hypertext Transfer Protocol):** A protocol used to transfer data over the web. Data sent over HTTP is not encrypted.
- **HTTPS (Hypertext Transfer Protocol Secure):** The secure version of HTTP, where the communication is encrypted using SSL/TLS.
- **Key Difference:** HTTPS ensures data is secure during transmission, while HTTP does not.

---

### 3. What is the role of encryption in security?

- Encryption converts data into a secure format, ensuring that only authorized parties can read it. It protects data from unauthorized access, ensuring privacy and integrity, especially during transmission over untrusted networks.

---

### 4. What are some basic networking concepts every developer should know?

- **IP Address:** A unique address assigned to each device connected to a network.
- **Subnetting:** Dividing an IP network into smaller subnetworks to improve efficiency.
- **Router:** A device that forwards data packets between computer networks.
- **Firewall:** A network security system that monitors and controls incoming and outgoing traffic.
- **DNS (Domain Name System):** Resolves domain names to IP addresses.

---

### 5. What are some common cybersecurity terms every developer should know?

- **Phishing:** A type of cyberattack where attackers impersonate legitimate entities to steal sensitive information.
- **Malware:** Malicious software designed to harm or exploit devices.
- **Ransomware:** A type of malware that locks a user’s system and demands payment for access to be restored.
- **Encryption:** Protects data by transforming it into an unreadable format.

---

### 6. What are HTTP methods, and when should you use each one?

- **GET:** Retrieve data from the server (safe and idempotent).
- **POST:** Send data to the server, typically for form submissions (non-idempotent).
- **PUT:** Update existing resources on the server.
- **DELETE:** Remove resources from the server.

---

### 7. What is an IP address and how is it structured?

- **IP Address:** A unique identifier for devices on a network. It can either be IPv4 (32-bit) or IPv6 (128-bit).
- **Structure:** IPv4 example: `192.168.1.1` (4 sets of numbers between 0 and 255). IPv6 example: `2001:0db8:85a3:0000:0000:8a2e:0370:7334`.

---

### 8. What is DNS, and why is it important?

- **DNS (Domain Name System):** It translates domain names into IP addresses.
- **Importance:** It enables users to access websites using human-readable domain names (e.g., google.com) instead of having to remember complex IP addresses.

---

### 9. What is the difference between TCP and UDP?

- **TCP (Transmission Control Protocol):** A connection-oriented protocol that ensures reliable delivery of data by establishing a connection and using acknowledgments.
- **UDP (User Datagram Protocol):** A connectionless protocol that is faster but does not guarantee reliable delivery.
- **When to Use:**
  - **TCP:** For applications requiring reliable data transfer (e.g., web browsing, file transfer).
  - **UDP:** For real-time applications where speed is critical (e.g., video streaming, online gaming).

---

### 10. What are some best practices for web security?

- Use HTTPS to encrypt data.
- Implement input validation to prevent SQL injection and cross-site scripting (XSS).
- Use strong password policies.
- Regularly update software to patch known vulnerabilities.
- Implement two-factor authentication (2FA).

---

### 11. What is Cross-Origin Resource Sharing (CORS)?

- CORS is a security feature implemented by browsers that allows or restricts web pages from making requests to domains other than their own.
- It helps prevent malicious websites from accessing sensitive data from another domain.

---

### 12. What is SQL injection, and how can it be prevented?

- **SQL Injection:** A type of attack where an attacker inserts malicious SQL queries into input fields to access or manipulate a database.
- **Prevention:** Use parameterized queries, ORM libraries, and proper input sanitization.

---

### 13. What is a WebSocket, and when should you use it?

- **WebSocket:** A protocol that provides full-duplex communication channels over a single TCP connection.
- **When to Use:** Ideal for real-time applications such as live chat, gaming, and stock market updates.

---

### 14. What is the purpose of load balancing in web applications?

- **Load Balancing:** Distributes incoming network traffic across multiple servers to ensure no single server is overwhelmed, improving performance and reliability.

---

### 15. How does caching improve web performance?

- Caching stores frequently accessed data locally (in the browser or on a server) so it doesn't need to be fetched repeatedly from the database or an external source, reducing load times and improving speed.

---

### 16. What are some common HTTP status codes?

- **200 (OK):** The request was successful.
- **404 (Not Found):** The requested resource could not be found.
- **500 (Internal Server Error):** The server encountered an unexpected condition.

---

### 17. What is the purpose of a Content Delivery Network (CDN)?

- A CDN is a network of servers that distributes content to users based on their geographical location, reducing latency and improving load times.

---

### 18. What is OAuth, and how is it used for authentication?

- **OAuth (Open Authorization):** A protocol that allows third-party services to access user data without sharing login credentials. It is commonly used for single sign-on (SSO).

---

### 19. What is an API, and how does it facilitate communication between systems?

- **API (Application Programming Interface):** A set of rules and protocols that allow one software system to interact with another. APIs facilitate communication between different services or applications.

---

### 20. What is the purpose of SSL certificates, and how do they work?

- **SSL Certificates:** Digital certificates that authenticate the identity of a website and encrypt data transmitted between the website and the user’s browser, ensuring secure communication.

---
