<h1> Performance Testing Project: Invoice System </h1>
This project serves as a demonstration of performance testing for a local host application named Invoice System. The goal is to simulate various end-to-end scenarios typical in such systems, including user authentication, client management, and item management.

<h2>Scenarios Covered</h2>
<h4>1- Add client Thread Group:</h4>

-Simulates a user logging into the system, adding a client, saving the client information, and then logging out.
<h4>2- Add Item Thread Group:</h4>

-Mimics a user logging in, adding an item to the system, saving the item information, and subsequently logging out.
<h2>Tools and Techniques Utilized</h2>
<h4>HTTP(S) Script Recorder:</h4>

-Used to support the creation of scripts by recording HTTP requests and responses exchanged between the client and server.
Parameterization:

<h4>Leveraged different types of parameterization techniques:</h4>
-User Defined Variables: Employed to dynamically set the IP address for flexible script execution.
Random Variables: Utilized to generate unique client names and item details for each iteration, enhancing script realism.
<h4>Transaction Controllers:</h4>

-Implemented to structure and organize the test plan, grouping related requests and samplers together for better management and analysis.
<h4>Loop Controller for Login:</h4>

-Employed a Loop Controller to iterate through the process of adding items, providing a realistic workload for the system.
<h2>Result Analysis</h2>
The performance testing results were analyzed to assess various performance metrics such as response times, throughput, and error rates. 
