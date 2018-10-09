Pre requisite: Postman tool is installed.
Test suite: A sample API test suite framework to test CRUD
It will call webservice https://reqres.in
This webserver has few users already created. It is a dummy API which doesn't actually delete/update users. It exposes various requests including GET, PUT, POST, DELETE requests
	POST: Create user
	GET: To read a already created user
	PUT: To update any parameter of a user
	DEL: To delete a user

Execution steps:
Start postman tool
Import the code: Go to File->import->choose files
click on API tests to execute the test cases:
	Click on run(play button)
	Specify number of iterations
	Run API tests

The franework will execute the test cases and result will have:
	Number of Pass/ failed TCs
	Time taken to execute the test cases
	Logs are created.