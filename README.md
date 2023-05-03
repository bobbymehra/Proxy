# ProxyServer

It’s an intermediary server separating end users from the websites they browse. Proxy servers provide varying levels of functionality, security, and privacy depending on your use case, needs, or company policy.
If you’re using a proxy server, internet traffic flows through the proxy server on its way to the address you requested. The request then comes back through that same proxy server (there are exceptions to this rule), and then the proxy server forwards the data received from the website to you.

![proxy-flow](https://user-images.githubusercontent.com/64466106/235972154-100112ea-a87a-44d4-acb0-8daaf101c16c.png)

# How a Proxy Works

Because a proxy server has its own IP address, it acts as a go-between for a computer and the internet. Your computer knows this address, and when you send a request on the internet, it is routed to the proxy, which then gets the response from the web server and forwards the data from the page to your computer’s browser, like Chrome, Safari, Firefox, or Microsoft Edge.

A proxy server is basically a computer on the internet with its own IP address that your computer knows. When you send a web request, your request goes to the proxy server first. The proxy server then makes your web request on your behalf, collects the response from the web server, and forwards you the web page data so you can see the page in your browser. 

When the proxy server forwards your web requests, it can make changes to the data you send and still get you the information that you expect to see. A proxy server can change your IP address, so the web server doesn’t know exactly where you are in the world. It can encrypt your data, so your data is unreadable in transit. And lastly, a proxy server can block access to certain web pages, based on IP address.

# Why Should You Use a Proxy Server?
- There are several reasons organizations and individuals use a proxy server.

1. To control internet usage of employees and children:
Organizations and parents set up proxy servers to control and monitor how their employees or kids use the internet. Most organizations don’t want you looking at specific websites on company time, and they can configure the proxy server to deny access to specific sites, instead of redirecting you with a nice note asking you to refrain from looking at said sites on the company network. They can also monitor and log all web requests, so even though they might not block the site, they know how much time you spend cyberloafing.

2. Bandwidth savings and improved speeds: 
Organizations can also get better overall network performance with a good proxy server. Proxy servers can cache (save a copy of the website locally) popular websites – so when you ask for www.example.com, the proxy server will check to see if it has the most recent copy of the site, and then send you the saved copy. What this means is that when hundreds of people hit www.example.com at the same time from the same proxy server, the proxy server only sends one request to example.com. This saves bandwidth for the company and improves the network performance.

3. Privacy benefits: 
Individuals and organizations alike use proxy servers to browse the internet more privately. Some proxy servers will change the IP address and other identifying information the web request contains. This means the destination server doesn’t know who actually made the original request, which helps keeps your personal information and browsing habits more private.

4. Improved security: 
Proxy servers provide security benefits on top of the privacy benefits. You can configure your proxy server to encrypt your web requests to keep prying eyes from reading your transactions. You can also prevent known malware sites from any access through the proxy server. Additionally, organizations can couple their proxy server with a Virtual Private Network (VPN), so remote users always access the internet through the company proxy. A VPN is a direct connection to the company network that companies provide to external or remote users. By using a VPN, the company can control and verify that their users have access to the resources (email, internal data) they need, while also providing a secure connection for the user to protect the company data.

5. Get access to blocked resources: 
Proxy servers allow users to circumvent content restrictions imposed by companies or governments. Is the local sportsball team’s game blacked out online? Log into a proxy server on the other side of the country and watch from there. The proxy server makes it look like you are in California, but you actually live in North Carolina. Several governments around the world closely monitor and restrict access to the internet, and proxy servers offer their citizens access to an uncensored internet.



# Types of Proxy Servers
While all proxy servers give users an alternate address with which to use the internet, there are several different kinds—each with its own features. Understanding the details behind the list of proxy types will help you make a choice based on your use case and specific needs.

- Forward Proxy
A forward proxy sits in front of clients and is used to get data to groups of users within an internal network. When a request is sent, the proxy server examines it to decide whether it should proceed with making a connection.

A forward proxy is best suited for internal networks that need a single point of entry. It provides IP address security for those in the network and allows for straightforward administrative control. However, a forward proxy may limit an organization’s ability to cater to the needs of individual end-users.

- Reverse Proxy
Unlike a forward proxy, which sits in front of clients, a reverse proxy is positioned in front of web servers and forwards requests from a browser to the web servers. It works by intercepting requests from the user at the network edge of the web server. It then sends the requests to and receives replies from the origin server.

Reverse proxies are a strong option for popular websites that need to balance the load of many incoming requests. They can help an organization reduce bandwidth load because they act like another web server managing incoming requests. The downside is reverse proxies can potentially expose the HTTP server architecture if an attacker is able to penetrate it. This means network administrators may have to beef up or reposition their firewall if they are using a reverse proxy.

- Transparent Proxy
A transparent proxy can give users an experience identical to what they would have if they were using their home computer. In that way, it is “transparent.” They can also be “forced” on users, meaning they are connected without knowing it.

Transparent proxies are well-suited for companies that want to make use of a proxy without making employees aware they are using one. It carries the advantage of providing a seamless user experience. On the other hand, transparent proxies are more susceptible to certain security threats, such as SYN-flood denial-of-service attacks.

- Anonymous Proxy
An anonymous proxy focuses on making internet activity untraceable. It works by accessing the internet on behalf of the user while hiding their identity and computer information.

A anonymous proxy is best suited for users who want to have full anonymity while accessing the internet. While anonymous proxies provide some of the best identity protection possible, they are not without drawbacks. Many view the use of anonymous proxies as underhanded, and users sometimes face pushback or discrimination as a result.

- High Anonymity Proxy
A high anonymity proxy is an anonymous proxy that takes anonymity one step further. It works by erasing your information before the proxy attempts to connect to the target site.

The server is best suited for users for whom anonymity is an absolute necessity, such as employees who do not want their activity traced back to the organization. On the downside, some of them, particularly the free ones, are decoys set up to trap users in order to access their personal information or data.

- Distorting Proxy
A distorting proxy identifies itself as a proxy to a website but hides its own identity. It does this by changing its IP address to an incorrect one.

Distorting proxies are a good choice for people who want to hide their location while accessing the internet. This type of proxy can make it look like you are browsing from a specific country and give you the advantage of hiding not just your identity but that of the proxy, too. This means even if you are associated with the proxy, your identity is still secure. However, some websites automatically block distorting proxies, which could keep an end-user from accessing sites they need.

- Data Center Proxy
Data center proxies are not affiliated with an internet service provider (ISP) but are provided by another corporation through a data center. The proxy server exists in a physical data center, and the user’s requests are routed through that server.

Data center proxies are a good choice for people who need quick response times and an inexpensive solution. They are therefore a good choice for people who need to gather intelligence on a person or organization very quickly. They carry the benefit of giving users the power to swiftly and inexpensively harvest data. On the other hand, they do not offer the highest level of anonymity, which may put users’ information or identity at risk.

- Residential Proxy
A residential proxy gives you an IP address that belongs to a specific, physical device. All requests are then channeled through that device.

Residential proxies are well-suited for users who need to verify the ads that go on their website, so you can block cookies, suspicious or unwanted ads from competitors or bad actors. Residential proxies are more trustworthy than other proxy options. However, they often cost more money to use, so users should carefully analyze whether the benefits are worth the extra investment.

- Public Proxy
A public proxy is accessible by anyone free of charge. It works by giving users access to its IP address, hiding their identity as they visit sites. 

Public proxies are best suited for users for whom cost is a major concern and security and speed are not. Although they are free and easily accessible, they are often slow because they get bogged down with free users. When you use a public proxy, you also run an increased risk of having your information accessed by others on the internet.

- Shared Proxy
Shared proxies are used by more than one user at once. They give you access to an IP address that may be shared by other people, and then you can surf the internet while appearing to browse from a location of your choice.

Shared proxies are a solid option for people who do not have a lot of money to spend and do not necessarily need a fast connection. The main advantage of a shared proxy is its low cost. Because they are shared by others, you may get blamed for someone else’s bad decisions, which could get you banned from a site.

- SSL Proxy
A secure sockets layer (SSL) proxy provides decryption between the client and the server. As the data is encrypted in both directions, the proxy hides its existence from both the client and the server.

These proxies are best suited for organizations that need enhanced protection against threats that the SSL protocol reveals and stops. Because Google prefers servers that use SSL, an SSL proxy, when used in connection with a website, may help its search engine ranking. On the downside, content encrypted on an SSL proxy cannot be cached, so when visiting websites multiple times, you may experience slower performance than you would otherwise.

- Rotating Proxy
A rotating proxy assigns a different IP address to each user that connects to it. As users connect, they are given an address that is unique from the device that connected before it.

Rotating proxies are ideal for users who need to do a lot of high-volume, continuous web scraping. They allow you to return to the same website again and again anonymously. However, you have to be careful when choosing rotating proxy services. Some of them contain public or shared proxies that could expose your data.
