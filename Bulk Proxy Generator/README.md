# Master-Works Apigee-Tools
This Tool Is Designed to Rapidly Wrap the current Customer Set Of API's to a mapped set of Apigee proxies


Procedure :
============
Assuming that customer has a list of all of available api's in an excel file with the following info  :
1- BasePath
2- Path
3- Target Endpoint URL
4- Include Verify API Key -- If Yes The Generated proxy will be secured with Verify_API_key  Policy
5- Include OAuth
6- Include Assign Message Policy ( To Modify Request as per the back end requirements )
... any Other useful policy common attribute

The Tool Will Read this excel file and uses Management API to create the required policies.

By This Tool Master_Works will be able to Demonstrate it ability to rapidly apply all the Apigee benefits to the prospective customer
