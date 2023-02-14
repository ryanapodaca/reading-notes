# WWW Structure

The web is like the mailing infrastructure.

Consider,

Mail(information) is transferred along determinate paths by a protocol termed 'Hypertext Transfer Protocol" (HTTP) to determinate locations (IP addresses.)

The mailman (server) and receiver (client) are the basic building blocks of the web infrastructure.

One major difference from the analogy is the manner in which information is parsed. Physical mail comes to clients as a discrete whole.  Virtual information is received in small packets, because this method helps ensure efficiency of data dissemination at scale.  

First the client sends a signal to servers that they would like access to an address. After approval, the information is normally parsed as follows:

1. HTML information is parsed first, which ensures that the critical information is not lost if CSS or JS fail.

2. Once a link for CSS is encountered, a request is sent for CSS information.  

3. JS follows similar protocol as CSS, normally directly after CSS retrieval. 

## Image Protocol

Best practice for images is to use images from copy-write free websites.

**String vs. Number in JS**

*String*

let x = '5';

*Number*

let x = 5;

Quotes are the determinate factor.

**Variables**

A variable is a designated holder of data which can either be constant or changed on condition of user input or functional information processes.  

Variables are the condition which allows for the possibility of input sensitivity. 

**HTML Attribute**

Attributes are extra data about the element that aren't immediately available to the client.

HTML Elements normally consist of tags which encapsulate content. Attributes can be modified from within the opening tags.  

### Article vs. Section Elements

An article is a piece of information meant to  be disseminated as a whole, such as a news story.

A section is more general, because a section is semantically referring to the structure of thr web page.  Technically, an article can be contextualized inside a section, but it  is semantically strange to put a section element inside an article element, unless the article was sufficiently long.  

These matters are irrelevant to the computer in many instances.  Element decisions are normally made to coordinate design decisions across HTML CSS and JS.

There exists a standard set of elements which are virtually used in most sites.  There is a title section and head section which is used for meta-data, which is followed by a body element. The body element is where the content is placed.
