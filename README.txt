RBScoutSubmit v1.2

RBScoutSubmit is a small set of REALbasic classes that can be used to submit crash data from your REALbasic application to your FogBugz installation.


*** License ***

Please see RBScoutSubmit License.txt for the license for the main RBScoutSubmit classes and example code. Summary: It's a standard MIT license, do what you like with the code.

For the StackCleaner classes, please see the readme.txt file in the StackCleaner folder.


*** How To Use ***

1) Copy the RBScoutSubmit folder and it's contents into your REALbasic project.

2) Add RBScoutSubmit class as a property of the main App class.

3) Copy code from RBScoutSubmitExample project's App.UnhandledException into your own project.

4) Change URL, ScoutProject, ScoutArea and ScoutUserName to reflect your FogBugz install and project for this application.

If you want to use the stack trace functionality in your app, copy the StackCleaner folder into your project, otherwise comment out the code in the UnhandledException example code that uses StackArray.

It is *STRONGLY* recommended that you try the RBScoutSubmitExample project with your own URL, ScoutProject, ScoutArea and ScoutUserName settings to test that it all works before updating your own project.

Remember, none of this is going to work unless you have a publicly available FogBugz scoutSubmit.asp or scoutSubmit.php page.


*** Feedback/Bug Reports ***

mailto:support@imij.co.uk


*** Version History ***

1.2 2012-05-25

* Moved to GitHub.

1.1 2008-03-06

* Released on Google Code.

1.0 2007-05-26

* Initial public release.

--- EOF ---