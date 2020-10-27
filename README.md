Download a Blob from Azure Storage
==================================

            

This runbook downloads an Azure blob to the host running the runbook job.


In addition to this runbook, you will need an OrgID credential with access to your Azure subscription ([http://azure.microsoft.com/blog/2014/08/27/azure-automation-authenticating-to-azure-using-azure-active-directory/](http://azure.microsoft.com/blog/2014/08/27/azure-automation-authenticating-to-azure-using-azure-active-directory/))
 stored in an Azure Automation credential asset.


 When using this runbook, be aware that the memory and disk space size of the processes running your
runbooks is limited. Because of this, we recommened only using runbooks to transfer small files.
All Automation Integration Module assets in your account are loaded into your processes,
so be aware that the more Integration Modules you have in your system, the smaller the free space in
your processes will be. To ensure maximum disk space in your processes, make sure to clean up any local
files a runbook transfers or creates in the process before the runbook completes.



 


 

 

        
    
TechNet gallery is retiring! This script was migrated from TechNet script center to GitHub by Microsoft Azure Automation product group. All the Script Center fields like Rating, RatingCount and DownloadCount have been carried over to Github as-is for the migrated scripts only. Note : The Script Center fields will not be applicable for the new repositories created in Github & hence those fields will not show up for new Github repositories.
