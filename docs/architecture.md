# Architecture

A build is a directed graph of shards. The planner resolves the graph, the fetcher
pulls remote sources, and the writer materialises each shard into the artifact store.
