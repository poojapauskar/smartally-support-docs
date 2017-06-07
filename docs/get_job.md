# Get Job

    GET request
    https://reimburse.herokuapp.com/get_job/?id=<pk field received after adding a job>

## Description
To get a job

***

## Output

### Success<br />
{<br />
  "status": 200,<br />
  "message": "Job Found",<br />
  "job": {<br />
    "amount": "",<br />
    "invoice_no": "",<br />
    "imageEp": "",<br />
    "name": "",<br />
    "completedBy": "",<br />
    "ocr_verified": "",<br />
    "date": "",<br />
    "pk": ,<br />
    "user_verified": "",<br />
    "user_id": "",<br />
    "status": ""<br />
  }<br />
}<br />

### If Job not present<br />
{<br />
  "status": 400,<br />
  "message": "Job Not Found",<br />
}<br />

***
