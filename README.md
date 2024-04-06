To save the PowerShell script, simply create a new text file and copy the script contents into it. Then, save the file with the extension '.ps1'. This extension indicates that the file is a PowerShell script and allows it to be executed using PowerShell.


**To execute the PowerShell script, you can follow these steps:
**

1. Open PowerShell: You can do this by searching for "PowerShell" in the Start menu or by pressing Win + X and selecting "Windows PowerShell" or "Windows PowerShell (Admin)" from the menu.

2. Navigate to the directory where your PowerShell script is located using the `cd` command. For example, if your script is located in the "Scripts" folder on your desktop, you would type:

   ```
   cd C:\Users\YourUsername\Desktop\Scripts
   ```

4. Once you're in the correct directory, you can execute the PowerShell script by typing its filename (including the `.ps1` extension) and pressing Enter. For example:

   ```
   .\myscript.ps1
   ```

Replace `"myscript.ps1"` with the name of your PowerShell script.

4. Press Enter to execute the script.

Make sure that you have the necessary permissions to execute scripts on your system. If you encounter an error stating that scripts are disabled on your system, you may need to adjust the PowerShell execution policy. You can do this by running PowerShell as an administrator and executing the following command:

```
Set-ExecutionPolicy RemoteSigned

```
This command allows scripts that you created locally to be executed but requires scripts downloaded from the internet to be digitally signed by a trusted publisher.
