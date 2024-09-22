# Hadoop map reduce and IP addresses 
Using the same docker image of  1, process the log of web entries using map-reduce to:
1. Count the number of unique IP addresses involved in the
attack.
2. For each interval of 10 seconds, provides the following
information: [number of request, average execution time,
maximum time, minimum time]
3. Create an inverted index that for each interval of 10 second,
has a list of (unique) IPs executing accesses.
