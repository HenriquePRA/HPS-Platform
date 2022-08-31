# Hybrid-Polymorphic Spring Platform

This project is being created with the sole purpose of being modified into my final project for the __Programing For Web II__ university discipline, i should   make this project at the beginning of the semester (this september) and when the final project requirements become public i will easily modify it and grant an easy 100 points.
<br />
<img src="https://c.tenor.com/gKpWG8u-u2QAAAAi/evil-evil-pepe.gif" style="float: left; margin-right: 10px;" />

### At the front-end uses:

 - Thymeleaf
 - Bootstrap
 
### At the back-end uses:

  - Docker containers
  - Spring
  - Postgres
  - An appropriated design pattern (Only on the announced project)
    
    <strong>_specificaly in spring_</strong>
 
  - Controllers and Models
  - Redirect and Flash
  - Spring data JPA
  - HTTP Sessions
  - Authentication and Authorization
  
### Also has the functional requirements:
 
  - Type 1 objects to be composed by one or many Type 2 objects(1-*)
  
  - Users can signup via Thymeleaf form
  
  - Users can create and modify Type 1 Objects
  
  - Users can create and modify Message Objects to other users and administrators
   <br /><strong>_a message can only be modified within a maximum of 5 minutes after its creation_</strong>
  
  - Users can block Messages from other users
  
  - Message objects can be modified at the maximum of 5 minutes from its creation
    
  - Administrator modification page that allows administrators to create, modify and delete Type 2 objects 
  <br /><strong>_Requires Authentication and the option to create and modify Type 2 Objects, should only appear to tier 3 administrators_</strong>
  <br /><strong>_Requires Authentication and the option to delete Type 2 Objects, should only appear to tier 2 administrators_</strong>
  
  - Administrator user management page that allows the administrator to modify and delete users and other administrators
  <br /><strong>_(Requires Authentication and Tier 1 Authorization)_</strong>
  
  - when a user is deleted all Type 1 Objects associated to him should recursively deleted by a trigger.
  
  - when a Type 2 object is deleted it should be recursively removed from all the Type 1 objects that it composes
  
