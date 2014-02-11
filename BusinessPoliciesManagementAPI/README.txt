This SoapUI Sample Project file is for eBay Business Policies Management API and can be used to test Business Policies Management API requests and responses via SoapUI tool.
REF : http://developer.ebay.com/Devzone/business-policies/CallRef/index.html

The sample project file covers all supported Business Policies Management API calls in both XML and SOAP format. It also has a 'Default' file which is directly generated from wsdl. 
The api that are "no longer supported" as per the docs are marked as "Deprectaed" in the project.

Instructions for setting up and configuring SoapUI :
1. Download the "BusinessPoliciesManagementAPI_SoapUI_Sample_Project.xml" project file.
2. Download soapUI from http://www.soapui.or and install it.
3. In the File menu, select 'Import Project' and import the "BusinessPoliciesManagementAPI_SoapUI_Sample_Project.xml" file.
4. After the project is loaded, expand the project tree and select an API call.
5. Specify your 'Auth Token' in the X-EBAY-SOA-SECURITY-TOKEN header for the format (XML or Soap) of interest.
For HTTP Headers (XML API Only)  and SOAP URL Parameters (SOAP API), see here : http://developer.ebay.com/Devzone/business-policies/Concepts/MakingACall.html
6. Run the test.
