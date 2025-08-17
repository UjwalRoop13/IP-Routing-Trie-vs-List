This project implements an IP Routing Table using two approaches:
Trie-based (Prefix Tree)
Naïve List-based Lookup
It compares their performance on insertion, search (lookup), and deletion operations, simulating how routers store and query IP prefixes.


Features:
Insert random IP addresses into both Trie and List structures
Search IP prefixes efficiently with Trie vs slow linear lookup in List
Delete random IPs and compare pre- and post-deletion search results
Measure performance (in ms and µs) for all operations
Performance gain calculation (Trie vs List)
