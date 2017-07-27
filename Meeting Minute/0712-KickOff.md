> 07/12(Wed)  
안윤근, 오지강, 이기찬, 이학진

# Topic: Project Kick Off Meeting

## 1. Milestone
> Refer [GitHub Wiki](https://github.com/SELab-IoT/XACML-Server/wiki#2-milestone)

## 2. Member Schedule(July)
> Refer Schedule.xlsx in Dropbox (\신진연구\Schedule.xlsx)

## 3. To Do List(July)
+ 안윤근: Balana Example bug fix, PEP Design, PDP Server Design, Decide PEP-PDP Communication Protocol, August Scheduling
+ 오용택: Write GitHub Wiki, PDP Server Design & Abstraction & Develop
+ 오지강: Arduino Study(HTTP Communication), PEP Design & Abstraction & Develop(Additional)
+ 이학진: Write GitHub Wiki, Arduino Study(HTTP Communication), PEP Design & Abstraction & Develop(Additional)

## 4. Design Decision
![Overall Deployment Diagram](https://github.com/SELab-IoT/IoT-Documents/blob/master/Diagrams/Deployment%20Diagram/overall.png?raw=true)
+ First of all, user application will be developed later.
+ So, in PEP, XACML Request/Converter have to be modularized.
+ Enforcer is just temporary one. 
+ Just implement simple user input/output and enforce user to use external entities.
+ Enforcer will be replaced with user application.
+ PEP-PDP Communication will be formed with HTTP.
+ PEP-PDP Message Protocol will be decided by 안윤근.

## 5. Next Meeting
> 7/19(Wed) or 7/21(Fri) (Tentative)
