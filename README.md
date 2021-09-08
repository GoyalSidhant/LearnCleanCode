# LearnCleanCode

Clean Architecture Cone 

entities -> use case -> controller -> External Interface 

Rest API(entry Point) ->  Entities & Use Case (Core) -> Database File System Network Devices (Data Points)

core == business Logic 

* effective testing 
* Always ready to deploy 


## Entities 
* Rep domain object 
* Plain object(POJO)
* Apply logic applicable to whole whole entity 

## Use Case 
* Business Action 
* pure BL 
* throws business expectations

## Interface/Adapters 
* Retrieves and Store data 
* Implements interface defined by the use case 
* Interact with application
* eg. Controller for MVC 
## External Interface 
* appropriate Framework 

### All layers r dependent on core layers not visa versa  


In Nutshell Clean Architecture is : 
* DB agnostic   
* client interface agnostic 
* framework agnostic 


### Basic Principles
* independent of framework 
* testable 
* independent of UI 
* independent of DB 
* independent of any external agency 


Outer most circle is called mechanism 

Inner circles r called policies

## Source code dependency can only point inwards 

# 12 Factor App

for SaaS 
* One codebase tracked in revision control, many deploys
* Explicitly declare and isolate dependencies
* Store config in the environment
* Treat backing services as attached resources
* Strictly separate build and run stages
* Execute the app as one or more stateless processes
* Export services via port binding
* Scale out via the process model
* Maximize robustness with fast startup and graceful shutdown
* Keep development, staging, and production as similar as possible
* Treat logs as event streams
* Run admin/management tasks as one-off processes









