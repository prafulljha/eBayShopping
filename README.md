eBayShopping
============

A mini-application to demo how you can leverage eBay Web Services to find items off eBay listings.

This application shows how to use the eBay Shopping API to perform searches using the FindItemsAdvanced call. 

Note: This codebase uses the jQuery JavaScript library (http://jquery.com/) which is a free, open source software dual-licensed under the MIT License and the GNU General Public License. 

Software Requirements:
----------------------
- Tomcat 5.x / 6.x 
- JDK 1.5 or above


How to run this sample:
-----------------------

- Deploy this application in your local Tomcat Server

- Next, you will need to enter your Application ID (APP_ID) obtained from eBay into the "FindItemsAdvanced/WEB-INF/classes/com/ebay/shopping/search/config.properties" file in the tomcat webapps directory. You will also need to set the URL of the server (ENDPOINT_URL) you wish to use (Sandbox or Production), in the same file. 

- Start Tomcat server if it is not running already.

- Enter URL in this form in the browser : http://servername:port/FindItemsAdvanced/FindItemsAdvanced.jsp (replace servername:port appropriately according to your Tomcat configuration. For default Tomcat installation in your localhost, the URL will most likely be http://localhost:8080/FindItemsAdvanced/FindItemsAdvanced.jsp)

- Search eBay listings by providing inputs for "Query Keyword", "Site to Search" and "No. of Items"
