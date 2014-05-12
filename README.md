contactbuilder
==============
Contact Builder – Customer Relationship Management Application.


 Contact Builder includes the following;
1.	A Company Manager, which is used to add, change and delete companies that a subscriber is interested in tracking.
2.	A Contact Manager. The contact manager allows the subscriber to add contacts to the companies that have been created using the company manager.
3.	An Opportunity Manager. The opportunity manager allows a subscriber to create and track opportunities related to the companies created using the company manager

About Contact Builder

Contact builder has been created as a proof of concept using Angular.js and bootstrap.

Getting Started

Contact builder can be downloaded from github to your local machine;

Once loaded to be able to write and run the automated end-to-end tests, then node and protractor also need to be downloaded.

Node can be downloaded from the node site;
http://nodejs.org

Protractor (https://github.com/angular/protractor/blob/master/docs/getting-started.md) should be downloaded using the following command;
1.	Navigate using the terminal to the contactbuilder folder
2.	Type npm install protractor
3.	Type webdriver-manager update

This will install protractor into a folder inside the contactbuilder folder.  In the config folder/protractor-conf.js I have set the base URL to port 8888 –  to utilize my existing (MAMP) server. You may need to reset this to another port number.

To run unit tests, using Chrome, open the file in the unit folder named SpecRunner.html. 

To run end-to-end tests,using the terminal, navigate into the scripts folder and run ./e2e-test.sh

To run the application, with a webserver pointed at contactbuilder,  type http://localhost:8888/app/customerManagementApp.html

Jshint is used to lint the javascript files. This is installed using npm install jshint 
( http://blog.teamtreehouse.com/improving-code-quality-jshint ),
 ( http://www.akawebdesign.com/2012/12/12/lint-roller-nodejs )

then run node launchLinter.js from the scripts folder. A log file will contain the errors (error.log).
