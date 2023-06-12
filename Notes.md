<h1 align="center">Postman API Fundamentals Program Notes<h1>
<h3>What are APIs?</h3>
<ul> 
  <li>API -> Application program interface, is a contract that allows code to talk to another code. </li>
  <li> Importance-> Help developers to use existing features, enterprise get faster innovation, API are product themselves.</li>
  <li> Used by- All sort of engineerers in various industries</li>    
  
  <li> Analogy: API can be visualised as waiter, that serves as a link between customer and kitchen. Similarly, API is link between client and server</li> </ul>
  
  <table align = "center">
    <th>Networking term</th>
    <th>Description</th>
    <th>Restaurant Analogy</th>
    <tr>
      <td>Client</td>
      <td>The requester ex: browser,application</td>
      <td>Customer</td>
    </tr>
    <tr>
      <td>API</td>
      <td>Inferface that interacts with backend</td>
      <td>Waiter</td>
    </tr>
    <tr>
      <td>Server</td>
      <td>The backend where processing happens</td>
      <td>Chef / Kitchen</td>
    </tr>
  </table>
  <img src="https://everpath-course-content.s3-accelerate.amazonaws.com/instructor%2F26fp2261340y1ukokimvca8su%2Fpublic%2F1647355689%2Fdigitalrestaurant.1647355689760.png">
  
  <h4>TYPES OF API</h4>
  <ul><li>Hardware API: When software communicates with hardware. <br> <i> Example: Phone camera interacting with OS.</i></li>
    <li>Software Library API: Code communicating with another code block. <br> <i> Example: Code Libraries </i></li>
    <li>Web API: Interface to communicate with any code base present over internet. <br> <i> Example: Chatgpt API in personal code</i></li></ul>
  <h4>TYPES OF API ARCHITECTURES</h4>
  <ul>
    <li>REST API (Representational State Transfer)</li>
    <li>GraphQL</li>
    <li>SOAP(Simple Object Acess Protocol)</li>
    <li>gRPC(Google Remote Procedural Call)</li>
    <li>WebSockets</li>
    <li>WebHooks</li>
  </ul>
  <p><i>NOTE: RestAPI's are used the most. In this course of Postman API, Only Restful API is discussed.</p></i>
  
  <h3>Introduction to PostMan</h3>
  <ul>
    <li>Postman: A platform to use, build and collaborate APIs</li>
    <li>Old method: API calls used <kbd>curl</kbd></li>
    <li>Postman is improvised platform to this old method.</li>
  </ul>
   
  <h3>Module-3: First API Request</h3>
  <ul>
    <li>Create a workplace, (Workplace: A place where all your work, api requests, api posting, collaboration etc. happens</li>
    <li> Create a collection (Collection: A place to organise your API Requests.) </li>
    <li> Request your API using <kbd>GET</kbd>.</li>
    <li>Client ->Makes the request.</li> 
    <li>Request is sent over ->Network</li> 
    <li>Server -> interprets the request and sends an appropriate response.</li>
  </ul>    
<br>
    <table align="center">
      <th>Method Name</th>
      <th>Operation</th>
      <tr> 
        <td><kbd>POST</kbd></td>
        <td> CREATE (Send Data)</td>
      </tr>  
      <tr>
        <td><kbd>GET</kbd></td>
        <td> READ (Retrieve Data)</td>
      </tr>
      <tr>  
        <td><kbd>PUT/PATCH</kbd></td>
        <td> UPDATE (Update Data)</td>
      </tr>
      <tr>  
        <td><kbd>DELETE</kbd></td>
        <td> DELETE (Delete Data)</td>
      </tr>
    </table>
  
  <table align="center">
    <th>Protocol</th>
    <th>Host</th>
    <th>Path</th>
    <tr>
      <td>https://</td>
      <td>library-api.postmanlabs.com//</td>
      <td>/books</td>
    </tr>
  </table>    
<h4>QUERY PARAMETERS</h4>
  <li>To refine/specify/filter API requests, query parameters (key-value pair) are used</li>
  <li>Syntax: at the end of path, <code>&lt;key&gt;=&lt;value&gt;</code></li>
  <i>Example: https://some-api.com/photos?orientation=landscape</i><br>
  <i>Example: https://some-api.com/books?genre=comedy</i><br>
  <i>Example: https://google.com/search?q=apple&q=mobile</i><br>
  <i>Example: https://some-api.com/photos?orientation=landscape&color=blue</i><br>
  
  <table>
    <th>Code</th>
    <th>Meaning</th>
    <th>Example</th>
    <tr>
      <td>2XX</td>
      <td>Success</td>
      <td>200-OK,201-Created,204-No content</td>
    </tr>
    <tr>
      <td>301</td>
      <td>Redirection</td>
      <td>301-Moved(path changed)</td>
    </tr>
    <tr>
      <td>4XX</td>
      <td>Client Error</td>
      <td>400-Bad request,401-Unauthorized,403-Not permitted,404-Not found</td>
    </tr>
    <tr>
      <td>5XX</td>
      <td>Server Error</td>
      <td>500-Internal server error, 502-Bad gateway, 504-Gateway timeout</td>
    </tr>
  </table>
  
  
  
  
  
  
