## Task 1

## 1.	What is Morrison's Strategy

We have seven priorities to grow and enhance the brand and the business, all of which are supported by our Fix, Rebuild, Grow, Sustain strategy. (Morrisons PLC)
a.	Increase level of competition:

b. Good customer service:
c. Service to the community and local integration:
d. Organization simplification and speed up:
e. naturally digital:
f. pride in cleanliness:	
g. scaling and innovation of profitable growth:

## 2.	What strategic decision did it make with Amazon?
• Consider Structured and Unstructured decisions types
Actually Morrison does  have an online e-commerce site platform to sale their product like Tesco and other retail organization but it is not efficient  as the competitors so they plan to improve their online shopping methodology but instead of improving their own e-commerce site they collaborated with amazon because amazon is the largest e-commerce website in the world and  amazon works as per new generation shopping thoughts and amazon review system and recommendation system helps users to shop their desire product. So this strategy decision to collaborate with amazon helps Morrison to advertise their products in larger scale and it saves their money to improving on their own e-commerce site . 

### More about Morrison strategic decisions 

![image](https://github.com/kireetigudla/Business_intelligence/assets/122108823/3bc575b3-5035-449e-a5d9-18915e7ca0bc)



The strategic decision help to booster sales by making goods more accessible to customers. It also helps in supply of freshly baked foods and everyday essentials. It enables good delivered on time to customers without delay.


## 3.	What tactical decisions did Morrison make as a company to achieve the goals and objectives set by its strategy?
• Consider Structured and Unstructured decisions types


![image](https://github.com/kireetigudla/Business_intelligence/assets/122108823/7872dc94-6dfb-4d6c-8783-23c6d213bdca)



## 4.	What day to day operational decisions needed to be made to operate this partnership?
• Consider Structured and Unstructured decisions types

![image](https://github.com/kireetigudla/Business_intelligence/assets/122108823/6db0733b-d86f-4ee4-a522-d35e8e6cb535)


## Task 2:

## 1. Propose/Identify/Develop an adequate diagram that illustrates the existing BI Architecture of your organization.
 

![image](https://github.com/kireetigudla/Business_intelligence/assets/122108823/f0d9d4ee-20e2-45df-ac2e-896e65df766d)



 ## 2. Indicate/explain the Data sources (internal and external data)? Think of the existing management support systems (OLTP)

Uber's internal data sources include:

1.	Car and Driver Information: Driver details, such as vehicle information, driver engagements, time of delivery, driver and riders’ evaluation, and more, are gathered from the Uber application.

2.	Information on Ride-Hailing Assistance: The Uber app provides information about the following: the climate condition, driver and passenger details, trip duration, pickup and drop-off locations, payment transactions, and traffic conditions.

3.	Functional Measure: Food availability, driver availability, estimated arrival and delivery times, and other information are collected by the Uber app.

4.	Data on transactions and payments: All transactions, including low amounts, declined top-up messages, card information, customer account information, amounts, and so forth, are recorded by Uber's transactional system.

5.	User Choices and Profiles: User information, ride history, user experience, login history, and user engagement details are all accessible from the dashboard of the Uber application.

6.	Customer Support Conversations: In order to help consumers with their problems, the Uber customer care team uses chatbots, emails, and phone calls to obtain data.

7.	Data on logistics and supply chains: The Uber organization obtains data from various departments, including manufacturing, distribution, surveillance of quality, and management of logistics.

8.	Geographic Information Systems and GPS data in real time: The mapping system on the Uber app provides the company with location, pick-up time, car selection based on size and cost, matching system, and accurate real-time information.

## External Data Sources at Uber:

1.	Climate Information: The Uber organization's climate forecasting department obtains its data from a climate smartphone and climate application, which it uses to adjust prices in accordance with demand.

2.	Map information and traffic detection system: The Uber organization operates on a real-time system pattern and uses the Google Maps system to check the amount of traffic at that specific time.

3.	Data on Markets and Competition: The Uber Surveillance department gathers information on customer preferences, competitor market patterns, market dynamics, and other topics.

4.	Event and Location Information: In order to measure the statistical pattern that will benefit their business, the Uber Organization department obtains information from the current venue and events news application.

5.	Information on Public Transit: The Uber Organization department obtains information for the public transportation app so that it can receive news, updates on transportation laws and policies, and other things.

6.	Law and Regulation Information: Uber Organization measures news patterns and makes adjustments to its regulatory and legal data by utilizing government regulatory and legal apps.


Uber's OLTP enables decision-making, handling, and managing complex tasks like critical assessment, more evaluation, large, complex data, to improve optimization of the business—all of which are very important in both the external and internal data—by utilizing tools like artificial intelligence, machine learning, data analytics, and more. (Berthold and Hand, 2007)


## 3.  Will your organization consider unstructured data as a data source? – Why, explain?
Yes, Uber Organization views unstructured data as a source of data since it is relevant to the application. 


Uber employed icons to describe rides, deliveries, and promos in addition to pictures and photos that provide details about the services, such as text, important plans, airport rides, and so on.

-Information about mapping and matching 

-text from the application providing a description of the data, both in chatbot conversation and writing

## 4. Justify your choices made in the BI Architecture design – based on business needs and trends in industry (e.g., Cloud computing, data Lake houses, agility – refer to the reading on the Six shifts to create a game-changing data architecture)?
  1.  Cloud based data platforms:
The cloud database system used by Uber Organization is called NoSQL. In terms of service-oriented computing, cloud computing is a model of astounding success. Major factors contributing to this success include elasticity, pay-per-use pricing, economies of scale, and scalability. 
Uber Organization can now execute heterogeneous query workloads concurrently and estimate how each query's performance when using cloud NoSQL database systems for data processing environments. 
One important way that NoSQL databases help Uber's organization is through replication, which boosts availability, dependability, and performance forecasting. However, this implies a cost to maintain consistency. 
2. Real time data Processing: The ETA (Estimated Time of Arrival), safety features, fraud detection performance monitoring, supply and demand, balancing pricing algorithms, and geospatial data are among the various real-time operations that the Uber organization engages in. These tasks are managed by various artificial intelligence-powered APIs, and Apache Kafka handles the ETL process of all the activities in a real-time manner.
3. From pre-integrated commercial solution to modular, best -of -breed platforms: Before developing the next generation, Uber Organization noted that our underlying infrastructure was horizontally scalable to meet the urgent business needs. We also had ample time to analyze our data content, data access patterns, and user-specific requirements to determine the most important issues. Our investigation uncovered four primary pain points:
- Scalability constraint on HDFS: To address this issue, Uber Organization relies on HDFS to grow their big data infrastructures. Performance can be adversely affected by storing a large number of small files because HDFS's Name Node capacity acts as a bottleneck by design.
- More rapid data in Hadoop: Uber Organization had to re-architect their pipeline to incrementally ingest only updated and new data in order to accelerate data delivery. This was necessary due to the inefficiencies of our snapshot-based ingestion method on our second-generation Big Data platform.
-Hadoop and Parquet support updates and deletes: Uber organization needed to figure out how to get around this restriction in our HDFS file system so that we could also support update/delete operations in order to set up our Big Data platform for long-term growth.
-Quicker modeling and ETL: ETL and modeling uber jobs were snapshot-based, much like raw data ingestion, meaning that each run of the platform required rebuilding of the derived tables. Additionally, ETL jobs needed to become incremental in order to lower data latency for modeled tables.

-Recent Generation: The Uber organization improved the reliability, scalability, efficiency, latency, and quality of its data.
4. Transforming decoupled data access from point-to-point: Uber's architecture has improved as a result of the move to a more decoupled data access strategy. It can now handle a variety of payload traffic, support a flexible logical topology, and provide differentiated latency guarantees. Without creating closely knit relationships between data sources and services, it permits data access and analysis across multiple organizational divisions. This modification to Uber's architecture aligns with the concepts of micro services, modularity, and data democratization. (Liu et al., 2015, pp.90–97)
5. Transitioning from a corporate repository to a domain-oriented design: The Uber Organization employs a Domain Metric approach to facilitate the dissection of current applications, accounting for scalability, workload, and account performance. Micro services-based architecture is used to handle these aspects. (Camilli et al., 2020, pp.189–196)
6. Transitioning from inflexible data models to adaptable and expandable data schemas: Uber manages complex tasks, like data processing and batch and real-time processing, by utilizing machine learning, artificial intelligence, and data analysis tools.

## Task 3:
## Based on the articles above, identify and describe the metrics (profitability, revenue, risk) that Amazon or Morrisons could consider in supporting the decision of Amazon on whether or not to purchase Morrisons. (Note: Morrisons has already been purchased by a US firm – _therefore, imagine this has not happened yet)
“Note: All this points stated below show that Amazon should buy Morrison”
## Revenue:
- Morrison shared a profitable 10.5% stake in Tesco, Sainsbury's, and Asda.
- Morrison gains from the automated stock-ordering strategy employed by Amazon and the collaboration with Prime Subscribers.
- Amazon uses click-to-revenue analytics to rank marketing performance.

## Profitability:
-With so much money to invest in the company, Amazon may open more stores in the south of England, especially in the southeast, where Morrison's presence is most pronounced.
- To determine the Net Promoter Score and profit margin of each client that improves on-time performance
- Businesses like Morrison should sell a variety of profitable products, as the majority do, must admit that certain revenue generates greater profit than others.
## Risk:
-Due to the pandemic Morrison did not have to close in 2020-21, sales went up but annual profit fell. Morrison had business stability and good strategies to manage their risks and also consistency.
- Occasionally, management may develop an infatuation with a single measure, overemphasizing it to the detriment of other signals and ultimately distorting behavior of Morrison.
- Morrison should implement project projection and business forecasting to be able to manage risk
- Morrison should use machine learning tools. By doing so, Morrison businesses may gain a deeper understanding of their actual performance and improve their handling of company risk.
-The growth of German discount retailers Lidi and Aldi has been the primary concern in recent years.
## Task 4:
## (i)	Identify (with examples) the value proposition/s of Alpen Hotel.

### a. Customer Intimacy: 
- An interview was done in order to collect client information.
- The hotel industry can learn about reservations, remarks, and feedback from travelers by using these data.
- Introduction of Data analytics is a means to understand customer’s behaviors.
- A CRM system is now used by hotels all over the world to find and cultivate long-term business relationships with clients.

### b. Product Innovation:
- The widespread use of mobile technology along with the advancements in artificial intelligence, machine learning, and deep learning make working with the hotel business even better for customers.
- The use of CRM System has help to bring improvement in the market strategies.
-Data Analytic are used for solving complex problem like understanding the trends

### c. Operational Excellence: 
-This skill necessitates not only technological expertise but also a business comprehension of the hospitality sector.
-To be successful in the increasingly complex and competitive business, companies must have the capability to digitally harness all the available information from the CRM system.
- The future management of clients' confidentiality and privacy is aided by privacy-intrusive profiling.
- CRM has developed into a crucial component of businesses' marketing strategies in order to keep their devoted customers, which boosts their market share, builds their brand, and increases revenue.
- The hotel sector may pursue data-driven decision-making more rapidly, effectively, and efficiently with the use of data analytics.
- The lack of real-time information in non-integrated hotel systems prevents hoteliers from having complete control over and visibility into their business operations, which is a drawback of operational excellence.

### d. Risk Management:

-Customer Privacy 
-Customer Security
- Data analysis can also assist in accurately preparing data to reduce risk within the organization, including errors and noise in data descriptions that could cause incorrect decisions to be made.


## (ii) Propose BI/D&A approaches based on the value propositions identified for Alpen Hotel.

### D&A Approaches by Values Proposition

![image](https://github.com/kireetigudla/Business_intelligence/assets/122108823/01b06210-4eae-499f-a77c-d406c9b6c908)
![image](https://github.com/kireetigudla/Business_intelligence/assets/122108823/3d720807-77a3-47b3-b8ce-9781ea706776)


## (iii) Identify and provide examples of any three (3) types (descriptive, diagnostic, predictive, prescriptive) of analytics that Alpen Hotel could apply to its business problem..

- Breach of privacy (descriptive “What happened?")
- Invasive personal profiling: using privacy security tools to keep an eye out for any odd behavior (diagnostic   "Why did it happened?")
- What guidelines and plans does John have going forward regarding the confidentiality and privacy of his clients? (Prescriptive "What should I do?")
- John must weigh the trade-off between privacy and the guests' personalization.
- To keep the trust of his clients, he must make sure that the information gathered from them is safe and secure.
- John would have to make sure that the personal information and data of their visitors is protected by multiple layers of strong encryption in order to entice them to divulge their details to Alpen Hotel.

## Task 5:
### Business Driven Approach: 
-Data Scalability, Data Aggregation, Data Integration
-They learnt Problem Framing and understanding business outcome for example they created a system called bricks 
-Digital Transformation 
-Data Scalability 
-Cloud Development/ real-time Data lake i.e. Data Global Architecture (Delta and data lake house)
-Creation of Digital Central of Excellent 
### Energy Transition and Digital Transformation: It facilitates the development of new business models to manage the energy transition (Artificial Intelligence)
- Ability to reduce and optimize stock level in shell
-Value chain in shell base of the business case
-The market's diversity in shell products.
--Failing early and fast. Successful failure rewarded.
-Micro Development

### Joint Ownership:
- Regardless of where you are in the organization, you can subscribe to the essential principles of the shared Foundation architecture, which operates on shared platforms throughout the shell business. (Global Architecture).
 
### Cross Functional or Scum Teams:
-Leadership and Mentorship
-Partnership and Sponsorship
-The ability to persevere in the face of difficulty, or fortitude.
-Development Program was introduce in shell to hence the growth.
- Team work 

### Emerging Technologies:
-Cloud Development/ real-time Data lake i.e. Data Architecture (Delta and data lake house).
