Log All HTTP Headers
--------------------

Zeek logs a minimal selection of data from HTTP by default that have historically
been found useful for incident response. This packages extends the logged data to 
include all of the HTTP headers and their associated values. There are scenarios 
where this information is useful. 

Installation
------------

::

	zkg refresh
	zkg install sethhall/zeek-log-all-http-headers
