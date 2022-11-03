### Set up Serenity Framework and automate a get call.

### API Doc : https://petstore.swagger.io/



### Sample Request :  https://petstore.swagger.io/v2/pet/findByStatus?status=available



## Test Cases.

 ### 1) Verify status code is 200. 

 ### 2) Verify  status of all pets is "available" in the response body.

 ###      Verify number of pets returned is greater than 5. Log how many pets are returned by the response. 

 ###  3) Verify content type and access-control-allow-methods in response header.

 ###  4) Add a failureTest to verify status code is 404.

 ### Run maven command , generate serenity report with 4 test cases. 3 Success and 1 Failed.







﻿
