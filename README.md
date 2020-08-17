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

<img width="2" alt="Screenshot 2020-08-17 at 21 06 49" src="https://user-images.githubusercontent.com/46126326/90435604-84dab800-e0cf-11ea-9403-ff3f480004e5.png">

<img width="1437" alt="Screenshot 2020-08-17 at 21 07 12" src="https://user-images.githubusercontent.com/46126326/90435606-85734e80-e0cf-11ea-9072-49062ef81704.png">

<img width="1437" alt="Screenshot 2020-08-17 at 21 08 54" src="https://user-images.githubusercontent.com/46126326/90435613-860be500-e0cf-11ea-9dfd-c4bdbb82bcf8.png">

<img width="1440" alt="Screenshot 2020-08-17 at 21 10 00" src="https://user-images.githubusercontent.com/46126326/90435619-873d1200-e0cf-11ea-94bd-40347ea8ba01.png">

<img width="1439" alt="Screenshot 2020-08-17 at 21 10 37" src="https://user-images.githubusercontent.com/46126326/90435624-886e3f00-e0cf-11ea-9fa8-cb5d9b6d28a6.png">

<img width="1440" alt="Screenshot 2020-08-17 at 21 11 00" src="https://user-images.githubusercontent.com/46126326/90435627-8906d580-e0cf-11ea-8741-3d77525680b7.png">

<img width="1440" alt="Screenshot 2020-08-17 at 21 11 38" src="https://user-images.githubusercontent.com/46126326/90435630-899f6c00-e0cf-11ea-8fe7-6557e9bc1cd9.png">

<img width="1436" alt="Screenshot 2020-08-17 at 21 12 21" src="https://user-images.githubusercontent.com/46126326/90435637-8ad09900-e0cf-11ea-9553-6e3d442c42dd.png">

<img width="1440" alt="Screenshot 2020-08-17 at 21 12 48" src="https://user-images.githubusercontent.com/46126326/90435639-8c01c600-e0cf-11ea-92b7-175b38601e43.png">
