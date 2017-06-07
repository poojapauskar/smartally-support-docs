# Update Job

    PUT request
    https://reimburse.herokuapp.com/update_job/?id=<pk field of job added>

## Description
To update a job

***

## Input Fields

Raw Json Data<br />
{<br />
  "name" : "Pooja",<br />
  "amount" : 100.50,<br />
  "user_id" : 1<br />
}
    
***

## Output

Success<br />
{<br />
  	'status':200,<br />
  	'message':'Job completed.',<br />
}<br />

If job was already completed by another user<br />
{<br />
  	'status':401,<br />
  	'message':'Job already completed.',<br />
}<br />

If job not found<br />
{<br />
  	'status':400,<br />
  	'message':'Job Not Found',<br />
}

***
