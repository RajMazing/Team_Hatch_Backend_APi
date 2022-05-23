# Team_Hatch_Backend_APi

-A simple backend API that returns a json on the server


**Installing / Getting started**



 npm install
 npm start
 then the local the server will run on PORT 8000.





**Description**



The link http://localhost:8000/api/solution/posts?tag=tech displays a json handled by an axios.get() with query parameters set to tag and the value to "tech", this request is then directed to a route http://localhost:8000/api/solution/posts. This json should display all the objects with the value of "tech" inside of the tag paramter. When the tag parameter is incorrect or doesn't exist then an error message will render on the page.





**Built With**

Javascript, express, axios



**Prerequisites**

express
axios
body-parser
cors
nodemon




**Tests**

Postman

-Used the api testing platform to run the server to see if the api receives the correct json data. 

