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

