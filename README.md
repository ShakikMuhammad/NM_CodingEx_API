# NM_CodingEx_API

Instructions

1.	API Automation:
I.	Project Summary: 
-	Create collection file from the given site by making GET, POST, PUT, and DELETE calls. 
-	Set the body for requests.
-	Used random data generators and reused them while making calls by storing them in environment variables.
-	Asserted responses from the requests made.
-	Run the collection using command
-	Generated report in htmlextra 

II.	Pre prerequisite

i.	GitHub account
ii.	Git configured with your system
iii.	Installation
1.	Postman API
2.	npm
3.	Node
4.	newman
5.	htmlextra reporter

III.	How to run the project:

i.	Go to the link: https://github.com/Shakik-M/NM_CodingEx_API 
ii.	Clone it to local machine
iii.	Go to the cloned folder
iv.	Open POSTMAN
v.	import the environment and collection files from the cloned folder
vi.	Go to the collection file “NM_CodingEx_API”
vii.	Select environment “jsonplaceholderEnv”.
viii.	You can send the request separately opening each request OR
ix.	Run the collection by clicking “Run”
x.	See the results in the next window

To run the collection & generate report in htmlextra by command: 
xi.	Open Terminal/Cmd
xii.	Go to cloned folder using command “cd”
xiii.	Run any of the following command:

newman run NM_CodingEx_API.postman_collection.json -e jsonplaceholderEnv.postman_environment.json -r htmlextra

xiv.	The test will start running and the terminal will show the run progress like the following screenshot.

 

xv.	Go to cloned folder/ NM_CodeChallenge/NM_CodingEx_API/newman
xvi.	Open the .html file in any browser
xvii.	You will see the Newman Run Dashboard like the screenshot in following page:

![image](https://github.com/ShakikMuhammad/NM_CodingEx_API/assets/96020266/1360f283-5f6b-4d39-8ea9-939532289b51)




 
