# mojobake
a Mojo app to purposely misidentify the content encoding

I had some problems with some user-agent and HTTP libraries doing the wrong
thing with servers that didn't declare a content encoding. I wanted to see
what would happen when the server didn't get it right.

This might happen when the content creator saves the content with the 
encoding that is not the one the server wants to report. Or, when the
server is misconfigured but the content it right.
