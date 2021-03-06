===================
Integration testing
===================


Deploy HA Environment with Contrail
-----------------------------------


ID
##

contrail_ha


Description
###########

Check Contrail deploy on HA environment


Complexity
##########

Core


Steps
#####

    1. Create an environment with "Neutron with tunneling segmentation" as a network configuration and CEPH storage
    2. Enable and configure Contrail plugin
    3. Add 3 nodes with controller role
    4. Add 2 nodes with "compute" and "Ceph-OSD" roles
    5. Add a node with contrail-config role
    6. Add a node with contrail-control role
    7. Add a node with contrail-db role
    8. Deploy cluster with plugin
    9. Run OSTF tests


Expected results
################

All steps must be completed successfully, without any errors.


Deploy Environment with  HA-Contrail and Base-OS
------------------------------------------------


ID
##

contrail_ha_baseos


Description
###########

Check deploy HA-contrail on an environment with a base-os node


Complexity
##########

Core


Steps
#####

    1. Create an environment with "Neutron with tunneling segmentation" as a network configuration
    2. Enable and configure Contrail plugin
    3. Add a node with controller role
    4. Add 2 nodes with "compute" and "Storage-cinder" roles
    5. Add a node with Base-OS role
    6. Add 3 nodes with "contrail-config", "contrail-control" and "contrail-db" roles
    7. Deploy cluster with plugin
    8. Run OSTF tests


Expected results
################

All steps must be completed successfully, without any errors.


Deploy Environment with Contrail and Ceilometer
-----------------------------------------------


ID
##

contrail_ceilometer


Description
###########

Check deploy environment with Contrail and Ceilometer


Complexity
##########

Core


Steps
#####

    1. Create an environment with "Neutron with tunneling segmentation" as a network configuration and CEPH storage
    2. Enable and configure Contrail plugin
    3. Add 2 nodes with "controller" role and 1 node with "controller" + "MongoDB" multirole
    4. Add 1 node with "compute" and "ceph-OSD" and 1 node with "compute" + "ceph-OSD" + " MongoDB" multiroles
    5. Add a node with "MongoDB" role
    6. Add a node with "contrail-config", "contrail-control" and "contrail-db" roles
    7. Deploy cluster with plugin
    8. Run OSTF tests


Expected results
################

All steps must be completed successfully, without any errors.


Deploy Environment with  Contrail and jumbo-frames support
----------------------------------------------------------


ID
##

contrail_jumbo


Description
###########

Check deploy contrail on an environment with jumbo-frames support


Complexity
##########

Core


Steps
#####

    1. Create an environment with "Neutron with tunneling segmentation" as a network configuration
    2. Enable and configure Contrail plugin
    3. Add a node with controller role
    4. Add 2 nodes with "compute" and "Ceph-OSD" roles
    5. Add a node with "contrail-config", "contrail-control" and "contrail-db" roles
    6. Add 2 nodes with "contrail-config", "contrail-control" roles
    7. Configure MTU on network interfaces (Jumbo-frames)
    8. Deploy cluster with plugin
    9. Run OSTF tests


Expected results
################

All steps must be completed successfully, without any errors.


Deploy Environment with  Contrail and vlan tagging
--------------------------------------------------


ID
##

contrail_vlan


Description
###########

Check deploy contrail on an environment with vlan-tagging


Complexity
##########

Core


Steps
#####

    1. Create an environment with "Neutron with tunneling segmentation" as a network configuration
    2. Enable and configure Contrail plugin
    3. Add 3 nodes with controller role
    4. Add 2 nodes with "compute" and "Storage-cinder" roles
    5. Add a node with "contrail-config" and "contrail-db" roles
    6. Add a node with "contrail-db", "contrail-control" roles
    7. Add a node with "contrail-db" role
    8. Configure VLAN on network interfaces
    9. Deploy cluster with plugin
    10. Run OSTF tests


Expected results
################

All steps must be completed successfully, without any errors.


Deploy Environment with Contrail and bonding
--------------------------------------------


ID
##

contrail_bonding


Description
###########

Check deploy contrail with aggregation of network interfaces


Complexity
##########

Core


Steps
#####

    1. Create an environment with "Neutron with tunneling segmentation" as a network configuration
    2. Enable and configure Contrail plugin
    3. Add 3 nodes with "controller" role
    4. Add 2 nodes with "compute" roles
    5. Add 3 nodes with "contrail-config", "contrail-control" and "contrail-db" roles
    6. Bond network interfaces with balance-rr mode
    7. Deploy cluster with plugin
    8. Run OSTF tests


Expected results
################

All steps must be completed successfully, without any errors.


Deploy Environment with Controller + Cinder multirole
-----------------------------------------------------


ID
##

contrail_cinder_multirole


Description
###########

Check deploy contrail with Controller + Cinder multirole


Complexity
##########

Core


Steps
#####

    1. Create an environment with "Neutron with tunneling segmentation" as a network configuration
    2. Enable and configure Contrail plugin
    3. Add 3 nodes with "controller" + "storage-cinder" multirole
    4. Add 1 node with "compute" role
    5. Add 2 nodes with "contrail-config", "contrail-control" and "contrail-db" roles
    6. Deploy cluster with plugin
    8. Run OSTF tests


Expected results
################

All steps must be completed successfully, without any errors.


Deploy Environment with Controller + Ceph multirole
---------------------------------------------------


ID
##

contrail_ceph_multirole


Description
###########

Check deploy contrail with Controller + Ceph multirole


Complexity
##########

Core


Steps
#####

    1. Create an environment with "Neutron with tunneling segmentation" as a network configuration and CEPH storage
    2. Enable and configure Contrail plugin
    3. Add 3 nodes with "controller" + "Ceph-OSD" multirole
    4. Add 2 nodes with "compute" role
    5. Add 1 node with "contrail-config", "contrail-control" and "contrail-db" roles
    6. Deploy cluster with plugin
    8. Run OSTF tests


Expected results
################

All steps must be completed successfully, without any errors.


Deploy Environment with Controller + Cinder + Ceph multirole
------------------------------------------------------------


ID
##

contrail_cinder_ceph_multirole


Description
###########

Check deploy contrail with Controller + Cinder + Ceph multirole


Complexity
##########

Core


Steps
#####

    1. Create an environment with "Neutron with tunneling segmentation" as a network configuration and CEPH storage
    2. Enable and configure Contrail plugin
    3. Add 1 node with "controller" + "storage-cinder" + "Ceph-OSD" multirole
    4. Add 1 node with "controller" + "storage-cinder" and 1 node with "controller" + "Ceph-OSD" multiroles
    4. Add 2 nodes with "compute" role
    5. Add 3 nodes with "contrail-config", "contrail-control" and "contrail-db" roles
    6. Deploy cluster with plugin
    8. Run OSTF tests


Expected results
################

All steps must be completed successfully, without any errors.
