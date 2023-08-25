# STEPS TO CLONE AND BUILD
Install git client client from https://git-scm.com/downloads
Install nodejs and npm from https://nodejs.org/en/download
Open the command prompt move to folder where you want to get the source code and enter below commands
             > git init
             > git clone https://github.com/sanketsharma99/vedichoroo.git
             > npm install
Now you should be able to build the source code using below command to produce android app
             > ionic cordova build android --release --prod     
The above command will create the required output file (.apk) (please note you will need a signed apk, in order to host your app in playstore)
Further inorder to test and debug the app you will need Android Studio 
