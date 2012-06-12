Salesforce-GoogleMaps-3
=======================

Force.com Labs released a great app for Salesforce to embed Google Maps, called [GoogleMapsInternational][0]. Since it was released, Google Maps has updated its API to version 3.  This repo contains the code you need to update Salesforce to match it.

 [0]: http://appexchange.salesforce.com/reviews?listingId=a0N300000016d25EAA

Here are the instructions:

 1. Install GoogleMapsInternational from the link above.
 1. Replace `GoogleMapsInternational.component` with the file in this repository.
 1. Find and download the Static Resource called GoogleMapsInternational	 within Salesforce.  Open it up, replace `googleMapsInternational.js` with the file in this repository, and reupload it.
 1. In Salesforce, go to Setup > Create > Custom Labels.  Find the label named `GMI_googleMapURL` and change its value to `https://maps.google.com`.
 1. That's it!
