Sites
*****

A Site is a collection of information, typically containing some devices, users and the assocaited permissions for those users to view and interact with the devices in that Site. There are typically multiple Sites in a Portal.

Devices
=======

Devices in the Site that the current user has the correct Permissions to view are listed in a sortable table. The device name is custom where as the other information about a given device is reported back from the device itself. 

More information about devices can be viewed by clicking it which will open the device view for that device. It is the decision of the device manufacturers as to what information the device reports back. 

Adding a device
---------------

- Click the 'Add Device' button to the top right of the device table
- Give the device a name and click Submit
- Copy the :term:`device key` to the new device and paste it into the device using the method specified by the device manufacturer

A device will show as 'Unassociated' until the device connects for the first time. Permissions related to this device can be managed as soon as the device appears in the device table.

Replacing a device
------------------

- Select a device by clicking the circle to left of the device name
- Select 'Replace' from the toolbar above the devices table
- Copy the new device key to the new device and paste it into the device using the method specified by the device manufacturer

Removing a device
-----------------

- Select a device by clicking the circle to left of the device name
- Select 'Remove' from the toolbar above the devices table
- The device will be removed from the Site and the device will no longer try to connect to the Site

The Device name will be retained but when the new device connects all existing device information will be lost and replaced by the new device information

Note: where possible, all settings related to this device will be retained but if the device type has changed, its possible that Tasks and Actions associated to this device will be invalid. Please check the Tasks tab for any conflicts. 

Users
=====

Users that are part of a Site and that the current user has permission to view will appear here.

Users in a site can be in 3 different states:

- Active: Can access the site according to their permissions
- Invited: Is yet to create their account in this :term:`portal`, but when complete they will be able to access the account according to their permissions
- Suspended: This user has been suspended at a :term:`portal` level and will not be able to login or interact with the site. Learn more about suspending a user :ref:`here<Suspending a user>`.

Inviting a user
---------------

- Click the 'Invite User' button to the top right of the users table
- Enter the new users Email Address and click 'Submit'
- If the user is already part of the :term:`portal` then they'll be added to the site and notified by email and a alert in their browser. If the user is new to the portal they will receive a email asking them to make an account

New user email links are valid for 7 days after they are invited. If the user doesn't sign up in this time their link will become invalid and will need to be re-invited to the project by selecting the users and clicking 'Re-Invite' in the toolbar.

Removing a user
---------------

- Select a user by clicking the circle to left of the users name
- Click 'Remove' in the toolbar
- Confirm the removal of the user by entering their email address 

A user that has been removed from a site will no longer be able to see the site in their 'My Sites' section of the portal. The user may still login to the portal even if they are not members of any site. To stop a user logging in see :ref:`user suspension<Suspending a user>`.

Permissions
===========

User permissions for this site alone can be managed here. For more on permissions see the permissions_ section of this documentation.

.. _permissions: Permissions.html

Settings
========

.. figure:: img/settings.png
   :align:   left

Site information
----------------

With the correct permissions this information can be in-line editted. Click on the text to be edited to open up the text editor.

- Primary Contact: The name of the contact for this site
- Primary Contact Email: The email address of the contact for this site
- Primary Contact Phone: The phone number of the contact for this site

While any information can be entered into the fields above we recommend filling them with the desired contact information.

Notes
-----

A free form notes feild for this site. With the correct permissions this can be in-line editted. Click on the text to be edited to open up the text editor.

Site location and time
----------------------

Selecting a site location is important as this setting is used to determin the sites local time for scheduled tasks. 

In a new project the map will display a random location to start with though the location is only set once a user has selected the sites actual location.

- Navigate around the map until you can see where the location of the site is
- Click on the map where the location of the site is
- If the pin looks to be correct and the address preview looks accurate click the check mark to accept that location

One a location is set the following information will be filled:

- Latitude: the latitiude of the site 
- Longitude: the longitude of the site
- Geo address: an address for the site from the lat and long above. This address doesn't need to be exactly accurate for the site to function correctly but should be as accurate as possible. This address is calcuated on the SixEye servers
- UTC offset: the calculated UTC offset of the site from the lat long
- Time zone: the calculated time zone of the site from the lat long

Notifications
-------------

Three types blah blah blah