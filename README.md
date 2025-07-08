# API Testing  
1. In accordance with the Swagger documentation at https://qa.demoshopping.ru/api-docs/, I created a collection for the "Online Store" project at https://demoshopping.ru/. All methods have been documented in Postman, and environment variables that are frequently reused — such as the base URL and token — have been created.

      1.1. The collection I created in JSON format  
      https://github.com/VolhaPiatrova/api/blob/main/DemoShopping.postman_collection.json  
      The public collection in my Postman workspace (for the Product module, I have written automated tests that can verify the following: the status code after sending a request, the response body (including data type checks), and changes to keys and values for POST requests).  
      https://www.postman.com/technical-administrator-59540941/workspace/my-test-course-workspace/folder/43040118-b8828583-47cd-48e1-81b2-a8ab23ead686?action=share&creator=43040118&ctx=documentation&active-environment=43040118-54efc7ee-b569-479f-8b97-8d66e66d4872
   
      1.2. Test cases for API (data was imported from the Qase system where i originally created it, methods i used:  GET, POST, PUT, PATCH, DELETE)  
      https://github.com/VolhaPiatrova/api/blob/main/TestCasesAPI.pdf

      1.3. The created tests were run using the Run Collection function, and the test results were exported in JSON format.  
   https://github.com/VolhaPiatrova/api/blob/main/DemoShopping.postman_test_run.json

2. Testing of requests for Country info service using the SOAP protocol was performed in Postman. The work was based on the WSDL file available at: http://webservices.oorsprong.org/websamples.countryinfo/CountryInfoService.wso?WSDL.

      2.1. The collection I created in JSON format  
      https://github.com/VolhaPiatrova/api/blob/main/SOAP%20Country%20info%20service.postman_collection.json

      2.2  The public collection in my Postman workspace  
      https://www.postman.com/technical-administrator-59540941/workspace/my-test-course-workspace/collection/43040118-e1a36ebe-c2d3-4bf7-af7e-41136163bef1?action=share&creator=43040118&active-environment=43040118-54efc7ee-b569-479f-8b97-8d66e66d4872
   
