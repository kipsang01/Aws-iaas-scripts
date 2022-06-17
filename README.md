# AWS CLOUDFORMATION SCRIPT

## Description
This repository contains scripts for launching web servers in Aws in two availability zones that ensures availbility and scalability.

# How To Run
* Clone the repository and run the create.sh shell script starting with solution scripts passing in environment variables i.e
 ```
./create.sh <name_of_application> solution.yml solution-parameters.json <region> <cli profile>
```
* Then followed by server scripts that ensures security of servers
 ```
  ./create.sh <name_of_application> servers.yml servers-parameters.json <region> <cli profile>
  ```
* "update.sh" is used to update stacks whenever there are changes in scripts to be effected e.g
 ```
./update.sh <name_of_application> solution.yml solution-parameters.json <region> <cli profile>
```
  
# Temporary live link  
  http://udagr-webap-wo665amgsqxf-256431030.us-east-1.elb.amazonaws.com/
