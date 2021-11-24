# TEST PLAN:
## Table no: High level test plan
|Test ID|	Description|	Exp I/P|	Exp O/P|	Actual Output|	Type Of Test|
|-------|------------|---------|---------|---------------|--------------|
|H_01	|Adding Medicine Record|	"Add_1", "mname", "1234", "1234", "cname", "12-12-1234",| "12-12-1234"	"Add_1", "mname", "1234", "1234", "cname", "12-12-1234", "12-12-1234|"Add_1", "mname", "1234", "1234", "cname", "12-12-1234", "12-12-1234"|	Requirement based|
|H_02	|Modify Medicine Record|	"Modify1"	|"Modify_1", "mname", "1234", "1234", "cname", "12-12-1234", "12-12-1234"|	"Modify_1", "mname", "1234", "1234", "cname", "12-12-1234", "12-12-1234"|	Scenario based|
|H_03	|Delete Medicine Record|	"Delete_1"|	-DEL--------NAM---	|-DEL---------NAM----|	Boundary based|
## Table no: Low level test plan
|Test ID|	Description|	Exp I/P|	Exp O/P|	Actual Output|	Type Of Test|
|-------|------------|---------|---------|---------------|--------------|
|L_01|	Search Medicine Record|"Search_1"|"Search_1", "mname", "1234", "1234", "cname", "12-12-1234", "12-12-1234"|	"Search_1", "mname", "1234", "1234", "cname", "12-12-1234", "12-12-1234"|	Requirement based|
|L_02|	Display Medicine Record|	"Displat_Output"| Records| Records|	Scenario based|


# Output

## Add Medicine

![AddMedicine](https://user-images.githubusercontent.com/94336423/143300500-20244f48-887a-4454-bc54-807b48ae6973.jpg)


## Searching And Deleting Medicine

![SearchDelete](https://user-images.githubusercontent.com/94336423/143300739-ed40ecdd-07e6-402b-b1d3-3b05e686c2a1.jpg)


## Modifying Medicine

![Modify](https://user-images.githubusercontent.com/94336423/143300838-0f595d82-4b7f-4cd2-a89a-5d57845628c9.jpg)


## Display Medicine

![Display](https://user-images.githubusercontent.com/94336423/143300949-f8483144-e73c-4176-9c48-3cdf30df5d24.jpg)



