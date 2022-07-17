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


The screenshots below shows a run of tests that they work

![image](https://user-images.githubusercontent.com/57834199/179417176-4c488049-04f7-49c8-b41b-76f621d96b11.png)
![image](https://user-images.githubusercontent.com/57834199/179417311-5184bf30-9e6d-460a-b4aa-6fcf5fb4f371.png)

