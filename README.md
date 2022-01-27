# bloom-filter
Implement the Bloom filter. Use:
http://www.stopforumspam.com/downloads/listed_username_30.zip
as your set S. This is a set of usernames known to be spam for the last 30 days. Select a
proper hashing memory size (n) and find the optimal number of hash functions (k). Use the
spam usernames for the last 365 days:
http://www.stopforumspam.com/downloads/listed_username_365.zip
as your stream. Submit your (1) code, (2) optimal k for your n, and (3) the percentage of
false positives all on blackboard. There is no need to submit your datasets.
Note. For hashing you can use
• murmurHash: https://sites.google.com/site/murmurhash/
• FNV: http://isthe.com/chongo/tech/comp/fnv/
• Jenkins Hash: http://www.burtleburtle.net/bob/hash/doobs.html
• Or you Hash Function of choice.
