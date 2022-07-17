# Postman_API_Tests
Only a tiny part of the API tests that I write in Postman at my job

Test examples

Creating environment variables for the WS collection API.

Includes getting {{host_ru}} for the request
Enables {{ws_name}} for query parameters of the GET request
Enables {{TOKEN}} for Auth. I send POST request to authoriz, get Bearer Token and use in inside the GET-request


In tests, I use checking:
1) For the response code from the server (HTTP 200 in positive scenarious),
2) Validating the JSON schema
3) Checking that in the search for the task in the JSON response, the name parameter contains the desired name {{ws_name}}
4) I get 2 arrays and compare them with each other, thereby I check that all task id are completed.( Not executed and not stuck)
![image](https://user-images.githubusercontent.com/57834199/179416983-6914852a-4fb4-421a-89c4-0dfc3062e1d3.png)

The screenshot below shows a run of tests that they work

![image](https://user-images.githubusercontent.com/57834199/179416967-3c1d13c2-3a36-4786-9fb6-ec5f4d9a9242.png)
