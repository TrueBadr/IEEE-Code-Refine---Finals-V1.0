# Backend Estimation
- Number of users is 10 Million users
- Number of daily active users (DAU) is a million users
- user make make in average 6 requests 
- so daily server has 6 million requests to handle 
- about 70 request per second
- each request in average - 3 queries
- so daily DB has 18 millions query to handle
- we could use 9 servers and divide the queries on like each server handles daily (around 670 thousand request - 2 milion query )
