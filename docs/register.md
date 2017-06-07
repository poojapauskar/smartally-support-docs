# Register

    POST request
    https://reimburse.herokuapp.com/support_register/

## Description
To register a user

***

## Input Fields

**Raw Json Data**
```
{
 	"username" : "",
 	"password" : ""
}
```   
***

## Output

**Success**
```
{
  	'status':200,
  	'message':'Registration Complete',
}
```
**If username already exists**
```
{
  	'status':400,
  	'message':'Username exists',
}
```
***
