
Myth: Eric Brewer On Why Banks Are BASE Not ACID - Availability Is Revenue 
---------------------------------------------------------------------------
http://highscalability.com/blog/2013/5/1/myth-eric-brewer-on-why-banks-are-base-not-acid-availability.html

For banks:
Consistency it turns out is not the Holy Grail. What trumps consistency is:

Auditing
Risk Management
Availability

In a post-internet world where write availability is key the real world looks more like weak consistency + delayed exceptions 
+ compensation rather than a mistake free world of perfect communication and transactions. 
Just like the old days, but now you have far more options on the ACID <---> CAP spectrum.


Eventual consistency and client applications
---------------------------------------------
http://blog.mischel.com/2012/01/31/eventual-consistency-and-client-applications/

Point: Don't start with eventual consistency.
Make your program work first. Then make it scale.


Eventually Consistent - Revisited by Dr. Werner Vogel, CTO and Vice President of Amazon.com
-------------------------------------------------------------------------------------------
http://www.allthingsdistributed.com/2008/12/eventually_consistent.html


Eventually Consistent: Not What You Were Expecting?
---------------------------------------------------
http://queue.acm.org/detail.cfm?id=2582994



An enlightening HN discussion on how shopping carts are implement in scale
---------------------------------------------------------------------------
The link itself is about Mongodb but the discussion in HN is about the shopping cart stuff.

https://news.ycombinator.com/item?id=14625702
