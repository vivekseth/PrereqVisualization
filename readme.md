# Rutgers Prerequisite Visualization #

Simply open prereq.html. If you see nothing your browser may be blocking local xhr requests. 

## Cross Origin Request Workaround ##

Some browsers block js requests to local files if you're using the `file://` protocol (e.g. chrome).

If you have python installed you should be able to open a simple http server using
`python -m SimpleHTTPServer <port>`

Run the server from the root directory of this repo and visit `localhost:<port>/prereq.html`

Alternatively, you can host on a local or remote server. 