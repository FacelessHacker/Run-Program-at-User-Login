# Practical A

## Running a Program at System Logon Using Windows Registry

## Case Study: Calc.exe File 

## Accessing Windows Registry Through the Start Icon

- Click on the start icon on the keyboard or on the system

![UI Image](https://github.com/FacelessHacker/Rahmah/blob/main/Screenshot%20(10).png)


- Enter 'Registry Editor' in the search colomn.

![UI Image](https://github.com/FacelessHacker/Rahmah/blob/main/Screenshot%20(11).png)

- Registry Editor App will appear, click on it.

- Alas! Here we are!!

![UI Image](https://github.com/FacelessHacker/Rahmah/blob/main/Screenshot%20(12).png)

### Note that Windows Registry is the Registry Editor.




## Accessing Registry Editor Through 'regedit'

- Press the windows logo key + R .

- You will see a search colomn, enter the command 
```
regedit

```
- Click okay.


![UI Image](https://github.com/FacelessHacker/Rahmah/blob/main/Image%201.png)

_Boom!!! the Registry Editor is opened!!

![UI Image](https://github.com/FacelessHacker/Rahmah/blob/main/Image2.png)


## Steps to Run the Program on Registry Editor

- Click on Computer

![UI Image](https://github.com/FacelessHacker/Rahmah/blob/main/Screenshot%20(13).png)

- Move to HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Run .

![UI Image](https://github.com/FacelessHacker/Rahmah/blob/main/Screenshot%20(16).png)

- From the Edit menu select New - String Value.

![UI Image](https://github.com/FacelessHacker/Rahmah/blob/main/Screenshot%20(17).png)

- A column will appear 

![UI Image](https://github.com/FacelessHacker/Rahmah/blob/main/Screenshot%20(18).png)

- Enter any name you want to save it as i.e. Calc at logon .

- Double Click the new colomn/name; another column will appear called 'Value data'

- In the Value data column, enter the path name of the programme i.e. Calc.exe

![UI Image](https://github.com/FacelessHacker/Rahmah/blob/main/Screenshot%20(19).png)

- Click on okay

#### Note that 'Calc.exe' is the path name for calculator on the sample system

- Close the Registry Editor

### Restart Your System

### Calc.exe file (Calculator) will run immediately on system logon


### Graphical Representation of the above steps


