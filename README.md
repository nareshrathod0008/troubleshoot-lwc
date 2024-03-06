# troubleshoot-lwc
<h5>Download Components for the Troubleshooting Lightning Web Components Trailhead Badge<h5>

<h1>Open Visual Studio Code and clone this GitHub repo.</h1>
<br>
In Visual Studio Code, open the Command Palette by pressing Ctrl+Shift+P (Windows) or Cmd+Shift+P (macOS).

<br>
1.Enter git.
<br>
2.Select Git: Clone.
<br>
 
3.Select Desktop and then click Select Repository Location.
<br>

<h1>Update Salesforce CLI</h1>

<h6>It's always a good idea to update to the latest CLI</h6>

1.Click View, and then select Terminal to open a terminal in Visual Studio Code.
<br>
2.Update the CLI by running this command in the terminal:
<br>

<h5>sfdx update</h5>

<h1>Create DX Project</h1>

1.Open the Command Palette.<br>

<br>2.Enter sfdx.

<br>3.Select SFDX: Create Project.
<br>4.Select Standard.
5.Enter troubleshoot-lwc as the project name and press Enter.
6.Select Desktop for folder to store the project.
7.Click Create Project.
8.Click Overwrite.
<h1>Authorize Your Trailhead Playground</h1>
<br>1.Open the Command Palette.
Enter sfdx.
Select SFDX: Authorize an Org.
Press Enter to accept the Project Default login URL option.
Press Enter to accept the default alias. Salesforce login opens in a separate browser window.
Log in using your Trailhead Playground credentials.
If you're prompted to allow access, click Allow.
Deploy to Playground
Right-click the default folder under force-app/main.
Click SFDX: Deploy Source to Org.
Assign Permission Set
Click View, and then select Terminal. A terminal window opens in Visual Studio Code. The terminal defaults to the top-level directory of the project.
Assign the Solutions Full Access permission set to the default user by running this command in the terminal:
sfdx force:user:permset:assign -n Solutions_Full_Access
View the Solutions App
In your Trailhead Playground, in App Launcher, search for sol.
Select Solutions.
