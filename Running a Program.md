# Running a Program at System Logon 
# Case Study: Calc.exe File | Windows Registry 

#### 1. Accessing Windows Registry Through the Start Icon

- Click on the start icon on the keyboard or on the system.

- Enter 'Registry Editor' in the search colomn.

- Registry Editor App will appear, click on it.

- Alas! Here we are!!

     #####   Note that Windows Registry is the Registry Editor.



![UI Image](https://github.com/FacelessHacker/Rahmah/blob/main/pictures/Screenshot%20(10).png)

![UI Image](https://github.com/FacelessHacker/Rahmah/blob/main/pictures/Screenshot%20(11).png)


![UI Image](https://github.com/FacelessHacker/Rahmah/blob/main/pictures/Screenshot%20(12).png)


#### 2. Accessing Registry Editor Through 'regedit'

- Press the windows logo key + R .

- You will see a search colomn, enter the command 
```
regedit

```
- Click okay.

     ##### Boom!!! the Registry Editor is opened!!

![UI Image](https://github.com/FacelessHacker/Rahmah/blob/main/pictures/Image%201.png)


![UI Image](https://github.com/FacelessHacker/Rahmah/blob/main/pictures/Image2.png)


### 3. Steps to Run the Program on Registry Editor

- Click on Computer.

- Move to HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Run .

- From the Edit menu select New - String Value.

- A column will appear. 

- Enter any name you want to save it as i.e. Calc at logon .

- Double Click the new colomn/name; another column will appear called 'Value data'.

- In the Value data column, enter the path name of the programme i.e. Calc.exe .


![UI Image](https://github.com/FacelessHacker/Rahmah/blob/main/pictures/Screenshot%20(13).png)

![UI Image](https://github.com/FacelessHacker/Rahmah/blob/main/pictures/Screenshot%20(16).png)

![UI Image](https://github.com/FacelessHacker/Rahmah/blob/main/pictures/Screenshot%20(17).png)

![UI Image](https://github.com/FacelessHacker/Rahmah/blob/main/pictures/Screenshot%20(18).png)

![UI Image](https://github.com/FacelessHacker/Rahmah/blob/main/pictures/Screenshot%20(19).png)

- Click on okay.

     #### Note that 'Calc.exe' is the path name for calculator on the sample system.

- Close the Registry Editor.

     #### Restart Your System

     #### Calc.exe file (Calculator) will run immediately on system logon



