Common Internet Performance Issues Statement of Action:
Describe common internet performance issues, such as bandwidth, internet connection types, pages loading slowly, resolution, and size of graphics. {Explain how these issues impact a user's experience when using a website or application.}
The type of internet connection (e.g., fiber, cable, DSL, satellite) determines speed and reliability. Fiber-optic provides the fastest speeds, while DSL and satellite are slower and may have higher latency.

Guiding Questions:
How do browsers handle large graphics or slow-loading pages?
Answer{Browsers render parts of a webpage as they are downloaded instead of waiting for the entire page to load. This allows users to see and interact with content sooner.
Lazy Loading: Large graphics or media files may not be loaded immediately. Instead, they are loaded only when they come into the user's viewport, saving bandwidth and improving initial page load times.}

How do web servers influence performance, such as through optimization or cloud services?
Answer{Caching: Web servers like Nginx or Apache can cache frequently accessed content (e.g., HTML, images, or database queries). This reduces the load on the server and speeds up response times.
Load Balancing: By distributing incoming requests across multiple servers, web servers ensure no single server is overwhelmed, maintaining smooth performance.}

What impact does IoT (e.g., multiple devices using the same Wi-Fi) have on performances?
Answer{High-bandwidth Devices: Smart cameras, video doorbells, and streaming devices consume significant bandwidth, potentially reducing speed for other users.
Cumulative Impact: Even low-bandwidth devices like sensors or smart lights can create performance issues when deployed in large numbers.}

How do protocols like IPv6 or HTTP improve performance over time?
Answer{Scalability: IPv6 provides a virtually unlimited address space, removing the need for techniques like NAT (Network Address Translation). This reduces complexity and latency caused by translating private to public IPs.
Direct Communication: Devices can have unique global IP addresses, enabling faster peer-to-peer communication and smoother IoT integration.}
