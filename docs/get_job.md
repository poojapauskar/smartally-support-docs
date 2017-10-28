# Get Job

    GET request
    https://reimburse.herokuapp.com/get_job/?id=<pk field received after adding a job>&access_token=<user access token>

## Description
To get a job

***

## Output

**Success**
```
{
  "status": 200,
  "message": "Job Found",
  "job": {
    "amount": "",
    "invoice_no": "",
    "imageEp": "",
    "name": "",
    "completedBy": "",
    "ocr_verified": "",
    "date": "",
    "pk": ,
    "user_verified": "",
    "user_id": "",
    "status": ""
  }
}
```
**If Job not present**
```
{
  "status": 400,
  "message": "Job Not Found",
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
