1. **Reliability**  - System can perform even when things can go wrong
    1. Application is performing what was expectations
    2. If any mistake is done by user - system should tolerate it
    3. Performance is good under expected load and data volume 
    4. Prevent any unauthorized access and abuse
2. We cannot make a system fault tolerant fully (let say if huge eaqrthquake happens and all destroyed). We can make system tolerate about certain type of faults.
3. Fault vs Failures - These are 2 different things. Fault means one component are deviating while failure means application stop providing service to user. Fault can happen so always design system to stop from failure even fault is there.
4. **Scalability** -  The application is working today doesn’t mean that it will work in even future. It all depend on load and load is affected by load parameters.
5. Performnace - Depends on 2 factor with the increase in load paramter and if reource is kept same how will the system perform . If load paramter increase then how much resource more will u need?
6. Throughput → **number of requests/transactions processed per unit of time** (not just inserts). It could be reads, writes, or any operation. 
7. Latency and Resposne time → reponse time is (service time → requestt processing time + network delay + queing delay ) while latency meaning request is waiting for handling.
8. Average Response time is mostly denoted in percentile mean first sort the repsonse tiem form faastest to slowest then median is halfway point. if median reponse time is 200ms then it means half of the user are getting ressponse in less than 200ms and remaining will take more than that - usually denoted by p50. Similarly p95 , p99 etc.
9. Horizontal Scaling means adding more machines while vertical scaling means make power thaat single machinge which isway costlier
