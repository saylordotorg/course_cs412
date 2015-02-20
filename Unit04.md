---
layout: default
title: "CS412: Mobile Applications Development"
course_description: "A detailed study of trends in the development of applications for mobile devices, focusing on the unique design and deployment issues that must be taken into consideration when developing applications for mobile devices."
next: ../Unit05
previous: ../Unit03
---
**Unit 4: JQuery and Structured Data** <span id="4"></span> 
*In this unit, we will take a brief look at JQuery, a mechanism for
direct access to the document object model within a script.  Since
mobile applications often need to interact with a service, we will also
look at how data between the service and the mobile application is
exchanged using either Extensible Markup Language (XML) or JavaScript
Object Notation (JSON).  We will compare and contrast both formats.*

**Unit 4 Time Advisory**  
This unit will take approximately 11 hours and 20 minutes to complete.  
  
 <span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 16px; line-height: 24px; text-align: left; -webkit-text-size-adjust: none; ">☐
   </span>Subunit 4.1: 6 hours 20 minutes
<span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 16px; line-height: 24px; text-align: left; -webkit-text-size-adjust: none; ">☐
   </span>Introductory Materials: 3 hours 20 minutes  
  
 <span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 16px; line-height: 24px; text-align: left; -webkit-text-size-adjust: none; ">☐
   </span>Subunit 4.1.1: 1 hour 30 minutes  
  
 <span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 16px; line-height: 24px; text-align: left; -webkit-text-size-adjust: none; ">☐
   </span>Subunit 4.1.2: 45 minutes  
  
 <span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 16px; line-height: 24px; text-align: left; -webkit-text-size-adjust: none; ">☐
   </span>Subunit 4.1.4: 45 minutes

<span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 16px; line-height: 24px; text-align: left; -webkit-text-size-adjust: none; ">☐
   </span>Subunit 4.2: 40 minutes  
  
 <span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 16px; line-height: 24px; text-align: left; -webkit-text-size-adjust: none; ">☐
   </span>Subunit 4.3: 2 hours 30 minutes  
  
 <span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 16px; line-height: 24px; text-align: left; -webkit-text-size-adjust: none; ">☐
   </span>Subunit 4.4: 1 hour  
  
 <span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 16px; line-height: 24px; text-align: left; -webkit-text-size-adjust: none; ">☐
   </span>Subunit 4.5: 50 minutes

**Unit4 Learning Outcomes**  
Upon successful completion of this unit, the student will be able to:  
-   Explain basic jQuery syntax.
-   Write jQuery code using event listeners.
-   Discuss how to integrate JavaScript with XML.
-   Explain how XML is used.
-   Describe JSON and its uses.

**4.1 JQuery** <span id="4.1"></span> 
-   **Reading: Erik Wilde’s “Mobile Application Design and Development:
    Ryan Greenberg’s jQuery”**
    Link: Erik Wilde’s [“Mobile Application Design and Development: Ryan
    Greenberg’sjQuery”](http://dret.net/lectures/mobapp-spring10/)
    (HTML)  
        
     Instructions: Click on the link under slides 2010–02–05, labeled
    jQuery.  This resource will take 20 minutes to complete.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Reading: W3Schools.com’s’“jQuery Tutorial”**
    Link: W3Schools.com’s [“jQuery
    Tutorial”](http://www.w3schools.com/jquery/default.asp) (HTML)  
        
     Instructions: Please complete the entire tutorial, including the
    examples. Note that this reading will cover the material you need to
    know for subunits 4.1.1 – 4.1.4.  This resource will take 3 hours to
    complete.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.  

**4.1.1 Overview** <span id="4.1.1"></span> 
-   **Reading: JQfundamentals.com: Rebecca Murphey’s “jQuery
    Fundamentals: Chapter 3: jQuery Basics”**
    Link: JQfundamentals.com: Rebecca Murphey’s [“jQuery Fundamentals:
    Chapter 3: jQuery
    Basics](http://jqfundamentals.com/book/index.html#chapter-3)”
    (HTML)  
        
     Instructions: Please read the entire chapter. This resource should
    take 45 minutes to complete.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Reading: JQfundamentals.com: Rebecca Murphey’s “jQuery
    Fundamentals: Chapter 4: jQuery Core”**
    Link: JQfundamentals.com: Rebecca Murphey’s [“jQuery Fundamentals
    Chapter 4: jQuery
    Core](http://jqfundamentals.com/book/index.html#chapter-4)” (HTML)  
        
     Instructions: Please read the entire chapter. This resource should
    take 45 minutes to complete.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**4.1.2 Events in JQuery** <span id="4.1.2"></span> 
-   **Reading: JQfundamentals.com: Rebecca Murphey’s “jQuery
    Fundamentals: Chapter 5: Events”**
    Link: JQfundamentals.com: Rebecca Murphey’s [“jQuery Fundamentals:
    Chapter 5:
    Events](http://jqfundamentals.com/book/index.html#chapter-5)”
    (HTML)  
        
     Instructions: Please read the entire chapter.  Note that this
    reading will cover the material you need to know for sub-sub units
    4.1.2 and 4.1.3. This resource should take 45 minutes to complete.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**4.1.3 Event Listeners** <span id="4.1.3"></span> 
Note: This topic is covered by the resources underneath subunit 4.1.

**4.1.4 AJAX with Jquery** <span id="4.1.4"></span> 
-   **Reading: JQfundamentals.com: Rebecca Murphey’s “jQuery
    Fundamentals: Chapter 7: Ajax”**
    Link: JQfundamentals.com: Rebecca Murphey’s [“jQuery Fundamentals:
    Chapter 7:
    Ajax](http://jqfundamentals.com/book/index.html#chapter-7)” (HTML)  
        
     Instructions: Please read the entire chapter.  This resource should
    take 45 minutes to complete.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**4.2 JavaScript and XML** <span id="4.2"></span> 
-   **Reading: Erik Wilde’s “Mobile Application Design and Development:
    Structured Data”**
    Link: Erik Wilde’s [“Mobile Application Design and Development:
    Structured Data”](http://dret.net/lectures/mobapp-spring10/)
    (HTML)  
        
     Instructions: Click on the link under slides 2010–02–08, labeled
    Structured Data.  Note that this reading will cover the material you
    need to know for subunits 4.2–4.5.  This resource should take 40
    minutes to complete.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**4.3 XML** <span id="4.3"></span> 
-   **Reading: XML.com’s “A Technical Introduction to XML”**
    Link: XML.com’s [“A Technical Introduction to
    XML”](http://www.xml.com/pub/a/98/10/guide0.html) (HTML)  
        
     Instructions: Please read all six pages.  Note that this reading
    will cover the material you need to know for subunits 4.3.1 – 4.3.2.
    This resource will take 1 hour to complete.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Reading: W3Schools.com’s “XML Tutorial”**
    Link: W3Schools.com’s [“XML
    Tutorial”](http://www.w3schools.com/xml/default.asp) (HTML)  
        
     Instructions: Please complete the entire tutorial. This resource
    will take 1.5 hours to complete.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**4.3.1 Data vs. Content** <span id="4.3.1"></span> 
Note: This topic is covered by the resources underneath subunit 4.3.

**4.3.2 Structure** <span id="4.3.2"></span> 
**4.3.2.1 Elements** <span id="4.3.2.1"></span> 
Note: This topic is covered by the resources underneath subunit 4.3.

**4.3.2.2 Tags** <span id="4.3.2.2"></span> 
Note: This topic is covered by the resources underneath subunit 4.3.

**4.3.2.3 Attributes** <span id="4.3.2.3"></span> 
Note: This topic is covered by the resources underneath subunit 4.3.

**4.4 JavaScript Object Notation (JSON)** <span id="4.4"></span> 
**4.4.1 Description** <span id="4.4.1"></span> 
-   **Reading: JSON.org’s “Introducing JSON”**
    Link: JSON.org’s [“Introducing JSON](http://www.json.org/)” (HTML)  
        
     Instructions: Please read the entire page. This resource should
    take 30 minutes to complete.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Reading: W3Schools.com’s “JSON Tutorial”**
    Link: W3Schools.com’s [“JSON
    Tutorial”](http://www.w3schools.com/json/default.asp) (HTML)  
        
     Instructions: Please complete the entire tutorial. This resource
    will take 30 minutes to complete.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**4.5 Examples of XML and JSON** <span id="4.5"></span> 
-   **Reading: JSON.org’s “JSON Example”**
    Link: JSON.org’s [“JSON Example](http://json.org/example.html)”
    (HTML)  
        
     Instructions: Please read the entire page. This resource should
    take 20 minutes to complete.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Assessment: W3Schools.com’s “jQuery Quiz Test”**
    Link: W3Schools.com’s [“jQuery Quiz
    Test”](http://www.w3schools.com/jquery/jquery_quiz.asp) (HTML)  
        
     Instructions: Please complete the entire tutorial to test your
    knowledge of jQuery.  Answers are found at the end of the quiz. This
    resource should take 30 minutes to complete.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.


