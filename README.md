# requestpipe

This package provides a general, http gateway. This serves to 
pipeline and throttle all calls to provide the best performance without 
overwhelming downstream services.

The input is a queue and the result is returned into a shared dictionary 
based on the uuid of the task consumed from the queue.
