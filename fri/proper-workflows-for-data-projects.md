# Proper workflows for data projects

Panel. 

Version control essential. 
Automation needs some programming experience?
Use shell for automation.
Using csvcut etc to automate collection of csv and making sql and shpfile. 
Script is runnable/repeatable and commented. Better than keeping a log/diary of your actions.
What do you do when you can't automate? Make the human part of the process (like cleaning dirty data) in between automated parts.

How can we involve other people (non-programmers) in the process? Make admin apps and preview screens.

Informative error messages. Error notifications.

What about data input automation and workflow? Django apps with admin screens to do CRUD. NPR using google doc. But they make a copy and serve static.

www.lobbyingmissouri.org
openrefine.org

treat developer as a reporter, no disposable coding labour. 

At NPR, Project manager is not boss but instead a peer. They are responsible for making sure of release and hitting deadline. Hard to do project manager at the same time as being a dev (or other role).

Is there a more elegant way to put database under version control? Have an audit schema. Have migration scripts for your schema.

Use CRON.

Unit testing? Make a unit test when making an assertion about the (outside) world. Automate running of tests.

What about code review? 

Do pair programming.