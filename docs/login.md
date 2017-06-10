# Login

    POST request
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
  	"user_details": {
         "username": "pooja",
         "pk": 1,
         "password": "pooja123"
    }
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
