# Postman_API_Tests
Only a tiny part of the API tests that I write in Postman at my job

Test examples<br />

Creating environment variables for the WS collection API.<br />

Includes getting __{{host_ru}}__ for the request host in URL<br />
Enables __{{ws_name}}__ and __{{q}}__ for query parameters of the GET request<br />
Enables __{{TOKEN}}__ for Auth. I send POST request to authoriz, get Bearer Token and use in inside the GET-request<br />
Use variables in CSV and JSON files. <br />
Use variables from a CSV file in GET/POST requests<br />


In tests, I use checking:<br />
1) For the response code from the server (***HTTP 200 in positive scenarious***),<br />
2) Validating the JSON schema<br />
3) Checking that in the search for the task in the JSON response, the name parameter contains the desired name __{{ws_name}}__<br />
4) I get 2 arrays and compare them with each other, thereby I check that all task id are completed. __(Not executed and not stuck)__<br />


The screenshots below shows a run of tests that they work

![image](https://user-images.githubusercontent.com/57834199/179417176-4c488049-04f7-49c8-b41b-76f621d96b11.png)
![image](https://user-images.githubusercontent.com/57834199/179417311-5184bf30-9e6d-460a-b4aa-6fcf5fb4f371.png)

Runned all collection with info:

![image](https://user-images.githubusercontent.com/57834199/179417481-68e7cc48-f892-4942-bf20-3d3ca9b6e05d.png)
