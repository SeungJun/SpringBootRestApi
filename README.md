# SpringBootRestApi
organized by SpringBoot. Develope for Rest Api. It includes get, post, put, delete http method

you can use the blow following api's uri for restful function 

GET : 
 -- http://localhost:8080/SpringBootRestApi/api/user/
  >> select all user's list 
   
 -- http://localhost:8080/SpringBootRestApi/api/user/{number}
  >> select one user
   
POST : following uri is create function   
 -- http://localhost:8080/SpringBootRestApi/api/user/save/
  >> create new user 
  http request body's raw payload is like below 
  { 
    "name" : "SeungJun"
    "age" : "30"
    "salary" : "3900"
   }

PUT : next uri id update function 
 -- http://localhost:8080/SpringBootRestApi/api/user/save/{number}
  >> update user's data 
    { 
      "name" : "SeungJun"
      "age" : "31"
      "salary" : "1900"
     }
     
DELETE : delete function
  -- http://localhost:8080/SpringBootRestApi/api/user/{number} 
  >> delete one user 
  
  -- http://localhost:8080/SpringBootRestApi/api/user/
  >> delete all users 