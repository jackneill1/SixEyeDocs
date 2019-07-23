Permissions
***********

Permissions in SixEye allow for grannular customisation of what a user can do per project/device or portal level project or device. 

.. figure:: img/perm_temp.png
   :align:   left

Contexts
--------

Context Site
++++++++++++

Permissions in this context are related to the current Site only. Users already in the site can be managed. Any user added to a Site but not yet registered will be preceded with a ``@``. 

All device within a Site can also be managed on an individual basis.

Context Portal
++++++++++++++

Permissions in this context are related all Sites in the current Portal. Users already in the portal can be managed. Only users that the current users shares Sites with will appear here.

Devices are managed across the whole Portal. 

Some user settings are also available here. 

Note: Only SixEye Admins can adjust the ``set_permissions`` permissions in this context.

Permissions functions
---------------------

In each section each permission has its own function. Not shown are the ``Set Permissions`` sections. These are for setting who can set other users permissions whose functionality is explained in the following.

Permissions here are listed as in the API. The SixEye UI may have naming differences.

Context Site
------------

Site
++++

=================   ========  
Permission          Function
=================   ======== 
``Device add``      Can add a device to the current Site  
``Owner``           Is granted all view permissions and ``Set Permissions`` permissions in the current site. There *must* be at least one owner per Site
``Self:Delete``     Can delete the current Site
``Self:Edit all``   Can edit all attributes for the current Site eg. Name
``Self:View all``   Can view the current Site
``User:Add``        Can add users to the current Site
``User:Delete``     Can delete users from the current Site
``User:View``       Can view all users in the current Site
=================   ========

Device
++++++

==================   ========  
Permission           Function
==================   ======== 
``Action reset``     Can reset the current device
``Control``          Can control the device - typically this means adjusting the output
``File:Add``         Can add a file to the current devices SixEye file server
``File:Delete``      Can delete a file from the current devices SixEye file server
``File:Transfer``    Can tranfer a file from the SixEye file server to the current device
``File:View``        Can view all files on the current devices SixEye file server
``Information``      Can view information about the current device
``Maintenance``      Can view and adjust maintenance related information
``Self:Delete``      Can delete the current device
``Self:Replace``     Can replace the current device
``Self:View all``    Can view core information about the current device
``Setting beacon``   Can beacon the current device
==================   ========

Context Portal
--------------

Site
++++

=================   ========  
Permission          Function
=================   ======== 
``Self:Add``        Can add a Site in the current Portal
=================   ========

User
++++

==================   ========  
Permission           Function
==================   ======== 
``Self:Add``         Can add a User to the current Portal
``Self:Delete``      Can delete a User in the current Portal
``Self:Edit all``    Can edit all attributes related to Users in the current Portal
``Self:Suspend``     Can suspent any User in the current Portal
``Self:View all``    Can view all Users in the current Portal
==================   ========
