Architecture of Arcadia Application
###################################

.. note:: This application is available in GitLab in case you want to build your own lab : https://gitlab.com/arcadia-application

First of all, it is important to understand how Arcadia app is split between micro-services


**This is what Arcadia App looks like when the 4 microservices are up and running, and you can see how traffic is routed based on URI**

.. image:: ../pictures/lab1/arcadia-api.png
   :align: center
   :scale: 50%

**But you can deploy Arcadia Step by Step**

If you deploy only ``Main App`` and ``Back End`` services.

.. image:: ../pictures/lab1/MainApp.png
   :align: center
   :scale: 50%
.. note:: You can see App2 (Money Transfer) and App3 (Refer Friend) are not available. There is dynamic content showing a WARNING instead of a 404 or blank frame.

|

If you deploy ``Main App``, ``Back End`` and ``Money Transfer`` services.

.. image:: ../pictures/lab1/app2.png
   :align: center
   :scale: 50%
   
|

If you deploy ``Main App``, ``Back End``, ``Money Transfer`` and ``Refer Friend`` services.

.. image:: ../pictures/lab1/app3.png
   :align: center
   :scale: 50%