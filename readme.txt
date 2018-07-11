Study Guide for Azure 70 533 Exam

Setting up the windows Powershell for Azure :

Notes :
 The azure powershell will work only on version 5.1 with windows 7 SP 1
 The ricsson image is providing only the Powershell version 2.1. Upgrade powershell to version 5.1

Steps Done :
	1. upgraded Windows Powershell to 5.1
	2. Installed azureRM 
		Commands to execute in powershell:
			$PSVersionTable					
			Get-ExecutionPolicy
			Set-ExecutionPolicy RemoteSigned
			Install-Module azureRM
			Install-Module azure -AllowClobber
