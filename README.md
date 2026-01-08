Creating Organizational Unit (OU)
In Active Directory,
Create Secuty Group, 
Create new User 

Project Overview:
I will create an organizational unit (OU) on Active Directory Domain Services and name the OU HR department. Inside the HR department, I will create the first user in the HR OU, User John Doe, as the first user in that department. Inside the HR organizational unit, or OU, I will create a security group for the HR department and add the new John Doe as a member of the security group for the HR department.

Operating System 
Windows Server 2025 
Client Computer
Windows 11 Professional


1.	Login to the domain controller windows server 2025 

<img width="1113" height="749" alt="image" src="https://github.com/user-attachments/assets/26d2ccbb-9eb0-46db-80ac-cd88db00164b" />

2.	Click on start on the server > click on Server manager > tools > active Directory and Domain Services

	<img width="1203" height="738" alt="image" src="https://github.com/user-attachments/assets/7d6b3813-dba0-4e83-9e8a-0b867daf5611" />

3.	On active directory users and computers select Syscom.local  > right click > new > organizational Unit

   <img width="1181" height="919" alt="image" src="https://github.com/user-attachments/assets/a1b0b6da-f88e-4147-8cfd-a784042c1d41" />

   4.	Name the organizational unit “HR Department” > check the box protect container from accidental deletion > click on OK

<img width="1117" height="725" alt="image" src="https://github.com/user-attachments/assets/91e57250-0fd6-4454-9893-5f63d3f93fb6" />

      
5.	Create new user John Doe. Right click on the HR OU department > New > User

<img width="1088" height="647" alt="image" src="https://github.com/user-attachments/assets/c9512443-b322-4e85-95c2-19f1c1cb199f" />

6.	Fill out the User information first name: John, Last Name: Doe,  Username jodoe, click on next, and click on finish.

   <img width="773" height="664" alt="image" src="https://github.com/user-attachments/assets/1bb9ca26-2b03-4c06-a472-c22f153265aa" />

  
7.	Set a password UHBggdnnf*@# for the user and click Next, and click on Finish 
 
<img width="855" height="698" alt="image" src="https://github.com/user-attachments/assets/9e34e393-ce4f-47de-97cc-ddcf0fbe16a7" />


8.	The result below shows that the new user was successfully created

<img width="975" height="688" alt="image" src="https://github.com/user-attachments/assets/bd707aad-65e5-4e59-b5dc-2b912c432365" />

9.	Creating a  group for the HR department. Right click on HR Department > new >  name the group HR dept > click on OK

    
<img width="975" height="664" alt="image" src="https://github.com/user-attachments/assets/afbcc049-e508-4598-87b9-a12b1577c445" />

<img width="808" height="517" alt="image" src="https://github.com/user-attachments/assets/29bda121-ac36-495e-8b3e-9e99519bdb5f" />

10.	Adding john Doe as member of the HR dept group. Right click on HRDept > properties

    <img width="1091" height="784" alt="image" src="https://github.com/user-attachments/assets/77e1f589-0570-454c-bca3-23c4b82151e9" />

    11.	Click on the members tab > add > type the user “John” > click on check names > click on OK

        <img width="1108" height="779" alt="image" src="https://github.com/user-attachments/assets/ef0921d4-8123-4c7d-9955-97126800c2ca" />

        12.	Click on apply > OK

            <img width="816" height="688" alt="image" src="https://github.com/user-attachments/assets/e1378f97-484e-4198-8d3e-dbcc91d8b51f" />

            
13.	Test login user John Doe on the Client Windows 11 Virtual machine with username jodoe and password. Username: jodoe Password: UHBggdnnf*@#

    <img width="975" height="623" alt="image" src="https://github.com/user-attachments/assets/91945c69-3014-4fb1-879d-bece62d5d4fb" />

    










   


   














