# AzureGroupLock
Azure allows administrators to <b>lock</b>  resource groups. This helps prevent users from inadvertently delete resources within a resource group.
<br>
1 - To configure a lock on a resource group, go to **NameOfResourceGroup** > **Locks**
<img width="524" alt="image" src="https://github.com/tipros/AzureGroupLock/assets/170012689/08d51894-d788-4ef5-b991-1f0ec60e271d"> </br>
2 - Click on <b>Add</b>, enter a name, a description, and select **Read-Only** or **Delete**.</br>
3 - Click **OK**.</br>
4 - Attempt to delete an existing resource, i.e. a VM. When you do this, you will get the following message that the resource cannot be deleted due to a **lock**. </br>
<img width="260" alt="image" src="https://github.com/tipros/AzureGroupLock/assets/170012689/c25adc41-bef5-49d7-9f70-87cd135f6ada">
