# Delete Job

    DELETE request
    https://reimburse.herokuapp.com/delete_job/?id=<pk field received after adding a job>&access_token=<user access token>

## Description
To delete a job

***

## Output

**Success**
```
{
  "status": 200,
  "message": "Job removed",
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
