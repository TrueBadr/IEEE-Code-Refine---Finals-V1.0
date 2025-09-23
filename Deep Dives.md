# 1. High Traffic ( Scalability and Performance )
- increase number of servers
- using load balancer that divide requests along servers
- indexing the repeated queries
- making DB Sharding where for example server1 : from 0% to 40% of data , server2 : from %20 to 60% , server3 : from 40% to 80% , server4 : from 60% to 100% , server5 : from 80% to 100% and from 0% to 20% 
# 2. Authentication and Authorization
- each user got his own JWT token
- the token has the user permissions
- token has specific time and then expire
- Passwords stores in DB hashed (bycrypyt)
