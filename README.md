# troubleshoot-lwc
Download Components for the Troubleshooting Lightning Web Components Trailhead Badge

Open Visual Studio Code and clone this GitHub repo.
<br>
In Visual Studio Code, open the Command Palette by pressing Ctrl+Shift+P (Windows) or Cmd+Shift+P (macOS).

<br>
Enter git.
<br>
Select Git: Clone.
<br>
 
Select Desktop and then click Select Repository Location.
<br>

<h1>Update Salesforce CLI</h1>

<h6>It's always a good idea to update to the latest CLI</h6>

1.Click View, and then select Terminal to open a terminal in Visual Studio Code.
<br>
2.Update the CLI by running this command in the terminal:
<br>
sfdx update
Create DX Project
Open the Command Palette.
Enter sfdx.
Select SFDX: Create Project.
Select Standard.
Enter troubleshoot-lwc as the project name and press Enter.
Select Desktop for folder to store the project.
Click Create Project.
Click Overwrite.
Authorize Your Trailhead Playground
Open the Command Palette.
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
