
# Problem Statement: 
### Develop a Web-Based Application to Facilitate Student Investment in the Share Market with a Credit System

There has been a growing interest among students in schools and colleges to invest in the Share Market. However, a significant majority of these students, approximately 95%, end up facing losses due to their limited knowledge and experience in financial markets. To address this issue and encourage responsible investing,  Develop a web-based application that provides students with a simulated investment platform using credits.

# Introduction about the Website
This web app is intended to provide a simulation of the real stock market. Every user is given an initial amount of 100,000 dollars, which they can use to purchase a variety of stocks. User can also search for a particular stock and view its information. For each stock, we provide a line chart of its price for the last three years so that user can do some analysis. We also provide the most recent market news for user to make better decisions.
   
## Tech Stack
 
1. We used React.js as our frontend framework, and Express, Node as the backend framework. 
2. We store user's information in Mongodb and the deploy the database on MongoDB Atlas. In addition to user's name and password, we also store user's balance as part of the schema.
3. The 3rd party API that we used are https://finnhub.io/ and https://www.tiingo.com/, one for retreiving the latest market news and one for retrieving the stock price.
