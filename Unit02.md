**Unit 2: Infrastructure** <span id="2"></span> 
*In this unit, we will look at the mechanics that enable web-based
mobile applications to run.  We will first start with basic networking
capabilities, such as how a device connects to the Internet, and then
discuss routing and proxies.  We will also learn how a browser on a
mobile device accesses the network and how a server receiving a request
routes it to the appropriate logic in order to process that request.  *

**Unit 2 Time Advisory**  
This unit will take approximately 13 hours and 20 minutes to complete.  
  
 <span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 16px; line-height: 24px; text-align: left; -webkit-text-size-adjust: none; ">☐
   </span>Subunit 2.1: 2.25 hours  
  
 <span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 16px; line-height: 24px; text-align: left; -webkit-text-size-adjust: none; ">☐
   </span>Subunit 2.2: 4.3 hours  
  
 <span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 16px; line-height: 24px; text-align: left; -webkit-text-size-adjust: none; ">☐
   </span>Subunit 2.3: 4 hours  
  
 <span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 16px; line-height: 24px; text-align: left; -webkit-text-size-adjust: none; ">☐
   </span>Subunit 2.4: 1.5 hours  
  
 <span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 16px; line-height: 24px; text-align: left; -webkit-text-size-adjust: none; ">☐
   </span>Subunit 2.5: 30 minutes  
  
 <span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 16px; line-height: 24px; text-align: left; -webkit-text-size-adjust: none; ">☐
   </span>Subunit 2.6: 45 minutes

**Unit2 Learning Outcomes**  
Upon successful completion of this unit, the student will be able to:  
-   Describe mobile and cell phone technologies.
-   Compare and contrast 3-G and 4-G.
-   Define and describe an IP address.
-   Discuss gateways and subnet masks.
-   Explain transport including HTTP and routing.
-   Explain how proxies and reverse proxies work.

**2.1 Mobile and Cell Phone Technologies** <span id="2.1"></span> 
-   **Reading: Erik Wilde’s Mobile Application Design and Development:
    “Mobile Web Mechanics”**
    Link: Erik Wilde’s Mobile Application Design and Development:
    [“Mobile Web Mechanics”](http://dret.net/lectures/mobapp-spring10/)
    (PowerPoint Slides)  
        
     Instructions: Please click on the link under slides 2010-01-27,
    labeled “Mechanics.”  Please note that this reading applies to all
    of unit 2.  This resource should take 15 minutes to complete.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Lecture: YouTube: Indian Institute of Technology: Professor S
    Ghosh’s “Lecture 22: Cellular Networks”**
    Link: YouTube: Indian Institute of Technology: Professor S Ghosh’s
    [“Lecture 22: Cellular
    Networks”](http://www.youtube.com/watch?v=2d26QaZVSo4) (YouTube)  
        
     Instructions: Please watch the entire video (59:51).  This resource
    should take 60 minutes to complete.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**2.1.1 CDMA** <span id="2.1.1"></span> 
-   **Reading: PCMagazine Encyclodedia’s “CDMA”**
    Link: PCMagazine Encyclodedia’s
    [“CDMA](http://www.pcmag.com/encyclopedia_term/0,2542,t=CDMA&i=39462,00.asp)”
    (HTML)  
        
     Instructions: Please read the entire article, which provides an
    overview of CDMA.  This resource should take 20 minutes to
    complete.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Reading: Michael Hendry’s “Introduction to CDMA”**
    Link: Michael Hendry’s [“Introduction to
    CDMA](http://www.bee.net/mhendry/vrml/library/cdma/cdma.htm)”
    (HTML)  
        
     Instructions: Please read the entire article.  This is an in-depth
    article which covers much of the engineering behind CDMA.  This
    resource should take 45 minutes to complete.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**2.1.2 GSM** <span id="2.1.2"></span> 
-   **Reading: PCMagazine Encyclodedia’s “GSM”**
    Link: PCMagazine Encyclodedia’s
    [“GSM”](http://www.pcmag.com/encyclopedia_term/0,2542,t=GSM&i=43985,00.asp)
    (HTML)  
        
     Instructions: Please read the entire article.  This article is more
    of an overview of GSM.  This resource should take 15 minutes to
    complete.  
                              
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**2.1.3 3-G** <span id="2.1.3"></span> 
-   **Reading: Wirelessinternet.org’s “3G Network and Services”**
    Link: Wirelessinternet.org’s [“3G Network and
    Services”](http://www.wirelessinternet.org/3G-network.php) (HTML)  
        
     Instructions: Please read the entire page.  This resource should
    take 10 minutes to complete.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**2.1.4 4-G** <span id="2.1.4"></span> 
-   **Reading: Wirelessinternet.org’s“What’s this about 4G?”**
    Link: Wirelessinternet.org’s [“What’s this about
    4G?](http://www.wirelessinternet.org/4G-network.php)” (HTML)  
        
     Instructions: Please read the entire page.  Think about how 3G is
    different from 4G.  This resource should take 15 minutes to
    complete.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**2.2 Internet Terms** <span id="2.2"></span> 
-   **Web Media: YouTube: Securitycatalyst.com’s “How the Internet Works
    in 5 Minutes”**
    Link: YouTube: Securitycatalyst.com’s [“How the Internet Works in 5
    Minutes”](http://www.youtube.com/watch?v=7_LPdttKXPc&feature=related)
    (YouTube)  
        
     Instructions: Please watch the entire video (4:48).  This is a good
    general overview of the Internet.  This resource should take 5
    minutes to complete.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**2.2.1 IP Address** <span id="2.2.1"></span> 
-   **Reading: WhatIsMyIPAddress.com’s “What is an IP Address?”**
    Link: WhatIsMyIPAddress.com’s [“What is an IP
    Address?”](http://whatismyipaddress.com/ip-address) (HTML)  
        
     Instructions: Please read the entire article.  This resource should
    take 10 minutes to complete.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Reading: Inria Research Centre: Professor Vincenzo Mancuso’s
    “Internet IP”**
    Link: Inria Research Centre: Professor Vincenzo Mancuso’s [“Internet
    IP](http://www-sop.inria.fr/members/Vincenzo.Mancuso/ReteInternet.html)”
    (PDF)  
        
     Instructions: Please click on the link for IP and read all slides. 
    This resource should take 1 hour to complete.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Lecture: YouTube: Indian Institute of Technology: Professor S.
    Gosh’s “IP Version 6 and Mobile IP”**
    Link: YouTube: Indian Institute of Technology: Professor S. Gosh’s
    ”[IP Version 6 and Mobile
    IP](http://www.youtube.com/watch?v=0QLRULNfbFg)” (YouTube)  
        
     Instructions: Please watch the entire video.  This resource should
    take 1 hour to complete..  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Web Media: YouTube's "What is an IP Address?"**

    Link:  [YouTube's "What is an IP
    Address?" ](http://www.youtube.com/watch?v=RHRXFTQMQgo)

     

    Instructions: Please watch the entire video (2:13).  You can also
    find the IP address of a computer by going to WhatIsMyIPAddress.com.
    This resource should take 2 minutes to complete.  
       
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**2.2.2 Subnet Mask** <span id="2.2.2"></span> 
-   **Web Media: YouTube: Astorino Networks’ “IP Address and Subnet Mask
    Basics”**
    Link: YouTube: Astorino Networks’ “[IP Address and Subnet Mask
    Basics](http://www.youtube.com/watch?v=w0RM7PY34Bg)” (YouTube)  
        
     Instructions: Please watch the entire video.  This will also serve
    as a good review of IP Addressing.  This resource should take 13.5
    minutes to complete.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Reading: Infria.fr: Professor Vincenzo Mancuso’s “Subnetting”**
    Link: Infria.fr: Professor Vincenzo Mancuso’s
    “[Subnetting](http://www-sop.inria.fr/members/Vincenzo.Mancuso/ReteInternet.html)”
    (PDF)  
        
     Instructions: Please click on the link for Subnetting.  Read all
    slides.  This resource should take 1 hour to complete.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**2.2.3 Gateway** <span id="2.2.3"></span> 
-   **Reading: WiFiNotes.com’s “What are Gateways: How Computer Gateway
    Works”**
    Link: WiFiNotes.com’s [“What are Gateways: How Computer Gateway
    Works](http://www.wifinotes.com/computer-networks/how-gateways-works.html)”
    (HTML)  
        
     Instructions: Please read the entire article.  This resource should
    take 15 minutes to complete.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**2.2.4 DNS** <span id="2.2.4"></span> 
-   **Reading: Dyn.com’s “What is DNS: Part 1—The Explanation”**
    Link: Dyn.com’s [“What is DNS: Part 1—The
    Explanation](http://www.youtube.com/watch?v=yl6h7Qdkc1o)”
    (YouTube)  
        
     Instructions: Please watch the entire video. This resource should
    take 4 minutes to complete.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Reading: WiFiNotes.com’s “How DNS Server Works: Role of DNS
    Servers”**
    Link: WiFiNotes.com’s [“How DNS Server Works: Role of DNS
    Servers”](http://www.wifinotes.com/computer-networks/how-dns-server-works.html)
    (HTML)  
        
     Instructions: Please read the entire article.  This resource should
    take 15 minutes to complete.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**2.2.5 Static vs. Dynamic** <span id="2.2.5"></span> 
-   **Reading: Whatismyipaddress.com’s “Dynamic IP vs. Static IP”**
    Link: Whatismyipaddress.com’s [“Dynamic IP vs. Static
    IP](http://whatismyipaddress.com/dynamic-static)” (HTML)  
        
     Instructions: Please read the entire page.  This resource should
    take 10 minutes to complete.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**2.3 Transport** <span id="2.3"></span> 
**2.3.1 HTTP** <span id="2.3.1"></span> 
-   **Reading: Infria.fr: Professor Vincenzo Mancuso’s “Internet HTTP:
    Parts I and II”**
    Link: Infria.fr: Professor Vincenzo Mancuso’s [“Internet HTTP: Parts
    I and
    II](http://www-sop.inria.fr/members/Vincenzo.Mancuso/ReteInternet.html)”
    (PDF)  
        
     Instructions: Please click on the links for HTTP (Part I) and HTTP
    (Part II).  Read all slides.  This resource should take 1 hour to
    complete.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Lecture: YouTube: Indian Institute of Technology: Professor S.
    Ghosh’s “Lecture 40—HTTP”**
    Link: YouTube: Indian Institute of Technology: Professor S. Ghosh’s
    [“Lecture 40—HTTP”](http://www.youtube.com/watch?v=yYy3oAapQHM)
    (YouTube)  
        
     Instructions: Please watch the entire video.  This resource should
    take 1 hour to complete.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**2.3.2 Routing** <span id="2.3.2"></span> 
-   **Reading: Infria.fr: Professor Vincenzo Mancuso’s “Routing”**
    Link: Infria.fr: Professor Vincenzo
    Mancuso’s [“Routing”](http://www-sop.inria.fr/members/Vincenzo.Mancuso/ReteInternet.html)
    (PDF)  
        
     Instructions: Please click on the link for Routing.  Read all
    slides.  This resource should take 1 hour to complete.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Lecture: YouTube: Indian Institute of Technology: Professor S.
    Ghosh’s “Lecture 26—Introduction to Routing”**
    Link: YouTube: Indian Institute of Technology: Professor S. Ghosh’s 
    [“Lecture 26—Introduction to
    Routing”](http://www.youtube.com/watch?v=AmlOSGYkKXc&feature=channel)
    (YouTube)  
        
     Instructions: Please watch the entire video.  This resource should
    take 1 hour to complete.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**2.4 Secure Connections** <span id="2.4"></span> 
-   **Lecture: YouTube: Indian Institute of Technology: Professor S.
    Ghosh’s: “Lecture 38—Security”**
    Link: YouTube: Indian Institute of Technology: Professor S. Ghosh’s:
    [“Lecture
    38—Security”](http://www.youtube.com/watch?v=3JblSrRT8XE&feature=channel)
    (YouTube)  
        
     Instructions: Please watch the entire video.  This resource should
    take 1 hour to complete.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Reading: Purdue University: Professor Cristina Nita-Rotaru’s CS555
    Lectures: “Lecture 22: SSL”**
    Link: Purdue University: Professor Cristina Nita-Rotaru’s CS555
    Lectures: [“Lecture 22:
    SSL”](http://homes.cerias.purdue.edu/~crisn/courses/cs555/) (PDF)  
        
     Instructions: Please scroll down and click on the link for lecture
    22.  Read all slides.  
      
     This resource should take 30 minutes to complete.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**2.5 Proxies** <span id="2.5"></span> 
-   **Reading: New York University: Professor Arthur Goldberg’s
    “Internet and Intranet Protocols and Applications: Lecture 11a: Web
    Caching Proxy Servers and Cookies”**
    Link: New York University: Professor Arthur Goldberg’s [“Internet
    and Intranet Protocols and Applications: Lecture 11a: Web Caching
    Proxy Servers and
    Cookies](http://www.cs.nyu.edu/artg/internet/Spring2003/syllabus.html)”
    (PDF)  
        
     Instructions: Please scroll down to Week 8 March 12 and click on
    the link for “Web Caching Proxy Servers and Cookies.”  This resource
    should take 30 minutes to complete.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**2.6 Reverse Proxies** <span id="2.6"></span> 
-   **Reading: SANS Institute InfoSec Reading Room: Art Stricek’s “A
    Reverse Proxy is a Proxy by any Other Name”**
    Link: SANS Institute InfoSec Reading Room: Art Stricek’s [“A Reverse
    Proxy is a Proxy by any Other
    Name](http://www.sans.org/reading_room/whitepapers/webservers/)”
    (PDF)  
        
     Instructions: Please scroll down to the link for “A Reverse Proxy
    is a Proxy by any other Name.” This resource should take 45 minutes
    to complete.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.


