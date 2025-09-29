# Multi-threaded-Proxy-Server
A high-performance proxy that forwards client requests to upstream servers using a thread pool for concurrent connections, supporting connection pooling, caching, logging, basic access control.

NOTE:

This code can only be run in Linux Machine. Please disable your browser cache.

To run the proxy without cache Change the name of the file (proxy_server_with_cache.c to proxy_server_without_cache.c) MakeFile.

When website is opened for the first time (url not found) then cache will be miss.

Then if you again open that website again then Data is retrieved from the cache will be printed.
