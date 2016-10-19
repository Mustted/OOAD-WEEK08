# OOAD-WEEK08 HOMEWORK
## USE CASE DIAGRAM
  Use case1
  Code
```
@startuml
title User <b>Using</b>\nTelephone

"Using Telephone" as (Use)
User -> (Use)

@enduml
```
<img src="https://github.com/Mustted/OOAD-WEEK08/blob/master/Homework/Use%20case%201.png?raw=true">

  Use Case2
  Code
  ```
  @startuml
left to right direction
skinparam packageStyle rect
actor Waiter
rectangle Restaurant {
  (Select) .> (payment) : include
  (Select) -- Waiter
}
@enduml
```
<img src="https://github.com/Mustted/OOAD-WEEK08/blob/master/Homework/Use%20case2.png?raw=true">
  Use case3
  Code
  ```
  @startuml

left to right direction
Admin --> (User1)
Admin --> (User2)
Admin --> (User3)
@enduml
```
<img src="https://github.com/Mustted/OOAD-WEEK08/blob/master/Homework/Use%20case3.png?raw=true">
