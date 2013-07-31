.. index: How Fuel Works

.. _How-Fuel-Works:

How Fuel Works
==============

Fuel works on a simple premise. Rather than installing each of the myriad 
components that make up OpenStack directly, you instead use a configuration 
management system like Puppet to create scripts that can provide a configurable, 
reproducible, sharable installation process.

In practice, that means that the process of using Fuel looks like 1-2-3:

1. First, set up Fuel Master Node using the ISO. This process only needs to be 
   completed once per installation.

2. Next, discover your virtual or phisical nodes and configure your OpenStack 
   cluster using the WebUI.

3. Finally, deploy your OpenStack cluster on discovered nodes. Fuel will do all 
   deployment magic for you by applying completely customizable Puppet manifests, 
   enabling you to maintain your cluster start with one of 
   the included OpenStack architectures and adapt to your own situation as 
   necessary.

.. image:: /_images/010-how-it-works_svg.png
    :width: 300px
    :height: 300px

Fuel comes with several pre-defined deployment configurations, some of which 
include additional options from which you can choose.

As of the 3.1 release of Fuel™ for OpenStack, FuelWeb is included as part of the 
package. FuelWeb is a simplified way to deploy production-grade OpenStack 
clouds. It provides a streamlined, graphical console experience using the 
underlying scripts from Fuel Library, including proven deployment configurations 
and a well-organized workflow for deploying and managing OpenStack environments.

FuelWeb integrates all of the components of Fuel Library into a unified, 
web-based graphical user interface that walks administrators through the process 
of installing and configuring a fully functional OpenStack environment.