# Get Incomplete Jobs

    GET request
    https://reimburse.herokuapp.com/get_incomplete_jobs/

## Description
To get all incomplete jobs in last 30 minutes

***

## Output

**Success**
```
{
  "status": 200,
  "message": "Jobs found.",
  "jobs": [
    {
      "status": "",
      "user_id": "",
      "name": "",
      "created": "",
      "ocr_verified": "1",
      "imageEp": "",
      "amount": "",
      "completedBy": "",
      "date": "",
      "pk": 10,
      "invoice_no": "",
      "user_verified": ""
    }
  ]
}
```
**If Job not present**
```
{
  "status": 400,
  "message": "No jobs in last half hour."
}
```
***
