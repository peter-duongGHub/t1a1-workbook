# PeterDuong_T1A1 Assessment - Workbook
## Q1 

### What is Web Development Markup Language?  
Web Development Markup Language is one of many languages in web development used to structurally present text, images and/or links in a web document, it enables components such as text to be rendered in a specific way. 

### How does Web Development Markup Language work?
Web Development Markup Language uses either tags or code around or between text, providing instructions to a computer on how certain elements should be displayed & structured on a web document. Text, tags and code may be written in a simple text editor such as notepad, microsoft word, visual studio code to name a few, and converted into a web development markup language format before rendering on a web page. Each markup language has certain rules to distinguish between text and the tags or codes necessary to implement web document structuring, this is called syntax.

### Example Web Development Markup Language
#### HTML
```
<h1>This is a title</h1>
```
HTML5 also referred to as HTML is the newest version of HTML. This language works by inserting opening and closing tags, which helps structure the content displayed on the web browser. Here's an example: The above code represents an opening and closing tag for a heading, specifically h1. h1 is the element name and the text between the opening and closing tags are the text that will be rendered. Opening tags begin with angle brackets specifying the beginning of content, represented by <>. Closing tags are similar, angle brackets with a forward slash inside the angle brackets - </> this represents the end of the element.

#### XML
```
<note>
<heading>Note to Self</heading>
<body>Lorem Ipsum</body>
</note>
```
XML is another example of a markup language, its function differs from HTML5. XML (eXtensible markup language) similarly to HTML5 uses tags. XML does not display content on a web document, software must be used to help store and transfer or display it. Tags and document display in XML need to be defined prior to use. The above code represents a note with a heading and body. These elements must be defined by the author.

### Components/Concepts of Markup Languages
#### Syntax
Syntax within markup languages involves the rules associated to the use of the markup language. They are pre-determined instructions that must be implemented when using attributes, elements & tags. Without proper syntax, error codes may appear and content may not be rendered.  
A few examples of markup language syntax:  
- **Angle brackets**  
```<>``` : Opening Tag  
```<\>``` : Closing Tag
- **Attributes**  
```alt=```: Alt Attribute (may be used if image does not render, screen reader purposes)  
```placeholder=``` Placeholder Attribute (sets placeholder text)  
```style=``` : Style attribute (not recommended, but is an attribute for in-line styling)  
- **Elements**(Represented by opening tag, closing tag & content)    
```<h1>Header</h1>```: this would represent the h1 element and would represent a primary header tag (opening and closing)  
```<p>Lorem</p>```: this would represent the p tag(opening and closing), associated with paragraphs   
```<img>```: this would represent the img tag(self-closing), associated with images 

#### Hypertext
A common and significant component within markup languages such as HTML is hypertext. Text components that may connect to other documents or chunks of text are referred to as hypertext. Hypertext helps with navigating pages of text/document much simpler, easier and accurate. Without hypertext, utilising search engines to navigate pages would not be possible. 

#### Tags
Tags are an important concept within markup languages. Without tags no content would be exhibited or stored(XML). In HTML, tags are necessary to represent the documents structure on web pages and help support search engines to categorise content relevancy. An example:  
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
Semantic tags are used in HTML to provide meaning for the content displayed on the web page. It helps divide sections of content into relevant containers that support optimal SEO purposes. Example: 
```
<nav>Menu</nav>
```
The nav element helps readers and developers by indicating this section of content involves navigation. 

#### Static Language
Markup languages are static in nature. They do not provide any 


### Where is Web Development Markup Language used?
- Google Chrome
- Mozilla Firefox
- Microsoft Edge
- Youtube
- Wikipedia

### Benefits of Web Development Markup Language
Web development markup languages allow authors to structure webpage content in a standardised format. The benefits of Markup Languages include:
- **Accessibility and Readability**  
With every browser supporting markup languages such as HTML language, this makes it readily accessible to both viewers and businesses in terms of application and rendering. In terms of readability, An example: for HTML, attributes such as ```alt``` helps with readability for images that fail to render or for screen readers, making HTML5 a viable option in many cases of displaying web content and for greater user experience.

- **Optimising SEO**  
Search engines such as google will rank websites based on their relevance, technical geography and popularity. Components in HTML such as semantic tags help group and contain specific content for search engines to better understand and navigate the content meaning and structure, ranking higher for relevant content. HTML tags play a key role in grouping specific sections for search engine optimisation. An example would be:
```
<main>
```
The main tag is the primary portion of the document. This section would contain content unique to the web page.
- **Ease of Use & Extensibility**  
HTML is a simple language in comparison to other languages, making it much easier to learn, understand and apply. As HTML works across multiple browsers and devices, structuring and rendering content of web pages becomes much simpler and smoother. HTML is also extensible, meaning it has a great affinity with stylesheet languages such as CSS and programming languages like Javscript. 

### Cons of Web Development Markup Language
- **Static Language**  
Markup languages such as html are static, this means they are limited in what they are able to do. In simple terms this means the components of the web page are not dynamic, they cannot change with user input or other factors.

- **Security**
HTML has its drawbacks, HTML injections are an example. HTML injections are a type of attack focused on manipulating the HTML components resulting in a disfigured structure or manipulated components. Certain components such as tags or attributes or hyperlinks may be replaced with malicious code. Certain preventative measures such as security audits, validating user input and sanitizing harmful content from user inputs may remove or mitigate the risks associated with the use of HTML.

- **Limited Designs**  
In regards to its static nature, this makes HTML language limited in what it may present to the viewer. Only texts, links, buttons, tables etc (to name a few), may be used as page content. 3D objects, animations, and interactivity cannot be created with markup languages. This is where other languages like CSS & Javascript support HTML.

## Q2 
What are packets?/ip/routers/domains and dns
### What are Packets
Packets also known as datagrams are fixed data units that are transmitted from one computer to another over an interconnected network. Packets are components broken down into fixed sizes, (such as images or text) when all packets are received at the destination IP address, packets are reassembled into the whole data component. Packets travel through layer 3 devices. The network protocol that is used will determine the components of each packet.  

### How do Packets work?
A TCP packet such as ACK packet confirms receiving packets and relays a signal back to the sender for continued packet transmission. 


### Why are they important
Packets are important as they help with the efficiency of transferring data. Without packets data would be transferred in large bits, if more than two computers are involved the other computers wont be able to access the data simultaneously.

### Components of Packets
Each packet is made up of:
**Header**  
The header is composed of:
- Version Number
- Header Length
- Differentiated services
- Datagram/Packet length
- Option field
#### Version Number
Helps Datagram be processed by internet protocol software in machine. 

#### Header Length
Each word is 4 bytes in length in IPv4.

#### Option Field
The option field allows Ipv4 header length to range from 20 - 60 bytes. The value in option field also determines the header length of the IPv4 datagram/packet.

#### Differentiated Services
Made up of:
- DSCP 
- ECN explicit congestion notification
Differentiated services of the datagram is composed of 2^6 bit combinations classify IP packets to facilitate the prioritising of different ip packets, giving precendence for those that are more important.

- Data 
- Footer
#### Header
The header is made up of the ip address of both the destination and source address which helps direct the packet to the correct computer in an efficient manner. 

#### IPv4 IPv6
**Ipv4** addresses are composed of 32 bit length ip addresses. They consist of 4 numbers seperated by a dot, each number may be a value between 0 and 255. Machines will convert this number into binary for rendering and understandability. The total number of devices 2^32 devices can be given an IPv4 Ip address. 

#### Complications of IPv4
With the limited number of devices IPv4 can allocate an ip address to, the move to IPv6 is happening. 

#### IPv6
**IPv6** addresses are composed of 128 bit length ip addresse. They consist of 
IPv6 will allocated 2^128 Ip addresses for each device. 


#### IP addresses
- Static IP Address
- Dynamic Ip Address

#### IPv4 Addresses
- Made up of Network Id and Host Id
- Made up of 32 bits (Ipv4)
- How IP address is divided into network id and host id is depending on the class the ip address is
- Loopback address 127
- Ipv4 classes:
A, B, C, D, E

#### Class A
- Network Id portion of Ip address takes up 8 bits. Host Id takes up 2^24 

#### Static Ip Address
Are used for DNS servers and are permanent addresses.


#### Dynamic Ip Address
Changes every time you access the internet. Such as your ISP providing internet to your computer. They provide an ip address within a certain range.



while Ipv6 addresses are composed of 128 bit

#### IPv4 Datagrams/Packets Format



#### Data
The data is made up of whichever data type is being transmitted. E.g Image, Text etc.

#### Footer
The footer/trailer role is to detect any errors with the packet also called EDC (error detection code). 


How do they work?

Why are they important?

Examples

## Q3 
What are TCP?/ HTTPS and HTTP ? Web Browsers
### What is TCP?
TCP stands for transmission control protocol. TCP helps in ensuring all packets are delivered to destination ip address. 

How do they work?

Why are they important?

Examples
## Q4 
What are interpreters/compilers
### What are interpreters/compilers?
Interpreters and compilers are used to convert high level language to machine language for interpretation and rendering.


How do they work?

WHy are they important?

WHat are the differences?

Examples

## Q5 
- What are programming languages? (two)
### What are programming languages? 
- Javascript
- Python
#### What is Javascript?


- HOw do they work?

- Benefits and drawbacks?

- WHy important

- Examples?


## Q6 
- Professional email response clients needs for website
- appropriate technologies or tools needed to build the website


## Q7 
- How would I do different for scenario of portfolio project again using appropraite reflective cycle or technique

## Q8 
Action plan identifying relevant networking opportunities for you to participate in or attend and add infomration about what you expect to gain or grow through each item in the action plan


## Q9 ot 
- explain use of language learning model tech such as chatg

## Q10 
### Language Learning Model Technology 
#### What is Language learning model technology?
Language learning model technology also known as large language models work by having artificial intelligence understand and transcribe human language from a large data set into generated content using deep learning. 



## Q11 
### Hard Skills
#### What are Hard Skills
Hard skills relate to technical abilities that may be taught and measured through progamming. They may be further learnt and developed over time. 

#### Examples of Hard Skills
- **Stylesheet Language**  
This refers to language such as CSS (Cascading stylesheet), involving the styling of webpages. Cascading stylesheet may be learnt and used in conjunction with HTML to help edit HTML elements. CSS is paramount to enabling a more entertaining and user-friendly experience for each visitor.

- **Markup Language**  
Markup Language refers to languages such as HTML, XHTML, LateX etc. These languages are crucial in web development and help design a websites structure, layout and presentation. 

- **Programming Languages**     
Programming Language refers to languages such as Python and Javascript. They help translate human language into binary,  helping computers understand and execute the instructions we provide.    
**There are two types of Programming Languages:**    
1. **Low Level Language**  
Low level language such as Assembly language are more easily understood by machines and offers much more control and efficiency in applications.   
2. **High Level Language**   
High level language introduces a more understandable way for people to transcribe our language into machine language for machines to better understand. 
 
- **Database Management**  
Database management involves the creating, improving and application of databases to help store organised and secure data. 
- **Debugging and Testing**
- **Frameworks, Libraries**

#### Why are Hard Skills Important?

#### How to Gain/Improve Hard Skills


### Soft Skills
#### What are Soft Skills
Soft skills involve an individuals personal abilities that are developed over time which are beneficial to all aspects of a successful software company ensuring fpr smoother processing, systems and outcomes.

#### Examples of Soft Skills
- Communication
- Leadership
- Managing Time
- Solving Problems
- Adaptability 
- Flexibility
- Teamwork
- Attention to Detail

#### Why are Soft Skills Important?




## Q12 
- Engineering project manager
- chief digital officer
- software architect
- product owner
- technical lead
- quality assurance engineer
- vice president of marketing
- user experience designer
- user interface designer
- scrum master


## References:
- https://theonetechnologies.com/blog/post/different-roles-in-software-company
- Packets - https://www.youtube.com/watch?v=j9A8Amdfyj0
- Ipv4 - https://www.youtube.com/watch?v=3Y70y6dM7Cs
- IP address, IPv4 and IPv6
- LLM - https://www.techtarget.com/whatis/definition/large-language-model-LLM
- Soft & hard https://www.ironhack.com/gb/blog/soft-skills-vs-hard-skills-what-do-tech-recruiters-want
- Programming language https://www.codecademy.com/resources/blog/programming-languages/
- Low level language - https://medium.com/@mohinisaxena/low-level-programming-language-examples-9658f578f468