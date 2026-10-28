# Network File Share

Create new Folder "CompanyShares" in C:/ drive  
Create subfolder "C:/CompanyShares/Finance-Data"  
Finance-Data -> Properties -> Turn on Sharing

![Alt Text](images/11a.png)

Check "Full Control" for "Everyone" in Advanced Sharing

![Alt Text](images/11b.png)

Security Tab  
Select "Convert inherited permissions into explicit permissions on this object"  
Remove "Users"  
Add -> Select a Principal  
Add in "SG-Finance-RW"  

![Alt Text](images/11c.png)

For "CompanyShares" Folder, turn on sharing and allow everyone full control  
From the Client computer, the shared folder became accessible using file path "\\\\192.168.10.10\CompanyShares"

![Alt Text](images/11d.png)

[← Back to Main Portfolio](README.md)
