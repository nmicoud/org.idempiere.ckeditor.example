Example of a plugin for https://idempiere.atlassian.net/browse/IDEMPIERE-6953

To test, import the plugins/fragment to your project in Eclipse.

Make sure to use it when lauching the server (org.idempiere.ckeditor.example must be ticked in your launcher)

Launch iDempiere

Make sure those 2 System Configurator entries are present with correct values to config files:
* CKEDITOR_FILE_CONFIG : /js/ckeditor/myConfig.js
* CKEDITOR_FILE_CONFIG_MIN : /js/ckeditor/myConfig-min.js
