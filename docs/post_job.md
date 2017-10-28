# Post Job

    POST request
    https://reimburse.herokuapp.com/ocr/?access_token=<user access token>

## Description
To post a job

***

## Input Fields

**Raw Json Data**
```
{
    "imageEp" : image url string,
    "coordinates" : {
          "name" : {
               "x" : 124,
               "y" : 85,
               "w" : 68,
               "h" : 7
          },
          "amount" : {
               "x" : 201,
               "y" : 254,
               "w" : 55,
               "h" : 5
          }
    }
}
```   
***

## Output

**Success**
```
{
  "status": 200,
  "message": "Job Saved",
  "job": {
    "amount": "",
    "invoice_no": "",
    "imageEp": "",
    "name": "",
    "completedBy": "",
    "ocr_verified": "1",
    "date": "",
    "pk": ,
    "user_verified": "",
    "user_id": "",
    "status": ""
  }
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
