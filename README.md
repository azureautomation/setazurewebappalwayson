Set-AzureWebApp-AlwaysOn
========================

            

This script can be used during code deployment in Microsoft Azure WebApp. It be design to force AlwaysOn activation and
It supports Slot deployment.



You can set multiples params :


[-ResourceGroupName(Mandatory)] [-WepAppName(Mandatory)] [-AlwaysOn(Mandatory)] [-Slot(Optionnal)]



What the script does :


  *  Check WebApp SKU 
  *  Configure AlwaysOn setting on the slot if param Slot configured 

Example:** *** *


 

 

        
    
TechNet gallery is retiring! This script was migrated from TechNet script center to GitHub by Microsoft Azure Automation product group. All the Script Center fields like Rating, RatingCount and DownloadCount have been carried over to Github as-is for the migrated scripts only. Note : The Script Center fields will not be applicable for the new repositories created in Github & hence those fields will not show up for new Github repositories.
