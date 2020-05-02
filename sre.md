how CPU works?
https://www.youtube.com/watch?v=6jSKldt7Eqs

Order by speed CPU call, RAM call

What's a mapreduce https://research.google/pubs/pub62/

Explain how docker works on Unix? What is `nsenter`? Differences between container and VMs?
https://www.youtube.com/watch?v=-YnMr1lj4Z8


What's a page? WHy is 8KB? When do I want to change it?
https://en.wikipedia.org/wiki/Page_(computer_memory)

how CDN works?

What definitely will not work for docker but works VM?
Kind of an obvious question, but people still like to ask it. You cannot run windows on Linux docker! 
Kernel is shared between containers and the host system, so you cannot run anything that won't be supported 
by the host system.   

Explain sidecar, ambassador, adapter patterns

Which deployment strategies do you know?

SLO\SLA, Error Budgets ?
https://landing.google.com/sre/workbook/chapters/error-budget-policy/

What are the three types of storage?

What would you use to store files on a network?

What is "big data"? What is a typical big data life cycle? 
What is map reduce? Describe the steps involved with map reduce. 
What is HPFS and what advantage does it have for processing big data?

Encrytions - Assymetric vs Symmetric and alogrithms?

Troubleshooting Latency?

HDFS, NOSQL Databases, MapReduce, Stream Processing, Coordination, use cases etc..)?

How to eliminate Single Point of Failures?

You have a system with limited memory, and you have to read a file and then depending on the input,
you need to pass the info to other nodes how will you do it. You can't load the whole input file in memory at once.
Modified the question: the file is a stream of words (one word per line) you need to sort the words.

What’s an SPF record?
An SPF record is a Sender Policy Framework record. 
It’s used to indicate to mail exchanges which hosts are authorized to send mail for a domain.




### Extra
4 golden sign of API health monitoring google

- **Latency:** The time it takes to service a request, with a focus on distinguishing between the latency of successful requests and the latency of failed requests.
- **Traffic:** A measure of how much demand is being placed on the service. This is measured using a high-level service-specific metric, like HTTP requests per second in the case of an HTTP REST API.
- **Errors:** The rate of requests that fail. The failures can be explicit (e.g., HTTP 500 errors) or implicit (e.g., an HTTP 200 OK response with a response body having too few items).
- **Saturation:** How “full” is the service. This is a measure of the system utilization, emphasizing the resources that are most constrained (e.g., memory, I/O or CPU). Services degrade in performance as they approach high saturation.

[Google's SRE Book](https://landing.google.com/sre/books/)

