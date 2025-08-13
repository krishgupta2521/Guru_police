Open PowerShell as Administrator

Right-click on PowerShell → Run as Administrator

Then run:

Set-ExecutionPolicy RemoteSigned

Choose Y for Yes.
Now close that Admin PowerShell window.
Open a new normal PowerShell and go to your project folder:

cd C:\Users\krish\Documents\gp_pro
.\detector-env\Scripts\Activate.ps1

Once it activates, your prompt will look like this:
(detector-env) PS C:\Users\krish\Documents\gp_pro>


All the Requirements 


pip install -r requirements.txt


python track_people.py main entry point 


video used is present in /videos folder 

