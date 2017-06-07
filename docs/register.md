# Register

    POST request
    https://reimburse.herokuapp.com/support_register/

## Description
To register a user

***

## Input Fields

Raw Json Data<br />
{<br />
 	"username" : "",<br />
 	"password" : ""<br />
}
    
***

## Output

Success<br />
{<br />
  	'status':200,<br />
  	'message':'Registration Complete',<br />
}<br />

If username already exists<br />
{<br />
  	'status':400,<br />
  	'message':'Username exists',<br />
}

***
