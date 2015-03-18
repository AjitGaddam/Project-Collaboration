# Project-Collaboration

1-	WRNS needs Microsoft IIS (Internet Information Service) server to run
	-	If you do not have it installed, please follow the bellow procedure:
		Under Windows XP pro:
		Control panel >> Add or Remove Programs >> Add/Remove Windows Components 
		Check the Internet Information Services (IIS), then Click Next

		Windows will install IIS on your computer



2-	Right Click on the folder wrns, chose Sharing and Security.
		Under the Web Sharing panel, choose Share this folder, and choose WRNS as the Alias. 
		Check the Read and Write Box under Access permissions
		
		Note: You have to keep the folder WRNS under the folder wwwroot
		      and the folders wwwroot and DB should be in the same folder
		      in order to connect to the database

3-	Under IE in the URL bar type the following link:
	http://localhost/wrns

4-	You�re done!
