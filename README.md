# Ensuring Fault Tolerance and Consistency in Distributed Systems Using ZAB
* Author: Naveen Srikanth Pasupuleti
* Published In : International Journal of Innovative Research in Engineering & Multidisciplinary Physical Sciences (IJIRMPS)
* Publication Date: August 2021
* E-ISSN: 2349-7300
* Impact Factor: 9.907
* Link: [Read the paper](https://www.ijirmps.org/research-paper.php?id=232536)

**Abstract**:\
This paper tackles the challenge of high write latency in distributed systems that use write batching to improve throughput. While batching reduces transaction overhead, it can cause significant delays due to coordination and flushing times, especially as system size grows. To overcome this, the study proposes using the Fast Paxos algorithm, which reduces communication rounds and speeds up consensus. This approach aims to balance efficient write processing with low latency, enhancing overall system responsiveness and consistency. The results demonstrate improved performance in write-heavy distributed environments.

**Fault Tolerence**:\
Fault tolerance is a system's ability to continue operating without interruption despite the failure of one or more of its components.

**Key Contributions:** 
* **Algorithm Development** \
  Designed and optimized Fast Paxos latency methodology by reducing write latency.
* **Performance Comparison** \
  Conducted bench marking between Write Batching Latency and Fast Paxos Latency.
* **Reserach Leadership** \
  Led the research and technical implementation , focusing on advancing distributed database through algorithm innovation.

**Relevance & Real-World Impact**
* **Distributed Consensus Enhancement:**\
Improves write performance by leveraging Fast Paxos’s low-latency fast path, which reduces write delays especially in low-contention environments.

* **Write Operation Optimization:**\
Write batching techniques help decrease latency in Raft-based systems, though the leader bottleneck remains a challenge for scalability.

* **Trade-offs and Practical Considerations:**\
While Fast Paxos offers faster writes, it adds complexity and coordination overhead, requiring careful conflict handling and quorum management to achieve efficient deployment.

* **Academic Recognition :** \
    Featured in academic literature and technical publications addressing DNS query management and performance enhancements within ETCD systems.
* **Educational Impact:** \
    Utilized in scholarly research efforts, facilitating ongoing academic discussions on container orchestration and optimization of cloud system performance.

**Experimental Results (Summary)**

| Cluster Size (Nodes) | Write Batching Latency (ms)| Fast Paxos Latency (ms)| Improvement (%) |
| ---------------------| --------------------- | --------------------------- | ----------------|
| 3                    | 46                    | 43                          | 6.52            |
| 5                    | 48                    | 45                          | 6.25            |
| 7                    | 50                    | 47                          | 6.00            |
| 9                    | 52                    | 59                          | 5.77            |
| 11                   | 54                    | 61                          | 5.56            |

**Citation**
* **OPTIMIZING WRITE PERFORMANCE BY REDUCING LATENCY IN DISTRIBUTED SYSTEMS**
*   Naveen Srikanth Pasupuleti
*   International Journal of Innovative Research in Engineering & Multidisciplinary Physical Sciences
*   E-ISSN-2349-7300

**License**
* This research is shared for academic and research purposes. For commercial use, please contact the author.

**Resources**
* [IJIRMPS Website](https://www.ijirmps.org/)

**Author Contact** 
  * LinkedIn: https://www.linkedin.com/in/naveensrikanth | Email: connect.naveensrikanth@gmail.com
