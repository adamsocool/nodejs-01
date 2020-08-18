# nodejs-01
Install nodejs on LinuxONE Community Cloud and run applications.

## Prerequisites
Request access to LinuxONE Community Cloud. Follow instructions https://github.com/linuxone-community-cloud/technical-resources/blob/master/faststart/deploy-virtual-server.md

Install Visual Studio Code on your workstation. https://code.visualstudio.com/

### Install postgres database server on LinuxONE Community Cloud
 
Install required packages
   
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

## Create a node js script 
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
## Create an application 
```sh
$ vim apps.js
```
<img width="1440" alt="Screenshot 2020-08-17 at 21 05 21" src="https://user-images.githubusercontent.com/46126326/90435602-83a98b00-e0cf-11ea-9426-e3b90a2df95d.png">
Save file and exit. 

Check the ip address of the server and copy it. 
```sh
$ nmcli
```
<img width="1437" alt="Screenshot 2020-08-17 at 21 07 12" src="https://user-images.githubusercontent.com/46126326/90444681-98d9e600-e0de-11ea-9f49-95596047a044.png">

Run the application
```sh
$ node apps.js
```
<img width="1437" alt="Screenshot 2020-08-17 at 21 08 54" src="https://user-images.githubusercontent.com/46126326/90444702-a42d1180-e0de-11ea-8777-f7c1b5f44f4f.png">

Open web browser, insert ip address port 3000
<img width="1440" alt="Screenshot 2020-08-17 at 21 10 00" src="https://user-images.githubusercontent.com/46126326/90444760-c45cd080-e0de-11ea-8c99-2b12feecf71b.png">

This was rendered using plain text, we will now render html.

Create index.html using vscode

Type ! and press enter and it will generate the outline on an html document for you. 
Inside the body insert This is HTML so that you know you are rendering htm instead of plain text. 
<img width="1439" alt="Screenshot 2020-08-17 at 21 10 37" src="https://user-images.githubusercontent.com/46126326/90444770-c757c100-e0de-11ea-9a68-4e4de35a9396.png">

Sample output after pressing enter
<img width="1440" alt="Screenshot 2020-08-17 at 21 11 00" src="https://user-images.githubusercontent.com/46126326/90444775-ca52b180-e0de-11ea-9828-86c826f3db57.png">

Create the file on server using vim and copy the contents  
```sh
$ vim index.html
```
copy apps.js file content add a function in apps.js to use html instead of plain text and import a library so you can read the file index.html

create file called appshtml.js and change the port to 3001
```sh
$ vim appshtml.js
```
<img width="1440" alt="Screenshot 2020-08-17 at 21 11 38" src="https://user-images.githubusercontent.com/46126326/90444779-cc1c7500-e0de-11ea-9b9d-7e1890087c61.png">

Run application 
```sh
$ node appshtml.js
```
<img width="1436" alt="Screenshot 2020-08-17 at 21 12 21" src="https://user-images.githubusercontent.com/46126326/90444785-d0489280-e0de-11ea-8e35-007253a71c86.png">

Open web browser, insert ip address port 3001
<img width="1440" alt="Screenshot 2020-08-17 at 21 12 48" src="https://user-images.githubusercontent.com/46126326/90444792-d2125600-e0de-11ea-8caa-10add182c942.png">
 
## Well done!
