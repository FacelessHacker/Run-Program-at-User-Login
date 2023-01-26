# Practical A

### Running a Program at System Logon for Persistency using Windows Registry

### Case Study: Calc.exe File 

##### Accessing Windows Registry Through the Start Icon

- Click on the start icon on the keyboard or on the system

- Enter 'Registry Editor' in the search colomn.

- Registry Editor App will appear, click on it.

- Alas! Here we are!!

- Note that Windows Registry is the Registry Editor.



##### Accessing Registry Editor Through 'regedit'
- Press the windows logo key + R .

- You will see a search colomn, enter the command 
```
regedit

```
- Click okay.


![UI Image](https://github.com/FacelessHacker/Rahmah/blob/main/Image%201.png)

- Boom!!! the Registry Editor is opened!!




##### Steps to Run the Program on Registry Editor
- Click on Computer
- Move to HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Run .
- From the Edit menu select New - String Value.
- A column will appear 
- Enter any name you want to save it as i.e. Calc at logon .
- Double Click the new colomn/name; another column will appear called 'Value data'
- In the Value data column, enter the path name of the programme i.e. Calc.exe
- Click on okay

- ###### Note that 'Calc.exe' is the path name for calculator on the sample system

- Close the Registry Editor

##### Restart Your System

#####Calc.exe file (Calculator) will run immediately on system logon


