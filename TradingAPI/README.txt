This SoapUI Sample Project file is for eBay Trading API and can be used to test Trading API requests and responses via SoapUI tool.
REF : http://developer.ebay.com/devzone/xml/docs/reference/ebay/

The sample project file covers all supported Trading API calls in both XML and SOAP format. It also has a 'Default' file which is directly generated from wsdl. 
The api that are "no longer supported" as per the docs are marked as "Deprectaed" in the project.

Instructions for setting up and configuring SoapUI :
1. Download the "TradingAPI_SoapUI_Sample_Project.xml" project file.
2. Download soapUI from http://www.soapui.org/ or and install it.
3. In the File menu, select 'Import Project' and import the "TradingAPI_SoapUI_Sample_Project.xml" file.
4. After the project is loaded, expand the project tree and select an API call.
5. Specify your 'Auth Token' in the <eBayAuthToken> tag for the format (XML or Soap) of interest.
For HTTP Headers (XML API Only)  and SOAP URL Parameters (SOAP API), see here : http://developer.ebay.com/DevZone/XML/docs/WebHelp/InvokingWebServices-Routing_the_Request_(Gateway_URLs).html
6. Run the test.

