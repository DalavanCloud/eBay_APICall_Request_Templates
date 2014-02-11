This SoapUI Sample Project file is for eBay Product Services API and can be used to test Product Services API requests and responses via SoapUI tool.
REF : http://developer.ebay.com/DevZone/product/CallRef/index.html
REF : http://developer.ebay.com/DevZone/product-metadata/CallRef/index.html

The sample project file covers all supported Product Services API calls in both XML and SOAP format. It also has a 'Default' file which is directly generated from wsdl. 
The api that are "no longer supported" as per the docs are marked as "Deprectaed" in the project.

Instructions for setting up and configuring SoapUI :
1. Download the "ProductServicesAPI_SoapUI_Sample_Project.xml" project file.
2. Download soapUI from http://www.soapui.or and install it.
3. In the File menu, select 'Import Project' and import the "ProductServicesAPI_SoapUI_Sample_Project.xml" file.
4. After the project is loaded, expand the project tree and select an API call.
5. Specify your AppID in the X-EBAY-SOA-SECURITY-APPNAME head.  And you will also need to specify your 'Auth Token' in the X-EBAY-SOA-SECURITY-TOKEN header for the Product Metadata Service.
For HTTP Headers (XML API Only)  and SOAP URL Parameters (SOAP API), see here : http://developer.ebay.com/DevZone/product/Concepts/MakingACall.html 
6. Run the test.

*NOTE - Because we don't want to add invalid products to eBay, and the functionality does not work for sandbox, botht he addProducts and getProductSubmission samples will not run.  They are just there for examples.
