# Post Job

    POST request
    https://reimburse.herokuapp.com/ocr/

## Description
To post a job

***

## Input Fields

Raw Json Data<br />
{<br />
    "imageEp" : image url string,<br />
    "coordinates" : {<br />
          "name" : {<br />
               "x" : 124,<br />
               "y" : 85,<br />
               "w" : 68,<br />
               "h" : 7<br />
          },<br />
          "amount" : {<br />
               "x" : 201,<br />
               "y" : 254,<br />
               "w" : 55,<br />
               "h" : 5<br />
          }<br />
    }<br />
}<br />
    
***

## Output

Success<br />
{<br />
  "status": 200,<br />
  "message": "Job Saved",<br />
  "job": {<br />
    "amount": "",<br />
    "invoice_no": "",<br />
    "imageEp": "",<br />
    "name": "",<br />
    "completedBy": "",<br />
    "ocr_verified": "1",<br />
    "date": "",<br />
    "pk": ,<br />
    "user_verified": "",<br />
    "user_id": "",<br />
    "status": ""<br />
  }<br />
}<br />

***
