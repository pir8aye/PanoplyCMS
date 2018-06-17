# pir8-CMS 1.0

## Dependencies
Install dependencies directly to your CMS source folder.
- [Choco](https://chocolatey.org/install) 
    - `SET "PATH=%PATH%;%ALLUSERSPROFILE%\chocolatey\bin"`    
- [Meteor](https://www.meteor.com/install)
    - install with the command: `choco install meteor --execution-timeout 5400`
    - [Alternate Windows Installation](https://github.com/meteor/docs/blob/master/long-form/alternate-windows-installation.md)
    - `SET "PATH=%PATH%;%LocalAppData%\.meteor"`
    - Turn off antivirus and firewall
- [NPM](https://www.npmjs.com/get-npm)


## Installation Method
- Pull pir8-CMS from GitHub Repository on your system OR you can download zip and extract it on your machine.
- Go to folder location through terminal or command prompt
- First run: `meteor npm install` 
- Then run: `meteor --settings settings.json` . Please wait for server to get start. It will automatically install all dependencies and will start running.
- Once server starts running, go to your browser and type: http://localhost:3000
- Thats it! You have successfully installed pir8-CMS on your system.

- Frontend Link: http://localhost:3000
- Backend Link: http://localhost:3000/admin

- Initial Login Credentials of Backend :-<br>
	Email: info@deligence.com<br>
	Password: Pass@123

Now go and create some categories, then articles and finally some menus. Look at the changes at your frontend.

## Demo
- Frontend: http://45.55.157.253/
- Backend: http://45.55.157.253/admin
- Backend Login Details :-<br>
	Email: info@deligence.com<br>
	Password: Pass@123

## Features
- Single Admin
- Multiple Categories
- Articles Associated With Created Categories
- Multiple & Multilevel Menus
- Tags associated with articles
- Dynamic Template
- Menu Module that can load at any given position
- HTML Blocks that can load at any given position
- Slider Module that can load at any given position

