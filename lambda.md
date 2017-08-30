# lambda

### serverless

- no server is easier to manage than no server at all - werner vogels
- outsourcing your computer to focus on app

### lambda

- function as a service tool
- no persistent state
- nodejs, python

EVENT - respoding to the event
CONTEXT - processing
CALLBACK - returning outcome of function 

Process/Workflow

- event
- function receives event, process
- return output

### Lab 1 - Hello World

hello world python
create lambda through console
need to provide lambda an IAM role so it can access resources needed to process
role is like a job title or hat that you give your function
common way to name roles is based on the job its doing, e.g. imageProcessingRole
role can have many policies, policies are statements, e.g. allow, action, resource

### Lab 2 - CSV from S3

