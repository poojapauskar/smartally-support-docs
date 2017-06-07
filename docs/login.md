# Login

    GET request
    https://reimburse.herokuapp.com/support_login/ 

## Description
To login a user

***

## Input Fields

Raw Json Data<br />
{<br />
 	"username" : "",<br />
 	"password" : ""<br />
}
    
***

Success<br />
{<br />
  	'status':200,<br />
  	'message':'Login successful.',<br />
  	'user id':,<br />
}<br />

If user not present<br />
{<br />
  	'status':400,<br />
  	'message':'User not found',<br />
}

***
