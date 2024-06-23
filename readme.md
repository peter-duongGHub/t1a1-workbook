# PeterDuong_T1A1 Assessment - Workbook
## Q1 

### What is Web Development Markup Language?  
Web Development Markup Language is one of many languages in web development used to structurally present text, images and/or links in a web document, it enables components such as text to be rendered a specific way (Chris, 2021).

### How does Web Development Markup Language work?
Web Development Markup Language uses either tags or code around or between text, providing instructions to a computer on how certain elements should be displayed & structured on a web document. Text, tags and code may be written in a simple text editor such as notepad, Microsoft Word, Visual Studio Code to name a few, and converted into a web development markup language format before rendering on a web page. Each markup language has certain rules to distinguish between text and the tags or codes necessary to implement web document structuring, this is called syntax (Chris, 2021).

### Example Web Development Markup Language
#### HTML
```
<h1>This is a title</h1>
```
HTML5 also referred to as HTML is the newest version of HTML. This language works by inserting opening and closing tags, which helps structure the content displayed on the web browser. Here's an example: The above code represents an opening and closing tag for a heading, specifically h1. h1 is the element name and the text between the opening and closing tags are the text that will be rendered. Opening tags begin with angle brackets specifying the beginning of content, represented by <>. Closing tags are similar, angle brackets with a forward slash inside the angle brackets - </> this represents the end of the element (Chris, 2021).

#### XML
```
<note>
<heading>Note to Self</heading>
<body>Lorem Ipsum</body>
</note>
```
XML is another example of a markup language, its function differs from HTML5. XML (extensible markup language) similarly to HTML5 uses tags. XML does not display content on a web document, software must be used to help store and transfer or display it (Chris, 2021). Tags and document display in XML need to be defined prior to use. The above code represents a note with a heading and body. These elements must be defined by the author.

### Components/Concepts of Markup Languages
#### Syntax
Syntax within markup languages involves the rules associated to the use of the markup language. They are pre-determined instructions that must be implemented when using attributes, elements & tags. Without proper syntax, error codes may appear and content may not be rendered.  
A few examples of markup language syntax:  
- **Angle brackets**  
```<>``` : Opening Tag  
```<\>``` : Closing Tag
- **Attributes**  
```alt=```: Alt Attribute (maybe used if image does not render, screen reader purposes)  
```placeholder=``` Placeholder Attribute (sets placeholder text)  
```style=``` : Style attribute (not recommended, but is an attribute for in-line styling)  
- **Elements**(Represented by opening tag, closing tag & content)    
```<h1>Header</h1>```: this would represent the h1 element and would represent a primary header tag (opening and closing)  
```<p>Lorem</p>```: this would represent the p tag(opening and closing), associated with paragraphs   
```<img>```: this would represent the img tag(self-closing), associated with images 

#### Hypertext
A common and significant component within markup languages such as HTML is hypertext. Text components that may connect to other documents or chunks of text are referred to as hypertext. Hypertext helps with navigating pages of text/document much simpler, easier and accurate. Without hypertext, utilising search engines to navigate pages would not be possible (Chris, 2021).

#### Tags
Tags are an important concept within markup languages. Without tags no content would be exhibited or stored(XML). In HTML, tags are necessary to represent the documents structure on web pages and help support search engines to categorise content relevancy (Chris, 2021). An example:  
```<p>```  
```</p>```  
Opening tags are represented with two enclosing angle brackets, closing tags are represented by two enclosing angle brackets with a forward slash inside followed by the annotation representing the specific element (p represents paragraph).

#### Text
Text component would be surrounded by opening and closing tags displaying the text manifested on the document. Example:
```
<p>Lorem Ipsum</p>
```
The following line of code would provide a paragraph with text content Lorem Ipsum.

#### Semantics (HTML)
Semantic tags are used in HTML to provide meaning for the content displayed on the web page. It helps divide sections of content into relevant containers that support optimal SEO purposes (Chris, 2021). Example: 
```
<nav>Menu</nav>
```
The nav element helps readers and developers by implying this section of content involves navigating content.

#### Static Language
Markup languages are static in nature. They do not provide any interactivity for users. Pages are 'static' and require application of programming languages such as JavaScript to add dynamic properties (Chris, 2021).

### Where is Web Development Markup Language used?
- Google Chrome
- Mozilla Firefox
- Microsoft Edge
- Youtube
- Wikipedia

### Benefits of Web Development Markup Language
Web development markup languages allow authors to structure webpage content in a standardised format. The benefits of Markup Languages include:
- **Accessibility and Readability**  
With every browser supporting markup languages such as HTML language, this makes it readily accessible to both viewers and businesses in terms of application and rendering. In terms of readability, An example: for HTML, attributes such as ```alt``` helps with readability for images that fail to render or for screen readers, making HTML5 a viable option in many cases of displaying web content and for greater user experience (Chris, 2021).

- **Optimising SEO**  
Search engines such as google will rank websites based on their relevance, technical geography and popularity. Components in HTML such as semantic tags help group and contain specific content for search engines to better understand and navigate the content meaning and structure, ranking higher for relevant content. HTML tags play a key role in grouping specific sections for search engine optimisation (Chris, 2021). An example would be:
```
<main>:
``` 
The main tag is the primary portion of the document. This section would contain content unique to the web page.  

- **Ease of Use & Extensibility**  
HTML is a simple language in comparison to other languages, making it much easier to learn, understand and apply. As HTML works across multiple browsers and devices, structuring and rendering content of web pages becomes much simpler and smoother. HTML is also extensible, meaning it has a great affinity with stylesheet languages such as CSS and programming languages like Javscript (Chris, 2021).

### Cons of Web Development Markup Language
- **Static Language**  
Markup languages such as HTML are static, this means they are limited in what they are able to do. In simple terms this means the components of the web page are not dynamic, they cannot change with user input or other factors (Chris, 2021).

- **Security**
HTML has its drawbacks, HTML injections are an example. HTML injections are a type of attack focused on manipulating the HTML components resulting in a disfigured structure or manipulated components. Certain components such as tags or attributes or hyperlinks may be replaced with malicious code (Chris, 2021). Certain preventative measures such as security audits, validating user input and sanitizing harmful content from user inputs may remove or mitigate the risks associated with the use of HTML.

- **Limited Designs**  
HTML is static in nature limiting the language in what it may present to the viewer. Only texts, links, buttons, tables etc (to name a few), may be used as page content. 3D objects, animations, and interactivity cannot be created with markup languages. This is where other languages like CSS & Javascript support HTML (Chris, 2021).

## Q2 
### Packets
A packet is a fixed amount of data representing content such as images, text etc. Packets are transmitted via wires, radio waves and cables across the internet via different network paths and reassembled by the receiving host to produce a complete image, text and more.
A packet is composed of multiple headers and payload. Some network protocols may attach footers and trailers at the end of a packet for extra information. Each header is composed at the front of each packet and is processed by different network protocols, this assists with the interpretation of data across devices (Zola and Gillis, 2017). The header is processed first as it is received by Routers, switches and devices. The header contains information about packet content, its origin IP address and destination or recipient IP address to ensure retrieval to the right recipient. A majority of packets that are transmitted across the internet will have both a TCP (Transmission Control Protocol) and IP (Internet Protocol) header. An example packet includes: TCP packet such as ACK packet acknowledges receiving packets and relays a signal back to the sender for continued packet transmission if necessary (Zola and Gillis, 2017).

#### Explain Contributions to Internet Development:
Packets enable efficient, reliable transmission of data across the network, allowing for fair use of the internet and efficient transportation of data. Without packets, data would be transferred as long lengths of bits making it difficult for other packets to enter and use the same route. A systematic approach to this is packet switching. This process  enables simultaneous connections over the same networks allowing for exchange of data across devices. Packets are crucial in enabling:  
- Different routing pathways for packets to be received 
- Error detection through checksum or cyclic redundancy checks allowing for retransmission or storage
- Data delivered efficiently as packets travel across optimal available routes for delivery. Minimising congestion within network and faster transmission of data  
- Packets offer capable encryption for safety, protection and secure delivery. Systems such as HTTPS offer encryption.  
- Packet-switched networks minimise risk of losing data, receiving devices may request missing packets from the origin device  

### IP Addresses (IPv4 and IPv6)
Ip addresses are numeric information used to identify different devices across networks governed by a set of rules named Internet Protocol. 

#### IPv4
They are the identifiable on devices to facilitate the exchange of information across devices on a network and contain geolocation. IP addresses are essential for network equipment and processes to differentiate devices, routers and websites. It is composed of a set of four numbers such as 192.168.1.254. Numbers within the set can range from 0 to 255. These generated numbers are not random and are assigned and produced by IANA (The Internet Assigned Numbers Authority). IPv4 addresses 32 bits in length and can produce 4.3 billion combinations of addresses. Addresses are allocated using CIDR (Classless Inter-Domain Routing) for efficiency and support interconnected communications via devices on a similar network (geeksforgeeks, 2020). IPv4 addresses are effective in terms of routing protocols essential to decongestion and effective routing of packets across the networks but are limited in the amount of addresses it may allocate to each device. Initial uses of IPv4 facilitated the growth and expansion of the internet, prompting communication between devices  An important feature within IPv4 is Network address translation (NAT), aiding with the conservation of IP addresses by allowing multiple devices on the same network to share the same IP address. This promoted fair use of the internet and extended utilisation across more devices (B, 2019). IPv4 inspired the production of many other protocols such as HTTP and DNS, forming the foundation for communication and exchange of data. 
A majority of devices across the network currently use this protocol to exchange information but are planning to move to IPv6. How it works on the internet:
1. Device connects to network connected to the internet (such as ISP, internet service provider)
2. IP address is assigned by ISP to your connected device
3. Internet activity enabled via ISP

#### IPv6
The latest version of the Internet Protocol is IPv6 which introduces several key features for security and has played a significant role in the development and evolution of the internet.
IPv6 utilises 128-bit addresses capable of an exponentially greater amount of addresses. The advancement of IPv6 has lead to an increase in the number of allowed devices connecting to the internet enhancing productivity, connectivity and education across the globe. Features of IPv6 include minimising routing tables within routers to help improve packet processing speeds and efficient routing of packets to specific destinations (BasuMallick, 2022). This is crucial as the population grows, so too does the volume of traffic associated with the internet. Optimised routing and efficient processing speeds will need to be prioritised to better user experiences and client-server interactions in relation to web applications. IPv6 also contains an important feature Internet Protocol Security (IPSec) providing authentication, integrity and obfuscation of packets across the network. Another feature is the Quality of Service (QoS) which optimises the prioritisation of certain resources depending on the type of traffic, ensuring responsible allocation of resources and greater management and control over traffic. This will be determined based on the header fields within IPv6. Overall due to the limited amount of IP address IPv4 may provide, IPv6 provides a long-term solution to accommodate for the exhaustion of IPv4 addresses due to proliferating users of the internet (BasuMallick, 2022).


#### Explain Contributions to Internet Development (IPv4 and IPv6):
With the release of IPv4 addresses, it provided the foundation for the development of the internet. It was the intial framework used in identifying devices throughout the internet and accelerated the growth of interoperability, enabling devices to communicate globally. The specific annotation of IP addresses helped ease management and troubleshooting as it is easily understood facilitating its growth and community support (Duo, 2020). The implementation of IPv4 scaled E-commerce, online businesses, social media and connected the world globally exponentially contributing to the development of the internet and its constituents (businesses, corporations and legal entities). With the adoption of IPv4, innovations in technological advancements and research were made possible. Examples include: developing technological security measures (Firewalls) to enhance IPv4 and accessing online resources for educational purposes. The added IPv6 feature including IPSec further allowed for secure, reliable transmissions of data between client-server interactions (Duo, 2020).

### Routers and routing

#### Routing
Routing is the system used to process effective pathways via nodes and paths within an interconnected network using pre-determined instructions. It involves transmitting packets across routers to reach the destination IP address. Firstly data is sent via a packet through a packet-switched network traversing multiple routers and devices. Routers help determine where to forward packets by measuring delays, capacity and speed, this is done through the use of a routing table (Molenaar, 2013). The router then forwards the packet to the next device or router within the network. Routing of packets through networks is determined by algorithms, routing tables and more. Routing has contributed to the functioning and processing of data for each device on the internet. It has helped load web pages while people browse, send emails or text to people across the globe and has opened up opportunities for people to gain online education, communication and entertainment (Molenaar, 2013). 

#### Router
A networking device that facilitates connection between devices and networks. Their role includes finding optimal pathways with the utilisation of routing tables to analyse metrics such as cost and congestion to determine optimal pathways in forwarding packets to their destination. They forward packets to other routers, devices etc to reach the recipient device. Some useful techniques routers may use involve sending out multiple similar packets using different pathways to; minimise packet loss errors and manage the volume of traffic  (Molenaar, 2013). Routers work in the network layer and facilitate the global exchange of data (packets) across multiple devices simultaneously and instantaneously. They play a crucial role in managing traffic effectively and improving the performance of the network. Routers utilise routing protocols such as RIP and BGP to exchange network topology or traffic conditions, forwarding packets on different routes depending on the mentioned factors including several others (Molenaar, 2013).
 

#### Explain Contributions to Internet Development (Routing and Routers):
Routing and routers are essential in the development of the internet as it contributes to:
- Maximising network capacity without causing congestion
- Loading web page speeds are faster leading to better SEO for websites, better user experience etc.
- Allows for processing and management of a greater amount of data traffic, minimising network failure
- Reliable and simultaneous transmission of data across multiple devices 
- Has facilitated the use and growth of the internet as users can access resources globally inspiring innovation and curiousity
- Serve to interconnect networks, devices and systems enabling global accessibility of services and resources on the internet 
- Routers and routing have played a significant role in the overall functioning, processing and evolution of packet transmissions contributing positively to a proficient resourceful system of transferring and receiving data between networks and devices.  



### Domain
Domain is method in defining the web address of a website or email address within the internet. It is used to organise, transfer and access internet services. The domain name involves several segments while separated with a dot between each segment such as Google.com. Domains are registered into databases and supported by the internet infrastructure managed by the Internet Domain Registry. They are setup by Domain Name Service (DNS), a protocol to convert host names and related IP addresses (Lutkevich and Burke, 2021). DNS allows users to access information across the internet by typing human readable language such as google.com instead of 192.168.1.221 etc. (the IP address) Domains are identified by IP addresses facilitating communication between devices with domains via the internet. Domain names may be purchased for a set amount of time to remove congestion of unused/inactive domain names (Lutkevich and Burke, 2021).

#### Explain Contributions to Internet Development:
- They help with identifying location of content (extensions such as .au represent Australia).
- Better user experiences globally as users do not need to input an IP address to access or use content.
- Domains help simplify navigation for all users and improving overall user experience. Helps with consistent memorisable name
- Ties online identity and presence of branding to help users centralise social media platforms and communications etc.
- Domains have supported the development of the internet with its integrated protocols such as HTTPS using certificates such as SSL and TLS to verify integrity of websites and reduce attempts of malicious damage to users and servers.
- Domains have been crucial to the adaptation, evolution and advancement of E-commerce, online education and establishes trust between users and clients


### DNS
DNS is a hierarchical naming database used to simplify communication across the internet. DNS works by locating and translating specific domain host names to IP addresses for multiple use purposes across the internet, this is called a DNS query. When a person searches a domain name DNS fetches the associated IP address to send to the devices request (Lutkevich and Burke, 2021).

#### Explain Contributions to Internet Development:
- Ensuring user-friendly, streamlined navigation. Without DNS users would need to type long IP addresses proving difficult in accessing content.
- Assisting with the transition of services from web hosts without altering web traffic, benefitting client-server interactions
- Enhancing website performance by minimising the time it takes for user's requests to be completed. This helps reduce latency and optimise user experience
- DNS actively prevents and stops users from accessing malicious content, malware and other online threats through DNS filtering and other security measures, helping minimise risks of having sensitive data revealed or leaked.
- DNS directs users to multiple servers based on traffic, preventing server strain. Users are directed to servers with the lowest load optimising performance and enhancing user experience.
- Utilisation of the DNS MX records enables email communication. They facilitate directing incoming email to corresponding mail servers, without it users would need to remember IP addresses for each receiving mail server.

## Q3

### TCP
Transmission Control Protocol (TCP) is a standardised connection-oriented communication method that governs the transmission of packets from origin to recipient. TCP helps to ensure end-end delivery of packets successfully by maintaining and establishing a connection end-end until data is transferred completely. TCP guarantees data integrity and secured delivery across a network. It is responsible in breaking down information into packets, reassembling them and sending them to routers, gateways, switches and destination (Basumallick, 2022). This protocol assists in receiving packets and handles lost packets and flow control making sure each packet reaches its destination. TCP is used in peer-peer sharing, sending and receiving of email & accessing the web etc (Basumallick, 2022). Examples include:
- File transfer protocol (FTP)
- Secure Shell (SSH)
- Internet Message Across Protocol (IMAP)
- SMTP (Simple Mail Transfer Protocol)
- Hypertext Transfer Protocol (HTTP)  

#### Explain Contributions to Internet Development Client-Server:
- Reliable packet delivery via error detections and retransmission of data to ensure delivery of data if corrupted or lost between client and server. This is necessary for clients where data integrity is needed. File transfers, Emailing, Browsing. 
- TCP establishes a connection between client and server prior to data exchange, ensuring orderly tranmissions and retrieval of data.
- TCP helps minimise congestion by using flow control methods to prevent sending too much data. This helps maintain network stability and fairness across resources amongst clients and servers. Prevents receiver from overwhelming amount of data faster than it can process. This is essential as devices may operate at different speeds, helping to reduce network congestion.
- TCP helps to provide reliable, consistent communication and access to information across the internet between clients and servers
- TCP is utilised adjacent with other protocols such as HTTP and SMTP for reliable data delivery between clients and servers.


### HTTP and HTTPS
Hypertext Transfer Protocol (HTTP) is an application protocol and enables a way to load documents or transfer information or content between clients and servers on the web via hypertext.  It works in conjunction with other protocols in the network protocol stack such as TCP to communicate with servers. They are rules allowing communication between web browsers and web servers. Without HTTP browsing the web would not be possible. HTTPS is HTTP but with added encryption technology such as secure sockets layer (SSL) and transport layer security (TLS) certificate (Vukadinovic, 2018). This helps encrypt data transfers between browsers and servers to prevent unauthorised access. These certificates in HTTPS authenticates the identity of websites hence providing legitimacy to websites. They also help prevent interference of data transfers. Without HTTPS, HTTP would transfer plain data non-encrypted increasing the likelihood of data leaks and tampering by third parties (Vukadinovic, 2018).

#### Explain Contributions to Internet Development Client-Server (HTTP):
- HTTP enabled a standardised method for communication between clients and servers. This facilitated interoperability across different devices contributing to the overall growth of the internet. 
- HTTP helped clients in the form of HTTP responses including the requested data. Examples include: retrieving resources such as images and HTTP requests such as form submissions. 
- HTTP's extensible nature propogated extensions helping the evolution and adaptation of new technology accomodating the changes in web applications
- HTTP contributed to the development of the internet as the foundation of the world wide web. It assisted users in accessing and interacting with web documents and applications. Without HTTP navigation of web pages would not be possible.
- HTTP has a cahcing feature allowing clients to store previously retrieved resources improving performance and reducing need for server requests.

#### Explain Contributions to Internet Development Client-Server (HTTPS):
- HTTPS helped with encrypting data transfers between clients and servers. This prevented unauthorised access of information and secured sensitive data through the use of SSL and TLS.
- Digital certificates within HTTPS mechanisms help verify server and client identity certifying correct communication between intended servers and clients.
- Overall HTTPS has helped enhanced security, privacy and validiy of communications between clients and servers with the development of the internet, it has been widely adopted and transitioned from HTTP originally. It has assisted users in accessing web browsers securely via visual cues such as a padlock icon next to browser address bars and prevents malicious attempts to tamper with sensitive information. 

### Web Browser
#### Requests
Web browsers initiate by HTTP requests made by clients to retrieve resources from web servers. This is initiated when a URL is entered or a hypertext link is click sending a HTTP request to server. With the development of the internet, standardised mechanisms help fetch and submit resources from servers and clients efficiently facilitating smooth communication between clients and servers (Humphrey, 2024).

#### Explain Contributions to Internet Development Client-Server:
Web browsers requests have played a pivotal role in client-server transmissions and connection. Requests have defined how web servers and clients respond, retrieve and request resources. It has implemented a reliable, secure and standardised method for different browsers to interact with servers through HTTP/HTTPS or AJAX (Humphrey, 2024). Requests are essential in contributing to the development of the internet as they help ensure data privacy, integrity and enhances the performance of client-server interactivity with the use of HTTP/HTTPS requests. Security and efficient transfer of resources and data help both clients and users gain trust, efficiency and is essential when dealing with sensitive data exchange and optimal user experiences while web browsing (Humphrey, 2024).


#### Rendering
Web browser rendering engines are involved with parsing HTML, CSS & JavaScript for display on web pages. Examples of common rendering engines include: WebKit and Gecko (Felix, 2022). Rendering process:
1. Parse HTML document to establish Document Object Model
2. Parse CSS to create CSS Object Model 
3. Both parsed HTML and CSS are interconnected to construct the Render Tree
4. Layout and Painting. Size and Position of elements on the page are constructed and pixels are rendered on-screen.

#### Explain Contributions to Internet Development Client-Server:
Web browser rendering is a necessary engine to display web pages within the development of the internet. They have contributed to supporting complex layouts and animations and enhancing interactivity optimising user experiences. Rendering engines are always updated with emerging technologies prompting developer use of latest features in applications benefitting users and clients. Parsing of HTML, CSS and JavaScript reduces the loading times of web pages and greatly increases performance of applications contributing to better user experiences(Felix, 2022).


#### Developer Tools
The purpose of web browser developer tools is to help analyze and debug web pages within browsers. It is a great feature within web browsers to assist with viewing source code and identifying errors (GeeksforGeeks, 2021). Common features include:
- Inspector
Inspect CSS and HTML code with the ability to edit for testing, debugging or analysis
- Console
Can log and run JavaScript code 
- Network Panel
Helps with performance analysis by monitoring network requests and responses
- Performance
Analyses rendering performance and identify bottlenecks
- Application
Manage and debug storage, caches and service workers

#### Explain Contributions to Internet Development Client-Server:
Developer tools offer techniques to debug, analyse and edit code in real time assisting developers in creating and optimising code for SEO, improving reliability of client-server interactions and optimal web application performance (GeeksforGeeks, 2021). They help developers identify and solve errors within web applications, analyse rendering performance, network requests and optimisation for better loading speeds leading to faster and responsive web experiences. These tools help encourage creativity and innovative skills driving the advancement of the developing internet (GeeksforGeeks, 2021).

## Q4   

### Interpreters
Interpreters are software that reads and translates source code within high-level languages one line at a time at run time into machine language. Interpreters are generally installed on most machines and are useful due to being platform independent, they must be installed on a machine for source code to be translated. Interpreters save on memory usage by not generating intermediate code in comparison to Compilers (Rouse, 2020). Debugging and testing with interpreters is much quicker and easier as compilation ends while/if any errors are detected allowing users to determine where an error occurred. There are multiple ways an interpreter may work. They may construct output direct from the source code, process the source code through intermediate code followed by execution or use pre-compiled code by an internal compiler to execute code (Rouse, 2020). Interpreters have disadvantages in terms of slower performance because of line by line translation and execution. Examples of interpreters include:
- Google Chrome
- Firefox
- Internet Explorer
- Python
- Ruby


### Compilers
Compilers are software that converts source code to machine or byte code in one instance. They generate a standalone executable file composed of machine code. This executable file is independent of the source code and can be executed multiple times without recompilation. Compilers result in faster execution times in comparison to Interpreters as they do not execute source code line by line but all in one instance (Programiz, 2019). Examples of languages that use compilers include C++, C and Java. The down fall of using compilers in comparison to interpreters is that they are harder to debug, test and/or identify issues in generated code due to conversion via one instance. Examples of compilers include:
- Ruby uses JRuby, IronRuby, Mruby etc.
- Python uses Pypy, Cython, IronPython etc.

### Key Differences between Interpreters and Compilers
| Interpreters | Compilers |
| ---- | ---- |
| Translates source code line by line during run time | Compilers translate entire source code as a whole into an executable object code containing machine code |
| Interpreters execute source code much slower due to lines being translated sequentially during runtime (there are techniques to optimise execution using Just-in-time compilation to enhance performance (freeCodeCamp.org, 2020)), although they analyse source code much faster due to line by line execution on the fly | Compilers take a greater amount of time to analyse source code, execution of executable object code is comparatively faster and may be used multiple times without recompiling code as it is executed directly on CPU without needing to interpret each code line by line |
| No executable object code is generated making interpreters much more memory effective usage, they instead execute source code directly | Compilers generate object code requiring linking resulting in more memory usage |
| Source code is run dependent on Interpreter | Executable code created by compiler is run independent of Compiler |
| Used by languages such as Python, Javascript | Used by languages such as C, C++ and Java |

(Programiz, 2019)

## Q5 
### What is a programming language?
Programming languages are used as a method to allow humans to communicate written instructions to computer language. They help us build, organise and automate tasks through the establishment of specific syntax dependent on languages such as Python, Ruby and Javascript. They supply us with a way to enhance web experiences and development, innovation and creativity. Multiple applications in our daily lives use programming languages such as apps, interactive features on websites or software to name a few (Singh, 2023). 

### JavaScript

JavaScript is an object oriented programming language utilised within web browsers for user interactivity, dynamics,client-side scripting and server-side application. JavaScript may be used to sample audio, change web page structure or style components and more. It has many features built on-top such as API's which allow for interconnected communication between software and applications, this is highly beneficial as they allow retrieval of data from external sources to better web development process (Singh, 2023). Libraries and frameworks which enables easily accessible in-built or third party pre-written code so you dont have to reconstruct code to achieve a particular feature or functionality. JavaScript code is executed by a javascript engine such as V8 created by google. V8 works by converting high-level language JavaScript code to machine language for execution, since JavaScript is event-based enforcing code only transpires after user interaction such as clicking a button. During runtime JavaScript runs on libraries and API's provided by a host environment, examples include: A browser (DOM) or Node.js file systems and networking API's etc. Overall JavaScript enhances user interactivity and experience, has extended functionality and minimises server load by running client-side instead of continually requesting information from the server (Singh, 2023).
                          
### Benefits 
---    
#### Manipulating the DOM  
JavaScript allows you to manipulate web page structure, Example: If text colour needs to be changed to red ,HTML elements may be selected using:
```
const colourChange = 
document.getELementById("element_id_name");

colourChange.style.color = "red";
```
#### Dynamic client-side     
JavaScript brings about dynamic behavior enhancing user experience by establishing direct user interactivity and functionality via libraries and/or frameworks (further discussed below). JavaScript is also cross-browser compatible by all major web browsers such as Chrome, Firefox, Safari  making it ubiquitous (Singh, 2023).

#### Libraries  
Libraries such as jQuery and D3.js optimises productivity and cross-browser compatability. They do so by allowing manipulation of user interface elements making it easier for software developers to target specific requirements within projects and creation of interactive web pages. Helps with scaling applications with extra functionalities for future instances (Singh, 2023).  

#### Frameworks 
Different frameworks serve different purposes required. There are different types of frameworks such as Full-Featured and Micro-Frameworks. Examples include: Angular, React and Vue.js (Singh, 2023). Use of frameworks allows programmers to enhance productivity and performance of applications.   
Example uses:

##### Routing    
- Routing allows for mapping URLs to a component. It authorises the use of single-page apps, navigating without full-page augmenting user experience and SEO through facilitated server-side rendering (Singh, 2023). 

##### Data Binding   
- Mechanisms for data binding through interpolation, property binding or custom directives. This helps with autonymous synchronisation of data between UI and an application's model. It ensures changes are reflected in the UI without manual interference with the DOM. Benefits in reduction in boilerplate coding and responsive design etc (Singh, 2023).


#### Full Stack Web Development    
Used for server side scripting, simplifies web development process and maintenance of applications and web documents. Acts as a pillar for many frameworks and libraries which permits the designing of complex user interfaces, streamlining proceses and provides solutions for tasks from data manipulation to UI design making it a multi-functional purpose language used in Full Stack Web Development (Singh, 2023).

### Drawbacks  
--- 
#### Security risk
Hackers may exploit vulnerabilities due to cross-browser compatability differences injecting malicious content to compromise security systems. The issue with JavaScript comes from scripts that are alterated being undetected, instances such as these warrant unauthorised access of data and system manipulation (snyk.io, 2020). Because JavaScript runs on the client-side, malicious content can be inserted into JavaScript files and processed locally within user environment. The risks associated prove why sturdy security measures need to be invoked to minimise related exposures. Another potential factor increasing risk is  JavaScript's code visibility, this also relates to abuse and exploitation by third parties. Preventative measures to minimise security risks include obfuscation of application code, filtering or validating input by removing malicious characters and client-side or server-side validation (snyk.io, 2020). 

Examples of cross-browser abuse includes XSS, stealing session data or CSRF:
##### XSS  
- They are an injection(s) of malicious scripts into websites. It involve web applications sending harmful code to an unsuspecting user. These threats occur where input is required by a user, the injected scripts may potentially access cookies, sensitive information retained by the browser or even manipulate HTML content (OWASP, 2020).

##### Session Data Stolen
User session ID's may be stolen by client-side browser scripts. These scripts are capable of accessing all content returned from web applications, this includes sensitive data. Hackers can use session ID's to seize and use sessions (OWASP, 2020).

##### CSRF
Cross-Site Request Forgery security attacks occur when malicious content such as a website or email performs functions through a users browser without the user's knowledge. Depending on user credentials, third parties can steal funds or even change the user's password (snyk.io, 2020).

#### Inconsistent Interpretations across browsers  
JavaScript may behave differently across browsers, need to handle cross browser comptability leading to additional testing,debugging and implementations. Additional techniques or code may be necessary to ensure standardised functionality across a diverse range of mediums. Additional code in turn can result in an increase in additional bugs and time needed to develop web application (Matuszek, 2023).

#### Rendering
As JavaScript is extensively used on client-side, this can lead to elevated server loading due to a large amounts of data required to be handled. Debugging tool capabilities within JavaScript results in diminished efficiency during development and productivity in comparison to other programming languages such as C or C++ etc.
JavaScripts interpreted nature makes it naturally slower as source code is executed singularly as opposed to entirely (Matuszek, 2023).

### Python  
Python is another example of an object oriented high-level programming language that is widely used worldwide (Statista, 2023). It is language relying upon providing instructions to our computer resulting in tasks being performed. Due to the easy nature of Python it requires less lines of code making it relatively more understandable and readable in comparison to programming languages such as JavaScript (Kumar and Acharya, 2023). Python expresses its syntax through values or statements such as:
```
print("Hello World")
``` 

It's diverse functionality allows for many uses in rapid application development, data analysis, and automation etc. It may be used for a myriad of visualisations and contains libraries for faster, more efficient programming in applications such as machine learning. Example libraries include: Keras and TensorFlow (Kumar and Acharya, 2023). Python has multiple application purposes ranging from Web Development to AI and machine learning. For AI and machine learning Python has contributed significantly to the advancement and development of AI and machine learning with the utilisation of its libraries and communities. Within web development, Python is highly sought after and is implemented across the industry due to its scalable, dynamic nature with the application of its frameworks such as Django and Flask (Kumar and Acharya, 2023).


### Benefits  
---
#### Easy to use
With its high level abstraction, Python syntax is easy to learn and write code quickly reducing the time needed for devlopment, progression, testing and debugging. It contains simple syntax enhancing readability and comprehension. Its easy nature is compounded by its versatility in a wide range of applications and assists programmers in reducing cognitive loading whilst increasing productivity. It is applied cross the industry in areas involving data analysis to AI and machine learning (Kumar and Acharya, 2023).

#### Features and Functionality
A vast ecosystem of libraries (NumPy, Tensorflow) and frameworks (Django, Flask,) accelerates development of applications and boosts productivity during development stages. The libraries contain pre-defined written code that can easily be utilised within projects removing redundancy and improving efficiency while developing an application. Python is extensible in collaborating with other languages to support specific requirements within a project. Numpy may be useful in computing numbers whereas Django and Flask can be employed when building web applications. Its functionality may also be embedded into other applications such as Java or C++, allowing for use of a diverse range of programming languages (Kumar and Acharya, 2023).

#### Scalability
Due to Pythons ability to analyse large datasets it plays a pivotal role in handling and processing data across many devices with the use of its libraries and frameworks. This is one of the fundamental reasons Python is used in applications involving AI and machine learning. It is scalable in nature based on its design, fostering quick prototype production contributed by its ease of use. This helps support multiple programs and offers flexibility while coding making incorporation of Python into existing projects simpler and time effective (Kumar and Acharya, 2023).

 ### Drawbacks  
---
#### Slower due to Interpreted Nature  
Due to Pythons interpreted nature, code is executed line by line and in turn slowing down processes leading to higher memory consumption and slower execution in comparison to languages such as C++ or java especially in CPU bound tasks. With its need for dynamic typing there is less control over the types of data that may be used. (Kumar and Acharya, 2023).

#### Global Interpreter Lock (GIL)
Python contains a Global Interpreter Lock (GIL) limiting the functioning of multi-core systems, allowing only for a single thread to execute Python bytecode simultaneously. Applications requiring multithreading are limited in what they may perform and function (Kumar and Acharya, 2023).

## Q6 

### Professional Email Response

Dear Alex,

I appreciate you contacting us at Peter's Software Development regarding the construction and design of your website. It is with great pleasure that I take up this opportunity to discuss with you in detail your website design, structure and the constituents that will be needed to run your website smoothly for both you and your visitors. I will provide a proposal that aligns with your requirements and goals.

I understand that you plan to create a website for your new museum within the city to showcase various interesting artefacts, objects and paraphernalia from all over the world. We also understand that you would like for a high volume of traffic to visit your Super Awesome Museum (SAM) and believe we're the perfect match in helping you achieve that. With your goal in mind I guarantee your satisfaction in achieving a friendly user interface and experience for your visitors that aligns with your goals and effectively represents your museum's identity.

To ensure we meet your expectations we will propose the following technologies and tools mentioned within our project proposal. We have outlined a brief summary of what each technology & tool is appropriately used for to help you better understand their purpose and role in the development of your website. I have attached a proposal outlining the scope of the website, a timeline and cost estimations based on your requirements and the required tools and technology.

[Project_Proposal](./Project_Proposal.md)

The addition of the discussed technologies and tools is paramount to the success of your websites design, functionality and features for you and your visitors. It follows best practices and industry standards with the creation of websites. Each of the mentioned technologies and tools will help simplify managing, tracking and editing your website proficiently. We will be integrating responsive designs, a navigation map directing clients to your museum and a beautiful contacts page in case visitors need to keep in touch with you. Styling with CSS will help retain your visitors, boost user experience, optimise user interface and search engine optimisation - if you ever feel the need to advertise your museum to attract more visitors.

I guarantee your satisfaction as our client, with my years of experience as a web developer who has helped over 100+ clients I can promise we reach a goal far beyond your expectations. I am committed to providing high quality websites and will ensure the same occurs for you as with every other client of mine.

While I develop your website, I will warrant transparency throughout the whole process. I encourage and appreciate feedback while we collaborate to incorporate many interations to your website based on your feedback at each stage. I will keep you regularly updated and guarantee the end result meets your specific needs and goals.

If you have any questions, concerns or would like further clarification with any aspects of the website or proposal feel free to let me know and I will help you to the best of my abilities. I look forward to the possibility of working with you on this great website. 

I thankyou for regarding my services. I am excited to help bring your museums vision and interests to life with your website.

_Warm Regards,_

_Peter_

**Director**

**Peter's Software Development**

## Q7 
### Gibb's Reflective Cycle for Past Assignment T1A2 Portfolio
A cyclical cycle to aid with affective reflection techniques via six stages of experience. This involves description, feelings, evaluation, analysis, conclusion followed by an action plan. It is a reflective cycle developed by Graham Gibbs, a psychologist, to help individuals learn from experiences. Useful for repeated experiences to identify and analyse issues and possible improvements within your experiences. (The University of Edinburgh , 2020)

#### Description
For a previous assessment I worked on I decided to pre-plan my objective on completing the assignment. I had used a colour kit, wireframes and trello. I started the assignment the week of release by myself. I mixed colours using coolor for the web document, wireframes to structure the website and trello to manage each task. The outcome of the situation is it didnt go according to plan. I had no clear direction on how I wanted my portfolio to be displayed and colours to use. Therefore, I spent a majority of my time finishing the assignment coming up to the deadline.

#### Feelings
I was confused and overwhelmed with picking the right colours and I had feelings of self doubt, anxiety and fear of not meeting my own expectations. I felt disheartened and felt I had not made much progress or would not get a good mark after putting so much effort into it, I didn't feel confident enough leading me to procrastinate and prolong finishing it. Before the assignment was released I was much more confident, ready to tackle the assignment and was aiming to achieve the best result I could. I was looking forward to the assignment and was excited to do my best prioritising my time into it. After the assignment was complete I felt a big sense of relief, accomplishment and was happy that I did my best and gave it 100% regardless of what mark I was going to receive. I believe it was not only my situation that was difficult I believe everyone had difficulties as well. Lack of time, anxiety, fear of failure, self-doubt, stress, imposter syndrome. After the assignment was complete I believe others in the CoderAcademy cohort also felt a sense of relief, accomplishment and fatigue. Looking back, im satisfied with the amount of work I put in and dont have any regrets.

#### Evaluation
First off the evaluation of the good aspects of the assignment. The things that worked well was I produced a good quality portfolio before the deadline. It clearly strengthened our understanding, knowledge and application of web development in terms of HTML and CSS. This experience lead me to become much better at HTML structuring with element names, syntax and HTML's skeleton. I had a clearer and greater understanding of how flexbox and grid components work for implementation of responsive designing of webpages. It cemented my understanding of styling using CSS and helped me explore both HTML and CSS in-depth to achieve a greater portfolio display. The overall experience of the assignment is a positive one, you are taught self-discipline, adversity, building a portfolio, deployment and repository techniques all in a short period of time and providing good quality work. It was well worth it. 

#### Analysis
I believe the assignment went well due to starting early and staying consistent dividing each requirement within the rubric into manageable chunks daily. It went well as I kept a positive mindset and self-reflected each day asking myself if I could do more to achieve a better outcome what would that be? I contributed to the assignment in a positive manner believing that even though it was difficult & emotional I would still strive to achieving the best I could as it was an invaluable experience. The bad experience of the assignment wasnt much. I would mention the time required to build the portfolio as the main negative aspect although I do take accountability in completing the assignment in a swift and efficient manner. The things that clearly didnt work for me was my own planning, time management and prioritising of specific tasks leading to hours spent on picking out different colour patterns, and hours on planning the display of each graphical and text component. It didnt go well as I had no clear understanding of HTML and CSS and was changing my intial plans during the process. This lead to me changing wireframes and colour schemes consistently. It cost me more time and energy than necessary. I believe a majority of my struggles was due to inefficient planning which would have reduced the need for additional reflection or mental burdens. It would also have provided me with better autonomy and motivation had I research effective planning techniques, not just write down tasks and layouts and not follow through. 

#### Conclusion
In conclusion I learnt that I lacked proper time management, prioritising of specific tasks and initial planning. I learned that planning would have provided me autonomy, motivation and saving resources such as time - having implemented better planning would have made it possible to put the portfolio together more efficiently without going through and picking multiple colour schemes and layouts. Overall I will continue to apply planning techniques such as SMART frameworks for future and current assignments due to its added benefits and the accountability it provides (University of California, 2017). Lastly I learned that not everything goes according to plan and expectations, sometimes you'll need to adapt and self-reflect on where you went wrong and what could have been improved. This self-reflection technique has taught me to be much more critical with my approach to completing tasks and to plan, organise, manage and prioritise my time and tasks better.

#### Action Plan
Next time if I had the chance to redo the assignment these are the things I would do. I would first and foremost read and comprehend the rubric completely this would help me grasp what is required and make me think of ways on approaching the assignment. Next I would plan. Planning by using trello much more regularly and write down when, how and why I expect tasks to be done this would help give me a clearer purpose, structure and understanding of tasks. I would start off with solely the colour scheme first and be happy with it before proceeding to the layout this would help save time as it wont be an intermittent back and forth scenario where I continually implement changes to either the layout or colour scheme. I would try and implement a framework such as SMART, stands for specific, measurable, achievable, relevant, time-bound leading to effective planning (University of California, 2017). Finally I would try avoid the negative emotions of anxiety, fear and lack of confidence repeating to myself that I can do this, remembering that a positive mindset will lead to better outcomes (Lonczak, 2021).

## Q8 
### Action Plan
My plan is to engage and continually attend and complete specific tech conferences, tech certifications and engage in meetups or forums. I am planning to prioritise my time in building up my technical skills by engaging in multiple leetcode challenges to prepare myself for potential interviews. On the side whilst building up my skills and knowledge with different languages I plan to build multiple projects to showcase on my GitHub for prospective employers or hopefully kickstart my own business or project to solve issues relating to technology, maybe an application that helps compare prices between different companies to help consumer decisions. I intend on attending the following:

#### Networking and Opportunities    
With my action plan I hope to engage with every available opportunity and experience to better my chances for employment. I wish to network with many like minded people, sharing my opinions, listening to other opinions and contributing in a positive way - this could involve attempting to solve technical problems, challenges etc. I will continue searching for more opportunities and network with an open mind and positive outlook. I would like to:   
- Keep updated on trends in technological advancements, cybersecurity and innovations  
- Network with industry leaders & peers
- Increase potential employment opportunities and partnership
- Gain insight into best practice and industry benchmark

##### Tech Conferences  
- **MongoDB on July 30th**  
Link: https://www.mongodb.com/events/mongodb-local/sydney
I have registered for MongoDB attending on July 30th at 08:00am. I hope to expand my knowledge about MongoDb and see its various capabilities in building data-driven applications. I plan to engage with speakers, network with like minded people and further my technical skills with MongoDb through note taking of live demonstrations and keeping track of the latest products and technology emerging. 
I have taken the necessary steps to register for the session on July 30.

- **Google I/O Extended on June 29th** 
Link: https://events.humanitix.com/gdg-sydney-x-google-i-o-extended 
With google I/O I would like to learn about the newest technologies and latest advancements with a deep-dive session. I also hope to network with other tech enthusiasts to hopefully open up more opporunities and positive contributions. This experience will assist in providing me insight from tech professionals to grow my career. 
I have taken the necessary steps to attend the session on June 29 by registration. 

##### Local IT Meetups
During local IT meetups I plan to connect with local professionals in similar tech industriers to share and gain knowldege through discussions including challenges and exchanging solutions. I am eager to build rapport amongst peers and expand my network for progression of my tech career. I intend on collaborating with others to create projects and optimise my chances in gaining freelancing opportunities

- **Ruby on Rails Oceania Sydney**
Link: https://www.meetup.com/ruby-on-rails-oceania-sydney/
Ruby on rails does not currently have any upcoming dates but I do plan on attending the next available session by regularly keeping track of the event. With ruby on rails I would like to expand my network and engage with several people involved in the tech industry. I plan on learning about industry leading web applications, discussions about the framework ruby on rails and further my knowledge about the programming language to add to my technical skills which I can use to help translate towards my resume. I hope to learn a great deal more from other tech professionals and contribute positively, occasioning my career growth.

##### Professional Certification and Training 
I plan to validate my technical abilities and credibilities by accomplishing accredited certifications increasing my likelihood of employability. These certifications will help demonstrate my commitment to learning, expand my knowledge and optimise my projects outcomes. It will further enhance my career prospects and reliability within the tech industry. I have taken the necessary steps to engage in certifications such as these:

- **CoderAcademy 2024 April Standard**
I have undertaken gaining certification in CoderAcademy's Full Stack Web Development course starting April 29th April 2024. I hope to develop my technical skills as a full stack developer and gain in-depth knowledge of the industry best practices and the appropriate tools and technology recommended as a professional full stack developer. I have continually networked with peers within my class and continue to engage with educators and plan on attending any events that are announced within the discord channel to increase my opportunities for career growth.  

##### Tech Forums and Communities
I will utilise tech forums and communities as a free way to share insight and help resolve problems by positively contributing. I plan on building up my online presence and  reputation within these communities and have started by creating accounts on each platform. I have subscribed to and joined multiple tech communities within the below forums. Engaging with tech forums and communities will help me stay updated and provide me with continued learning and improvement, the opportunity to network globally and potentially provide me a partership or freelance opportunity.

- **Reddit**
Link: https://www.reddit.com/
I have started by using reddit more frequently and have followed multiple tech communities within this forum. I plan on contributing and engaging with like minded professionals in the tech industry on reddit to procure potential freelance opportunities or employment. Regardless I hope to network with multiple peers globally which would be an advantage of using Reddit.

- **Leetcode**
Link: https://leetcode.com/
Leetcode is for me to advance my tech skills and knowledge with challenges and discussions. I hope to strengthen my hard skills such as Python and JavaScript by completing the challenges and engaging in discussions in resolving the challenges. I plan to network with the people I collaborate with and open up more pathways in getting into the tech industry.

## Q9 
### LLM (ChatGPT)
ChatGPT is useful technology used in reducing the need for extensive coding, repetitive phrases and streamlining certain aspects of a project or report.  
Chatgpt may be applied in multiple facets of projects or written reports:  

### Reports (written works)

#### Content generation & Editing
ChatGPT may provide written works such as reports a foundation to write on determined by specific topics or outline or drafted content. LLM may also provide useful insight and extensive information or explanations on requested topics with examples and analyses allowing for comprehensiveness. ChatGPT is used for proofreading and correcting sentence grammar & punctuation or providing alternative ways to structure sentences ensuring accuracy and clarity. The technology is useful in analysing consistency in language styling within documents further optimising coherence and readability. When prompted ChatGPT may draft multiple reports tailored to user requirements inspiring ideas, creativity & expansion on certain key points generated. It is also used in crafting certain sections withIN reports such as introductions, conclusions or methodologies or assists with structuring reports with examples and guidance. LLM have been created with the task of processing and producing text or content (AIContentfy, 2023).

#### Summarising information & Data Analysis
LLM such as ChatGPT is useful in condensing large amounts of information into more concise, brief and manageable summaries for written works such as reports. It can assist with quick access to relevant literature and information from a variety of sources within a database assisting users in obtaining and writing relevant, quality reports (Ray, 2023). ChatGPT can provide feedback on submitted information and suggest improvements in formatting, identifying typos and the overall consistency of written work. As ChatGPT obtains information from a large dataset involving a range of sources, it is capable of analysing large amounts of data efficiently and returning accurate findings (Deore, 2023). This is used within scientific works as key topics may be summarised and further supported with evidence provided in the form of data. Examples include: Surveys & Large Population Studies. ChatGPT also has a huge influence with developing and propogating scientific research, processing data, and producing hypothesis for written works (Ray, 2023).

### Software Projects (technical works)
#### Generating and/or Optimising Code

Within the software development industry software developers have utilised ChatGPT to further enhance their code to improve efficiency and performance (Litwin, 2023). They may also take advantage of suggestions on execution or alternative solutions of code recommended by ChatGPT. Examples include snippets of code to execute loops and remove redundancy following industry practices of DRY principle. LLM may be incorporated to aid in creating templates, frameworks or boilerplate code reducing workload and increasing productivity for developers. LLM such as ChatGPT has been utilised in software projects to generate code for 3D printing by analysis of variables relating to printing, its use has greatly depressed usage of resources and time helping developers contribute to other areas of a project. Overall ChatGPT's reliability within software projects have been studied concluding its successful reliability in different programming languages but does contain limitations (Beganovic, Jaber and Almisreb, 2023).


#### Documentation
LLM may has been used for the automated documentation of code in past studies. It has played a significant role as a programming assistant writing accurate detailed documentation for software projects consisting of user manuals and API documents for readability within a diverse audience (Waseem, 2024). It is also used for generation of comments or feedback to describe code assisting developers in understanding and managing projects. Within a software development company, ChatGPT has been used to summarise progress and suggest improvements assisting project managers to align objectives with specific requirements from clients and stakeholders.  

#### Fixing Bugs & Analysis
Use of ChatGPT may help trace root cause(s) of error or point to specific lines of code where errors may be caused. LLM provides a fast and efficient model in identifying, analysing, fixing, predicting and explaining fixes for specific bugs by analysing code and recognising patterns within programming. Previous findings have suggested the reliability of ChatGPT's performance in resolving bug-related issues noting its competence (Rahmaniar, 2023). Auxiliary applications with ChatGPT such as its dialog systems have further enhanced the LLM's success rate in fixing bugs within software projects. Integrating ChatGPT with other toolkits specific for debugging have proven to be substantially effective for debugging efficiently. As a result software developers can use LLM together with other debugging toolkits to take the necessary precautions to reduce future instances of similar errors or bugs.

## Q10   
### Language Learning Model Technology     
### What is Language learning model technology?    
Language learning model technology also known as large language models work by having artificial intelligence understand and transcribe information from a large data set into generated content using deep learning (Stöffelbauer, 2023). Issues arise when LLM are used inappropriately although it may be unintentional, this still raises legal and ethical concerns. Ethical and Legal concerns involve:    

#### Plagiarism  

Using text generated by language model without proper attribution or acknoledgement constitutes plagiarism potentially resulting in legal repercussions in academic and professional settings. When incorporated by multiple individuals or entities, LLM perpetuates plagiarism, lack of originality, integrity and intellectual property rights concerns. Large language models lack source referencing and so information that is provided may be unrealiable or copyrighted, therefore employing any of the particulars given may infringe rights or have academic repercussions as a consequence. It will greatly affect reports as information given by an author may have been used similarly elsewhere resulting in academic and legal penalties  (Elkhatat, 2023). In the case of software projects, trust and transparency are well considered virtues between stakeholders, clients and software development companies. If information or processes within a projects scope is completely dominated by generated content from LLM without accreditation, legal risks with plagiarism and negligence increase leading to economical difficulties, lowered reputation and reliability as a software development company across the market. Software companies will in turn lose trust and business with stakeholders, clients and users, a great economic loss. In terms of projects and reports plagiarism has substantial compounding effects on integrity, quality of work and skill development. With the use of LLM such as ChatGPT a majority of content published in reports may be exploited and copied removing the need for research, critical thinking and communication. It deprives the author of necessary cross-examining of information leading to potentially unreliable information being submitted (Sedaghat, 2024). Plagiarism also prompts legal complications such as expulsion, legal costs from copyrighted context and serious academic penalties respective to written reports.

#### Real-World example of plagiarism using chatGPT.    

The overall impact on both the development of individual hard and soft skills becomes diminished when using ChatGPT alone (Westfall, 2023). Students become over-reliant and negligent with accessing other sources of information leading to possible inaccuracies and generic reports lacking creativity or diversity. With consituents generated by LLM applied throughout a project, diversity of project objectives & structure, competition within the market & unique user experiences become obsolete (Westfall, 2023).

#### Accuracy of information  

LLM use a large data set to abstract information to formulate generated content. The generated material may be misleading and inaccurate, leading to legal liability issues and negligence in cross checking validity of components, putting reports and/or software projects under scrutiny leading to questions about the credibility of the author or company. Ensuring accuracy and reliable information cannot be guaranteed because information across data sets may not be credible. This strongly engenders report invalidity and encompasses a range of possible legal issues with copyright infringement, misinformation amongst peers & academic researchers & legal affairs which may involve costly damages imposed due to the authors negligence with respect to reports written. Within a software development company incorrect code generated by ChatGPT may result in errors causing wasting resources in debugging and testing and lowered productivity towards a projects objectives. It will misplace trust with stakeholders, clients and users as output brought about by ChatGPT may lack creativity and context. For academic research regarding projects, utilising components generated by ChatGPT may result in attending to consequences such as repeating an academic subject(costly consequence), expulsion and failing the subject (Ray, 2023). 

#### Real-World example of Accuracy of information using chatGPT.  
 
In the medical field there are ethical and legal concerns involving ChatGPT's inaccurate diagnoses (Bhattacharyya et al., 2023). Correct and reliable information & medical content is critical in regards to the well being and progression of human life, misrepresented information can cause inaccurate dosage of medication and treatments. Examples such as these further demonstrate LLM's potential lack of reliability as a source of information and indicates the adverse effects it may impose on society. 

#### Abuse and Bias
ChatGPT is subject to abuse as it generates natural human responses. Overuse of technology that results in misinformation and devoid of source referencing results in spreading misinformation and potential abuse by impersonation. Examples include programmers who misused ChatGPT to post answers within Stack Overflow only for a majority of answers inputed to be false (Guleria, 2023). In regards to reports, LLM may be used to yield a complete report involving skewed views on specific topics. As LLM's learn from a large data set, those data sets may be limited and contain outdated and/or inaccurate information subsequently removing the reliability of a report. ChatGPT also has ethical concerns with its use due to the bias nature and its capability to perpetuate misconceptions, on top of concerns with implementing education influenced by AI (Guleria, 2023). Within projects abuse of chatgpt may result in lack of context or exaggerate coding errors. An example of this would be a black box system where inner components are not easily interpreted hence fixing or resolving errors becomes problematic causing delays with project release, issues with client expectations and possible negative user experiences when using a product. Reports abusing LLM's may result in academic penalties such as expulsion or failure and legal penalties regarding intellectual property rights.

#### Real-World example of abuse using chatGPT.  

Abuse of LLM enables a dependence on information being imparted by ChatGPT. It may inhibit the growth of software developers in software development workspaces and forces a generalised approach in solving questions without needing thought, analysis or revision respective to reports and projects. This has an overall detrimental impact on a software developers quality of work and credibilty within the industry (Davis, 2023).

## Q11 
### Hard Skills
#### What are Hard Skills in a software development workplace & why are they important? 
Hard skills relate to technical abilities that may be taught and measured through progamming. They may be further learnt and developed over time. Hard skills are vital for enhanced project outputs and the development of the project itself. It is a required skill and culminates organised assigning for specialised roles, client satisfaction and meeting requirements, provides foundation for creativity and innovation, technical knowledge to perform tasks and roles essential for a prospering software development company. Acquired hard skills translates to assisting writing clean, maintainable code, improving quality of software and reducing likelihood of bugs and errors (Borges and de, 2024). Hard skills enhance reliability and credibility of individuals competence in accomplishing specific tasks. A positive consequence from adopting hard skills is acquiring the ability to adapt to newly emerging technology, debugging and creating solutions, and contributing positively towards desired objectives. Hard skills are the foundation for progression within software development companies, without them it becomes impossible to contribute to technical constituents (Borges and de, 2024).

### Examples of Hard Skills in a software development workplace
#### Stylesheet Language      
This refers to languages such as CSS (Cascading stylesheet), involving the design of applications, webpages etc. Cascading stylesheet may be learnt and used in conjunction with HTML to help edit HTML elements. CSS is paramount to enabling an entertaining and user-friendly experience for each visitor, essential to roles such as UI/UX designers and software developers. Stylesheet languages positively magnify the presentation and aids with aligning the displayed content with design requirements (Blansit, 2008). Styling elements ensues positive user experience and usability, in turn attracting new users and retaining current ones. With technology rapidly proliferating, there are a wide assortment of screen sizes and devices. CSS contains certain tools such as; Media Queries, CSS Grid, CSS Flexbox to standardise user experience regardless of the device being used. Responsive designs using media queries, grid and/or flexbox enhances accessability and encourages diverse compatability with devices. With hard skills such as CSS, a projects target audience may broaden to reach more users and overall result in greater economic benefit as well as stakeholder, client and user satisfaction (Blansit, 2008).

#### Markup Language       
Markup Language refers to languages such as HTML. HTML is  crucial in web development and helps design a websites structure, layout and presentation. As markup languages such as HTML are extensible in nature, it is recommended knowledge when working with other languages similar to Javascript & CSS. HTML is used in association with CSS and Javascript to write functionally and visually adequate applications and software (Huddleston, 2018). Having a hard skill such as markup language knowledge and application will be beneficial in integrating with other languages to augment user interfaces and excel user experiences. Markup languages help with search engine optimisation leading to higher conversions within advertisements potentiating new user traffic which promotes economic growth, this is favourable for software development companies in meeting stakeholder and client needs within a projects scope (Huddleston, 2018).

#### Programming Languages         
Programming Language refers to languages such as Python and Javascript. They help translate human language into binary,  helping computers understand and execute the code we provide. Programming language as a hard skill is desirable within a software development workspace. This hard skill further perpetuates, critical thinking, analysis and problem solving skills within the technical aspects of a project. Tools such as libraries and frameworks within common programming languages such as Javascript and Python amplifies developer productivity by mitigating redundancy while coding and simplifies troubleshooting and debugging tasks. Overall a deep understanding of programming language(s) can help streamline particular tasks, optimise computer performance, Save on memory usage, increase workload & optimise application performance within a software development workspace (Bartlett, 2022).
Knowledge of programming language is valuable as these languages are favoured towards specific applications such as:  
- Rapid development of applications
- Automation of tasks using libraries and frameworks 
- AI development
- System-level programming
**There are two types of Programming Languages:**    
1. **Low Level Language**  
Low level language such as Assembly language are more easily recognised by machines and offers much more control and efficiency in applications as they closely match underlying hardware architecture. They manage and handle hardware resources directly including: CPU & memory. Assembly is represented by using mnemonics to process machine operations. It's special applications are carried throughout tasks involving embedded systems & device drivers. Having hard skills such as Assembly additionally maximises performance, speed and execution of software within a software development workspace. With all the enhanced variables mentioned, client & stakeholder goals and expectations will be supplied within a projects scope. This will ameliorate user experience and interactivity with rapid application loading time & augmented execution of interactive components (Eggleston, 2023).
key features of using Low level language such as Assembly include:
- Manipulating hardware directly within an embedded system
- Highly efficient as they minimise abstractions and operate closer to machine language increases speed and saving on memory usage
- Required language for applications such as game development & high-performance computers as it provide fine grade controlling leading to optimal performance.

2. **High Level Language**   
High level language introduces a more understandable way for people to transcribe our language into machine language via compilers and interpreters for machines to better understand. A hard skill that is easier to understand, maintain, read (due to its syntax) and has portability across systems reducing the need for modifications throughout different platforms. This makes high level language easier to debug and collaborate with (GeeksforGeeks, 2023). Examples of High level language include: Python & Javascript using words such as: IF, ELSE, IN. With ease of usage and readability, this reduces the learning curve for implementation into a project and opens pathways for adaptability across various environments. They also come with built-in functions which may be imported and used allowing developers to use pre-defined blocks of code. In the best interests of a software development workspace, knowledge of a high level language would greatly enhance productivity and abstract complexities (GeeksforGeeks, 2023). Applications include:
- Data analysis
- Machine Learning or AI Development
- Web Development
- Server-side Development
 
#### Debugging and Testing  
Debugging and testing within projects in a necessary hard skills within a software development workspace. These techniques extensively guarantee quality assurance for users and clients and positively project the responsiveness of software. Debugging while developing software is essential in identifying potential bugs and errors during coding stages to verify the program executes as intended and meets necessary specifications (Codemotion, 2023). This hard skill helps developers improve their examination and problem solving skills associated with error reports resulting in a properly functioning product which delivers a seamless experience for both users and clients. During prototype phases or before product release developers, software testing engineers and QA (quality assurance) engineers, test and evaluate product functionality, display and technical components. Testing reassures both clients and users of quality, usability, compatability and adherance to projects specifications. It reduces risks of poorer performance, security and system failure and vulnerabilities with data. Without testing, errors/faults become a greater economic burden in the later stages of development (Codemotion, 2023).

### Soft Skills
#### What are Soft Skills in a software development workplace & why are they important? 
Soft skills involve an individuals personal abilities that are developed over time which are beneficial to all aspects of a successful software company ensuring for smoother processing, systems and outcomes. Soft skills are critical in unifying ideas, communication and cooperation within a software development workplace and are essential to understanding and accomplishing stakeholder & client needs. They are beneficial in receiving and providing feedback, fostering a positive environment. Overall soft skills proliferates productivity towards objectives and decreases contingencies when constructing software. Soft skills may be cultivated over time through persistent communication, experience and teamwork (Codemotion, 2023).

### Examples of Soft skills in a software development workplace
#### Communication         
Beneficial in conveying ideas, resolving technical difficulties and communicating bugs or changes within projects. To collaborate and work effectively in group settings communication is a key ingredient in confirming each individual role, project goals and deadlines are understood. A way to avoid misunderstandings and reach common ground and further facilitate fluid teamwork is by constructively communicating to maintain team dynamics for better project outcomes (Codemotion, 2023). Conflicts are common within software development workplaces as disparity in priorities arise, communication reduces workplace conflict and benefits decision making, inspires creativity, leadership and management of teams, resources and stakeholder and/or client requirements. All these qualities and promises that communication has to offer greatly convenes a successful development workplace (Codemotion, 2023).

#### Managing Time    
In a software development company management of time is critical as teams must meet deadlines while delivering quality in fast paced environments. Effective utilising of time enables efficient allocation of resources and budgeting towards other areas of projects and minimises wastage while productivity increases respectively. Without proper time management projects may be rushed and quality assurance may be compromised affecting user experience, and unfulfilled objectives (Codemotion, 2023). It is also crucial in planning priorities within a projects scope, if time management is insufficient this endangers a software development workplace achieving required specifications and meeting client, stakeholder or user needs. Time must be managed accordingly to reduce the possibility of errors, interruptions and decreased team morale to name a few. Time may be better managed when used as a soft skill adjacent to communication ensuing expected project requirements (Codemotion, 2023).

## Q12 
### Project Manager
Project managers are responsible in facilitating successful coordination and directing of components in a project. They are responsible in evaluating optimal planning and execution to reach project objectives and overseeing the entire project. They assess and manage associated risks, resources and prioritise business goals in regards to the objectives (Project-Management.com, 2018). Their roles include:

#### Team Management    
They assure smooth processes and systems are in place promoting professional communication, collaboration and provide essential support. Project managers are expected to assemble and allocate specific responsibilities to teams. They liaison between development teams and clients making their role essential in delivering concise communication to minimise any room for error with aligned goals (Project-Management.com, 2018). Project managers also commit to peripheral activites such as encouring team morale, leadership and motivation. Team Management is required for organised cooperation within group settings, increased productivity and effective communication and understanding of delegated tasks.

#### Risk Management  
Their role is to proactively manage risk, this involves any potential risks that may arise in the process of developing software. Some effective risk management methods incorporate systematic risk assessments to identify prospective risks that may potentially influence project objectives. Analysing and minimising risks while developing software are all activities project managers must attend to (Project-Management.com, 2018). Risk Management is crucial, it is a necessary means to reduce costs, automate processes, improve efficiency in workload output and handling of obstacles.  Examples include:    
- Delays with projects  
- Budget Management  
- Susceptability of Security  
- Any technical obstacles    

#### Budget Management  
Budget managing is a key component of being a project manager within a software development company. A role imperative to the success of a software development company, without proper allocation of resources possible contingencies of overrun may occur as well as reduced coherence when developing software (Project-Management.com, 2018). Some attributes include:
- Hiring Software Personnel
- Software & Hardware
- Costs for Operations
- Backup Funds
- Product Backlog

### Product Owner  
Product owners are designated to a scrum team, an adopted framework involving a self-organised approach to assist with project progression through small incremental workloads. They set the priority of the teams success utilising small blocks of work  called sprints (Simplilearn, 2020). Product owners facilitate the overall outcome of the project, they are in charge of:   
#### Product backlog     
Product owners create, manage and optimise product backlog to maximise a products value. They are responsible in adapting to the backlog, processing estimates and any changes in requirements after or during feedback from customers (Simplilearn, 2020). 
#### Arranging sprints      
Product owners are required to manage teams via scrum framework by arranging sprints to maximise efficiency of development teams to achieve expected outcomes and must recognise areas where necessary for improvement. They observe and discuss expected outcomes that scrum sprints should accomplish and when to release things (Simplilearn, 2020).   
#### Communication & Stakeholder Managing    
Product owners must know requirements of the business and clients, they must have knowledge of the value being delivered to clients and repeatedly communicate and collaborate with stakeholders. They are responsible for communicating between software developers and stakeholder management, ensuring the needs of stakeholders are satisfied and clarity is provided to ensure goals, vision and priorities align with the objective. They must guarantee clear instructions, strategies and objectives are communicated taking into account any feedback or changes that need to be evaluated or implemented (Simplilearn, 2020).

### Software Developers  
Software developers are responsible for the hands-on technical side. They conduct the coding behind the software and implement effective strategies in executing solutions and the code itself while maintaining best coding practices and coherent communication (Technojobs, 2019).
Their role includes:
#### Programming/Coding  
Creating and further improving programs, applications while identifying any errors or solutions within software or systems, encompasses testing and debugging. Governing software by maintenance and regular updating for practical improvements and usage (Technojobs, 2019). 
#### Collaboration & Use of Version Control    
Use of remote repositories such as GitHub for Version Control. This helps assist software developers in tracking, storing, reviewing and making changes to code. Version control is paramount for success within software development companies, it allows for easy continuous integration and a sound understanding of any changes made within source code in turn assisting with identifying potential errors (Technojobs, 2019).
#### Communication, Teamwork  
Software Developers usually work in scrum teams. They are expected to provide recurrent communication to product owners, project managers, UI/UX Designers etc, to confirm the objectives align with client expectations and to review and enforce any changes requested. Succinct communication and teamwork play a significant role in a software development company. It boosts engagement, encourages feedback, resolves issues and reduces workplace conflict (Technojobs, 2019). 

### UX Designer/UI Designers
UX and UI designers are designated to manufacturing a professional, user-friendly experience and interface. UX designers focus on the user experience whilst UI designers work on user interface. They create wireframes, mockups, analyse, design & prototype in conjunction to receiving and dispensing feedback. Great UI/UX designers help increase conversions and attraction towards released products, an economically viable decision (Zwidryn, 2023). 
They are pivotal in:
#### Designing for Visual Appeal    
**UI Designers** are essential in developing a projects visual aspects. This may include content such as buttons, logos, text font etc. They design for ideal user interactivty, convenience and visual appeal all key factors in software development as these are the intial features users are exposed to (Zwidryn, 2023).   

#### Research, Analyse, Adapt
**UX Designers** are accountable for researching potential risks, threats and opportunities to determine viability of designing the product after analysis of the current market.
They obtain information within meetings to determine user needs, objectives, discussions if in doubt and the deadline.
Research through the markets helps with identifying current trends and feasible designs, inspiring a myriad of ideas for designers (Zwidryn, 2023).  

#### Testing and Prototypes
In software development companies UX/UI Designers are expected to create wireframes, prototypes and receive feedback for any alterations necessary to meet client needs.
They must cater to and fully undestand specific needs after consideration of niche audience, advertising and overall expectations (Zwidryn, 2023). In doing so, UI/UX designers are constantly cooperating with clients, software developers and testers. This helps align goals with ensuring proper functionality and a visually pleasing user experience.
##### **Wireframes**  
Wireframes help as a blueprint in conveying ideas and structural design, defining the layout and functionality without any designing such as colours & images. A mandatory process for UI/UX designers to discuss and show off placement of items within interface to stakeholders early in the process of designing (Zwidryn, 2023). Wireframes are crafted schematically as a sketch representing different stages of progress with the design, industry standard tools such as **Figma** and **Balsamiq** are often used. They are categorised as:
- **Low Fidelity**   
Easy and quick process to display for prospective clients, users and stakeholders for discussions and improvements in the early stages of designing. Functionality isnt completely defined with low fidelity wireframes, these types of wireframes are generally to display and communicate structure, layout and navigation. Represents a sketch to promote conversation for greater ideas and making minor changes if necessary (Pernice, 2016).
- **High Fidelity**    
High Fidelity wireframes are used when functionality and navigation across pages have been defined and acknowledged. They tend to be a more realistic representation of the final product, serving as a checkpoint before approval and coding commencing. They are still namely wireframes as they still encourage feedback and improvements (Pernice, 2016).
- **Prototypes**  
Prototype are identical depictions of the final product. Functionality, display and user experience should imitate the intended display and interactivity. UI/UX Designers use prototypes to demonstrate design ideas to stakeholders, users and clients, this assists them with deciding if any adjustments with design or features are necessary before the final release (Pernice, 2016).


## References
- Rouse, M. (2020). What is Interpreter? - Definition from Techopedia. [online] Techopedia.com. Available at: https://www.techopedia.com/definition/7793/interpreter.
- snyk.io. (2020). JavaScript Security | JavaScript Vulnerabilities | Snyk. [online] Available at: https://snyk.io/learn/javascript-security/.
- Pernice, K. (2016). UX Prototypes: Low Fidelity vs. High Fidelity. [online] Nielsen Norman Group. Available at: https://www.nngroup.com/articles/ux-prototype-hi-lo-fidelity/.
- Zwidryn, B. (2023). What does the role of a UI/UX Designer look like in a software house? [online] SolDevelo. Available at: https://soldevelo.com/blog/what-does-the-role-of-a-ui-ux-designer-look-like-in-a-software-house/.
- Technojobs (2019). The Role of a Software Developer | Technojobs UK. [online] Technojobs.co.uk. Available at: https://www.technojobs.co.uk/info/developer-guides/the-role-of-a-software-developer.phtml.
- Project-Management.com (2018). Project Manager Roles and Responsibilities for Software Projects. [online] Project-Management.com. Available at: https://project-management.com/project-manager-roles-responsibilities-software-projects/.
- The University of Edinburgh (2020). Gibbs’ Reflective Cycle. [online] The University of Edinburgh. Available at: https://www.ed.ac.uk/reflection/reflectors-toolkit/reflecting-on-experience/gibbs-reflective-cycle.
- University of California (2017). SMART goals: A how to guide. [online] University of California. Available at: https://www.ucop.edu/local-human-resources/_files/performance-appraisal/How%20to%20write%20SMART%20Goals%20v2.pdf.
- Lonczak, H. (2021). Pessimism vs. Optimism: How Mindset Impacts Wellbeing. positivepsychology. [online] 28 Apr. Available at: https://positivepsychology.com/pessimism-vs-optimism/.
- AIContentfy. (2023). ChatGPT and the Future of Content Creation. [online] Available at: https://aicontentfy.com/en/blog/chatgpt-and-future-of-content-creation#:~:text=ChatGPT%2C%20or%20the%20%22Generative%20Pre [Accessed 23 Jun. 2024].
- Ray, P.P. (2023). ChatGPT: a Comprehensive Review on background, applications, Key challenges, bias, ethics, Limitations and Future Scope. Internet of Things and Cyber-Physical Systems, [online] 3(1), pp.121–154. doi:https://doi.org/10.1016/j.iotcps.2023.04.003.
- Deore, C. (2023). Handling Large Datasets with ChatGPT for Specific Tasks: A Professional’s Guide to Data Mastery. [online] Medium. Available at: https://medium.com/@chetakdeore1994/handling-large-datasets-with-chatgpt-for-specific-tasks-a-professionals-guide-to-data-mastery-1f09e7143651 [Accessed 23 Jun. 2024].
- Litwin, M. (2023). Chat-GPT in Software Development: Real-Life Use Cases. [online] Kyotu Technology. Available at: https://www.kyotutechnology.com/leveraging-chat-gpt-in-software-development/#:~:text=Chat%2DGPT%20can%20be%20utilized [Accessed 23 Jun. 2024].
- Beganovic, A., Jaber, M.A. and Almisreb, A.A. (2023). Methods and Applications of ChatGPT in Software Development: A Literature Review. Southeast Europe Journal of Soft Computing, [online] 12(1), pp.08-12. doi:https://doi.org/10.21533/scjournal.v12i1.251.g219.
- Waseem, M. et al. (2024) ‘CHATGPT as a software development bot: A project-based study’, Proceedings of the 19th International Conference on Evaluation of Novel Approaches to Software Engineering [Preprint]. doi:10.5220/0012631600003687. 
- Rahmaniar, W. (2023) CHATGPT for software development: Opportunities and challenges [Preprint]. doi:10.36227/techrxiv.23993583.v1. 
- Stöffelbauer, A. (2023). How Large Language Models Work. [online] Data Science at Microsoft. Available at: https://medium.com/data-science-at-microsoft/how-large-language-models-work-91c362f5b78f.
- Elkhatat, A.M. (2023). Evaluating the authenticity of ChatGPT responses: a study on text-matching capabilities. International journal for educational integrity, 19(1). doi:https://doi.org/10.1007/s40979-023-00137-0.
- Sedaghat, S. (2024). Plagiarism and Wrong Content as Potential Challenges of Using Chatbots Like ChatGPT in Medical Research. Journal of academic ethics. doi:https://doi.org/10.1007/s10805-024-09533-8.
- Westfall, C. (2023). Educators Battle Plagiarism As 89% Of Students Admit To Using OpenAI’s ChatGPT For Homework. [online] Forbes. Available at: https://www.forbes.com/sites/chriswestfall/2023/01/28/educators-battle-plagiarism-as-89-of-students-admit-to-using-open-ais-chatgpt-for-homework [Accessed 23 Jun. 2024].
- Ray, P.P. (2023). ChatGPT: a Comprehensive Review on background, applications, Key challenges, bias, ethics, Limitations and Future Scope. Internet of Things and Cyber-Physical Systems, [online] 3(1), pp.121–154. doi:https://doi.org/10.1016/j.iotcps.2023.04.003.
- Bhattacharyya, M., Miller, V.M., Bhattacharyya, D. and Miller, L.E. (2023). High Rates of Fabricated and Inaccurate References in ChatGPT-Generated Medical Content. Cureus, [online] 15(5), p.e39238. doi:https://doi.org/10.7759/cureus.39238.
- Guleria, A. et al. (2023) ‘CHATGPT: Ethical concerns and challenges in academics and research’, The Journal of Infection in Developing Countries, 17(09), pp. 1292–1299. doi:10.3855/jidc.18738. 
- Davis, A. (2023). ChatGPT sparks cheating, ethical concerns as students try realistic essay writing technology. ABC News. [online] 25 Jan. Available at: https://www.abc.net.au/news/2023-01-26/chatgpt-sparks-cheating-ethical-concerns-in-schools-universities/101888440.
- Blansit, B.D. (2008). An Introduction to Cascading Style Sheets (CSS). Journal of Electronic Resources in Medical Libraries, [online] 5(4), pp.395–409. doi:https://doi.org/10.1080/15424060802453811.
- Huddleston, R. (2018) ‘HTML basics’, Introduction to HTML and CSS [Preprint]. doi:10.1007/978-1-4842-3979-7_3. 
- Bartlett, J. (2022) ‘Basic javascript syntax’, Programming for Absolute Beginners, pp. 119–132. doi:10.1007/978-1-4842-8751-4_9. 
- Eggleston, L. (2023). A Guide to Low Level Programming for Beginners. [online] Course Report. Available at: https://www.coursereport.com/blog/a-guide-to-low-level-programming-for-beginners.
- GeeksforGeeks. (2023). What is High Level Language? [online] Available at: https://www.geeksforgeeks.org/what-is-high-level-language/.
- Codemotion (2023). Trending Hard Skills and Soft Skills In Software Development. [online] Codemotion Magazine. Available at: https://www.codemotion.com/magazine/it-careers/trending-hard-skills-and-soft-skills-in-software-development/.
- Simplilearn (2020). What is a Product Owner: Key Roles and Responsibilities Explained [2022 Edition]. [online] Simplilearn.com. Available at: https://www.simplilearn.com/what-is-a-product-owner-article.
- Kumar Mohbey, K. and Acharya, M. (2023) ‘Programming with python’, Basics of Python Programming: A Quick Guide for Beginners, pp. 251–259. doi:10.2174/9789815179637123010014. 
- Matuszek, D. (2023) ‘JavaScript’, Quick JavaScript, pp. 7–48. doi:10.1201/9781003359609-2. 
- Singh, J. (2023). How JavaScript Works: An In-Depth Guide. [online] Medium. Available at: https://jeetpalsingh.medium.com/how-javascript-works-an-in-depth-guide-770dd9d65a7d#:~:text=JavaScript%20is%20an%20object%2Doriented [Accessed 23 Jun. 2024].
- OWASP (2020). Cross Site Scripting (XSS) | OWASP. [online] Owasp.org. Available at: https://owasp.org/www-community/attacks/xss/.
- Programiz (2019). Interpreter Vs Compiler : Difference Between Interpreter and Compiler. [online] Programiz.com. Available at: https://www.programiz.com/article/difference-compiler-interpreter.
- Statista. (2023). Most used languages among software developers globally 2023. [online] Available at: https://www.statista.com/statistics/793628/worldwide-developer-survey-most-used-languages.
- Chris, K. (2021). What is HTML – Definition and Meaning of Hypertext Markup Language. [online] freeCodeCamp.org. Available at: https://www.freecodecamp.org/news/what-is-html-definition-and-meaning/.
- Zola, A. and Gillis, A.S. (2017). network packet. [online] SearchNetworking. Available at: https://www.techtarget.com/searchnetworking/definition/packet.
- geeksforgeeks (2020). What is IPv4? [online] GeeksforGeeks. Available at: https://www.geeksforgeeks.org/what-is-ipv4/.
- B, S. (2019). Differences between IPv4 and IPv6 - GeeksforGeeks. [online] GeeksforGeeks. Available at: https://www.geeksforgeeks.org/differences-between-ipv4-and-ipv6/.
- BasuMallick, C. (2022). What Is IPv6 (Internet Protocol Version 6)? Definition, Features, and Uses |. [online] Spiceworks. Available at: https://www.spiceworks.com/tech/networking/articles/what-is-ipv6/.
- Duo, M. (2020). IPv4 vs IPv6 — What’s The Difference Between the Two Protocols? [online] Kinsta. Available at: https://kinsta.com/blog/ipv4-vs-ipv6/.
- Basumallick, C. (2022). TCP vs. UDP: Understanding 10 Key Differences. [online] Spiceworks. Available at: https://www.spiceworks.com/tech/networking/articles/tcp-vs-udp/.
- Lutkevich, B. and Burke, J. (2021). What is DNS? How Domain Name System works. [online] SearchNetworking. Available at: https://www.techtarget.com/searchnetworking/definition/domain-name-system.
- Molenaar, R. (2013). Introduction to Routers and Routing. [online] NetworkLessons.com. Available at: https://networklessons.com/cisco/ccnp-encor-350-401/introduction-to-routers-and-routing.
- Felix, F.C. (2022). How Web Pages Get Rendered on the Browser – Different Methods Explained. [online] freeCodeCamp.org. Available at: https://www.freecodecamp.org/news/web-page-rendering-on-the-browser-different-methods/.
- Humphrey, M. (2024). What is a Page Request? [online] DigiBubble. Available at: https://www.digibubble.co.uk/2024/01/what-is-a-page-request/ [Accessed 23 Jun. 2024].
- Felix, F.C. (2022). How Web Pages Get Rendered on the Browser – Different Methods Explained. [online] freeCodeCamp.org. Available at: https://www.freecodecamp.org/news/web-page-rendering-on-the-browser-different-methods/.
- GeeksforGeeks. (2021). Browser Developer Tools. [online] Available at: https://www.geeksforgeeks.org/browser-developer-tools/.