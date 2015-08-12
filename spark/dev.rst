Development Notes
===============================================================================

* Commodity servers can replace a high end single server?
* HDFS is required in a cluster to work with files. Does HDFS require to be in
  a cluster? Single HDFS may create I/O delay.
  - can we measure the source of delay from process?
  - hdfs should be in /tmp?
  - hdfs is in SSD or SATA?

* wc took 4-5 secs
* 2 sparks took 12 secs
* 3-5 sparks took 9 secs
* How can we identify overhead?
* 
