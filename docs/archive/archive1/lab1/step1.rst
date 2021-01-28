Lab Overview
============

During this lab, you will configure the BIG-IP system to permit traffic
to multiple backend servers. You will then run simulated user flows
against BIG-IP and verify the traffic flow, reporting and logging of
these flows.

Base BIG-IP Configuration
=========================

In this lab, the VE has been configured with the basic system settings
and the VLAN/self-IP configurations required for the BIG-IP to
communicate and pass traffic on the network. Inspect the Virtual Servers 
which have been configured. Note that they are Wwildcard (listen for all traffic) 
and have SNAT auto-map enabled. We’ll now need to configure
the BIG-IP to pass it to the back-end server.
