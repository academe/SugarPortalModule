SugarPortalModule
=================

A portal module for SugarCRM, allowing contacts to register and log in.

The aim of this module is to extend the REST API for SugarCRM to provide additional functions
that support the registration and authentication of Contacts. This allows SugarCRM to be used
as a self-service portal of some type (I'm using it for a job site and soon for a holiday
booking system).

Most of the functionality of a self-service portal will be in the external application.
What this module will provide is the ability to track the registration state of of Contacts
and to store encrytped passwords against the Contacts.

This module is developed against SugarCRM 6.5 CE, and the Academe/SugarRestApi library will support
the API functions that it provides.

## Repository Organisation ##

This repository contains the files required for the plugin, and the tools to wrap the files up into
an installable zip file. It may be that the whole repository can be zipped to create an installable
module with no further tools to reorganise the files, but I've not got far enough to test that yet.
