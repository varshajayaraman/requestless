# requestless

This is a rate-limiter service which keeps the #request to any service/api under the agreed number.

ASSUMPTIONS:
Consider that RequestLess is a company which provides apis which do the job of rate-limiting the requests.
Service model:
  1. User-agnostic. A time-specific bucket approach for our customer. 
    Use case: We give our customer a tool which would ensure that they don't get bombarded with requests. Like a givernment website which is mostly used for information purposes.The government websites aren't focused on how many times the website has been accessed by a particular user.
  2. user-based:
  
 
