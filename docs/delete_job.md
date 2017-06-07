# Delete Job

    DELETE request
    https://reimburse.herokuapp.com/delete_job/?id=<pk field received after adding a job>

## Description
To delete a job

***

## Output

### Success<br />
{<br />
  "status": 200,<br />
  "message": "Job removed",<br />
}<br />

### If Job not present<br />
{<br />
  "status": 400,<br />
  "message": "Job Not Found",<br />
}<br />

***
