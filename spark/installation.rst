Spark Cluster
===============================================================================

Master
-------------------------------------------------------------------------------

::

   spark/sbin/start-master.sh -i [hostname or ip address]

.. note:: The master hostname or ip address will be used in slaves. If master
          started with a hostname, slaves can't get access via ip address.

Port
--------------------------------------------------------------------------------

* 7077: master default port
* 8080: master default webUI


