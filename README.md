# Custom project
Using Github as free hosting for static content, resources for the Blogger hosted website, www.offendextortion.com.

The DNS must contain something like this:

~~~~
offendextortion.com.	300	IN	A	192.30.252.153
offendextortion.com.	300	IN	A	192.30.252.154
www.offendextortion.com.	300	IN	A	216.239.32.21
www.offendextortion.com.	300	IN	A	216.239.34.21
www.offendextortion.com.	300	IN	A	216.239.36.21
www.offendextortion.com.	300	IN	A	216.239.38.21
~~~~

Then you can tell Github to serve pages for the domain.

To get traffic redirected, wei'll use the old-school method which is HTML's meta refresh.
