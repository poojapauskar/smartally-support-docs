# Update Job

    PUT request
    https://reimburse.herokuapp.com/update_job/?id=<pk field of job added>&access_token=<access token of support user>

## Description
To update a job

***

## Input Fields

**Raw Json Data**
```
{
  "name" : "Pooja",
  "amount" : 100.50,
  "user_id" : 1,
  "date" : "",
  "invoice_no" : ""
}
```   
***

## Output

**Success**
```
{
  	'status':200,
  	'message':'Job completed.',
}
```
**If job was already completed by another user**
```
{
  	'status':401,
  	'message':'Job already completed.',
}
```
**If job not found**
```
{
  	'status':400,
  	'message':'Job Not Found',
}
```
**Invalid access token**
```
{
    'status':401,
    'message':'Access Token not valid',
}
```
***
