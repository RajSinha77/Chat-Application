# Chat-Application


https://chat-app-cba35.web.app/












To deploy Firebase Hosting 

Install the Firebase CLI #
First of all, we need to install the Firebase CLI tools. This tutorial assumes that Node is installed on the machine and npm commands can be executed. CLI tools can be installed by running the following command:

npm install -g firebase-tools

Login to Firebase #
Once Firebase is installed, you will need to sign in to Firebase. To do that, we will run the following command from the widget below:

firebase login --no-localhost




Initialize Firebase in Your Project. #
Now you can initialize Firebase in your project by running the following command in the terminal provided above.

firebase init

Select Hosting From the Options #
When you see the menu for firebase services, choose Hosting with the arrow keys (up/down) and press the space bar to select. Then, hit enter.




















Public Directory #
Add ./firebase-code as your public directory. This tells Firebase to look for index.html in the root of your app. Then you will be asked if you want to configure it as a single-page app. Select no by entering N. Notice that the N is capital in the (y/N). That means that if you hit enter without putting N it will default to N.

You will be asked if you want to overwrite index.html. Add the N and press enter.




<h2> DEPLOYMENT </h2>








