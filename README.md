# nodejs-01
Install nodejs on LinuxONE Community Cloud and run applicatoins.

## Prerequisites
1. Request access to LinuxONE Community Cloud. Follow instructions 

### Step 1: Install postgres database server on LinuxONE Community Cloud
 
1.3 Install required packages
   
For RHEL: 
```sh
$ sudo yum install nodejs -y
$ sudo yum install git -y 
$ sudo yum install vim -y 
```
Check nodejs version 
```sh
$ node -v
```
Sample output 

<img width="1438" alt="Screenshot 2020-08-17 at 21 01 51" src="https://user-images.githubusercontent.com/46126326/90435565-7a202300-e0cf-11ea-9568-70fa510a9225.png">

Check npm version
```sh
$ npm -v
```
<img width="1438" alt="Screenshot 2020-08-17 at 21 02 36" src="https://user-images.githubusercontent.com/46126326/90435580-7db3aa00-e0cf-11ea-8a2f-c82f80bbeccc.png">

Create a node js script 
```sh
$ node 
> console.log(“This is a test”); 
```
Sample output
<img width="1436" alt="Screenshot 2020-08-17 at 21 03 39" src="https://user-images.githubusercontent.com/46126326/90435585-7ee4d700-e0cf-11ea-99f6-a605bb82b0bb.png">

exit
```sh
> .exit
```
<img width="1432" alt="Screenshot 2020-08-17 at 21 04 02" src="https://user-images.githubusercontent.com/46126326/90435591-80ae9a80-e0cf-11ea-8c52-c8161cb5afff.png">

Create test.js
```sh
$ vim test.js
```
<img width="1433" alt="Screenshot 2020-08-17 at 21 04 31" src="https://user-images.githubusercontent.com/46126326/90435595-81dfc780-e0cf-11ea-8f67-b72ab73f6a92.png">
Save file and exit. 

Run the script
```sh
$ node test.js
```
<img width="1439" alt="Screenshot 2020-08-17 at 21 04 51" src="https://user-images.githubusercontent.com/46126326/90435599-8310f480-e0cf-11ea-8054-3e2e7a5cd695.png">

Create a project folder named project-01
```sh
$ mkdir project-01
```
Change directory to project-01
```sh
$ cd project-01
```
Create application 
```sh
$ vim apps.js
```
<img width="1440" alt="Screenshot 2020-08-17 at 21 05 21" src="https://user-images.githubusercontent.com/46126326/90435602-83a98b00-e0cf-11ea-9426-e3b90a2df95d.png">
Save file and exit. 

