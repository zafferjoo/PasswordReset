# PasswordReset
Password Reset Script
This Script has been designed that whenver an admin resets the password of the Enduser , the Temp Password sends the email to his Personal ID

############## Steps to Run the script #################### 

#Create a csv file (example Password.csv) with two headers "UPN" and "PersonalID".

#Save the script on desktop with as PasswordReset.ps1.
#Connect to Exchange Online PowerShell with the following command
# connect-exchangeonline -Userprincipalname xxxx@domain.com
Then run the following Scripts
# cd ~\desktop
# .\PasswordReset.ps1 -Inputfile Password.csv

This will send the password to the Persoanl ids of the endUsers
