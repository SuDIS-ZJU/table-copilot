
00:00 
Hello, everyone. In this video, I will present our demo work table copilot, a table assistant empowered by natural language conditional table Discovery. The rise of ll MS enables the development of table assistance. 

00:15 
However, current table assistants often overlook the initial step, table Discovery, our aim to integrate table Discovery into the table assistant, creating an end to end table assistant, featuring precise, interactive, and personalized table search. 

00:32 
For example, the user may want unionable tables with specific conditions, such as CS grade above 90. A table assistant with table Discovery capability is the best choice for this practical scenario. However, we face two primary challenges. 

00:49 
Firstly, due to token limits and privacy concerns in putting table repository into an llm is impractical. Ll MS often struggle with tabular data. Second, existing table Discovery methods cannot handle scenarios where users input both tables and natural language requests simultaneously. 

01:08 
To fill the gap. We propose table copilot, an llm based table assistant capable of table Discovery. Specifically, we prompt an llm with carefully designed instructions to allow for recognition of table Discovery tasks, an invocation of the desired table Discovery methods. 

01:25 
Notably, we define a new table Discovery scenario named an lctd that takes both a natural language condition and a query table as input of the table assistant, and provide a novel fusion based solution for it. Our proposed solution makes table Discovery more intuitive and friendly to users. 

01:44 
Next, we'll demonstrate our table copilot system which features three main interfaces, the table repository, table search and table processing. Our table copilot panel is on the right. Users can choose ll MS and check their chat history. 

02:01 
On the table repository page, users can view both the overall Information about the repository and detailed Information for each individual table. Now let's move to the table Discovery interface. The work space in the upper middle section displays the current table. 

02:18 
And the Discovery panel below allows you to switch between different methods. Users can call table Discovery methods from the table Discovery panel or directly use the table assistant on the right. We'll simulate an end to end process starting from scratch without a query table. 

02:36 
Suppose users want to search for student related Information, browsing the repository can be time consuming. Instead, they can simply call the table assistant and enter the request student Information. 

02:50 
The assistant recognizes this as a table Discovery request and invokes our curfew me algorithm to return relevant tables. If the user finds this to underscore Info table interesting but wants to know the grades of the students. 

03:03 
They can load the query table stew under screen photo, work space and input natural language request, joinable tables containing Information about student grades. Users can also use the model panel on the right to adjust the model parameters. 

03:20 
For clicking create model. We can see the process of the online fusion model being trained. Users can find previously saved models in the model history section below the navigation bar. Here we simply select the train model we want and click the search button. 

03:37 
Through a brief moment, the search results will appear. By clicking the model analysis button. We can also view some metrics about the accuracy evaluation of the models outcomes. We'll demonstrate using the table assistant for nlctd once more. 

03:54 
Let's assume the user wants to search for students with high grades. They can input unionable tables to stoner surfer with high grade students. The assistant invokes our perfume a method and returns the results. 

04:12 
Finally, we'll quickly show how our system handles table manipulation tasks. For example, for a join operation, choose base table, specify the join column, decide whether to allow semantic joins and select the table to join with and finally click join to get the results. 

04:28 
Similarly, users can also perform table pre assessing directly through conversations with the table assistant. That's all for our demonstration. Thank you. 
