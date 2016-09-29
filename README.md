# server.py
This module builds on BaseHTTPServer by implementing the standard GET and HEAD requests. It supports GZIP compression and api history callback, which is suitable to host a static single page application using the HTML5 history API.

# Usage
Usage: server.py [options]

Options:  
 * -h, --help            show this help message and exit  
 * -e ENCODING, --encoding=ENCODING  
                        encoding type for server to utilize  
 * -p PORT, --port=PORT  the port to serve the files on  
 * -i INDEX, --index=INDEX  
                        the index file page  
 * -d DIRECTORY, --directory access=DIRECTORY  
                        access directory or not