# Reading Requirement 4
## Using Javascript to  Grab Data
Reading material 2 consisted of, **Fetching data from a server**, as the title states. I was shown another very common task in modern websites and applications which is, retrieving individual data and or items from the server to update sections of a webpage without having to load an entire new page. This small detail has had a huge impact on the performance and behavior of websites.

This reading material spoke of **Ajax** and how it led to the creation of technologies that allow web pages to request small chunks of data (such as HTML, XML, JSON, or plain text) and display them only when needed, helping to solve the problem of, loading the entire page again, when a viewer/client wants to update any part of the page. The process was extremely wasteful and results in a poor user experience, especially as pages get larger and more complex, which equaled to more bandwidth and Data use.

The example in this reading material used a basic **Ajax request**, which used both XMLHttpRequest and Fetch.

## What are both XMLHttpRequest and Fetch ?

* **XMLHttpRequest (XHR)** - objects are used to interact with servers. You can retrieve data from a URL without having to do a full page refresh. This enables a Web page to update just part of a page without disrupting what the user is doing. XMLHttpRequest is used heavily in AJAX programming. XMLHttpRequest (which is frequently abbreviated to XHR) is a fairly old technology now — it was invented by Microsoft in the late '90s, and has been standardized across browsers for quite a long time
  
* **Fetch API** - provides an interface for fetching resources (including across the network). Fetch provides a generic definition of Request and Response objects (and other things involved with network requests). This will allow them to be used wherever they are needed in the future, whether it’s for service workers, Cache API, and other similar things that handle or modify requests and responses, or any kind of use case that might require you to generate your responses programmatically (that is, the use of computer program or personal programming instructions.

In thise exercise a series of files which acted as our fake database, to fetch/grab/request data. **( *in a real application, we would mostlikely use a server-side language like PHP, Python, or Node to request our data from a database.* )**

Please view the **ajax-start.hmtl file** 