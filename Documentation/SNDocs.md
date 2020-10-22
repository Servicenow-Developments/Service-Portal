# SNDOC

The SNDoc system is designed to emulate some of the functionality found in JSDoc, namely the ability to comment on code in a structured way, to generate documentation. The only place where SNDoc comments are processed is within Script Includes.

There are some differences between SNDoc and JSDoc though:

- Documentation is live, there is no need to run a specific process to update the documentation, just open up the 'Instance API Reference' portal to see the latest documentation
- SNDoc relies entirely on the comments that you create, unlike JSDoc which will parse a script and work out some of the details for you
- SNDoc can provide a best guess at other scripts in the platform that use your commented Script Include. SNDoc is NOT a javascript parser though, so this may show false positives
- The comment syntax is very similar to that of JSDoc, so if you're used to that, you should have no problem in picking up the SNDoc syntax.

Documentation is presented in the familiar format that's used by the ServiceNow API docs themselves, so getting used to using and reading the documentation should be a snap.

SNDoc was created by Callum Ridley at UP3 Services Ltd, to help keep on top of clients instances, enabling developers and managed service support staff to easily understand each others work, and move to a development methodology of reUSE not reWRITE.

We hope that by sharing this with the ServiceNow communiity that you too can find working in the platform easier and create more useful and reusable code.

Full documentation is available upon installation on the 'Help' tab of the 'Instance API Reference' Page

Access to SNDoc is provided by an application in the navigator called 'SNDocs' and then clicking on 'Instance API Reference'