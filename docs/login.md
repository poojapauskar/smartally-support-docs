# Login

    GET request
    https://reimburse.herokuapp.com/support_login/ 

## Description
To login a user

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

**Success**
```
{
  	'status':200,
  	'message':'Login successful.',
  	'user id':,
}
```
**If user not present**
```
{
  	'status':400,
  	'message':'User not found',
}
```
***
