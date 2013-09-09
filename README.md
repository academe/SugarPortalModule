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
