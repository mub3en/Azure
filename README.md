# Azure Resource Group Deletion Tool

This PowerShell script provides a simple GUI tool to help with deleting Azure resource groups. The tool allows you to select a resource group from a drop-down list, confirm the deletion, and perform the deletion operation using the `Remove-AzResourceGroup` cmdlet from the Azure PowerShell module.

## Prerequisites

- PowerShell with Azure PowerShell module (`Az`) installed and configured.
- Permission to delete resource groups in the Azure subscription.

## How to Use

1. Open PowerShell or PowerShell ISE.
2. Copy and run the code from the script file (`Delete_Azure_Resource_Groups_GUI.ps1`) in this repository.
3. The script will launch a Windows Forms GUI window.
4. The drop-down list will display the names of all the available resource groups in your Azure subscription.
5. Select a resource group from the drop-down list.
6. A confirmation message box will appear to confirm the deletion.
7. Click "Yes" to proceed with the deletion or "No" to cancel.
8. If "Yes" is selected, the script will attempt to delete the selected resource group.
9. If the deletion is successful, a success message will be displayed.
10. If the deletion fails, an error message will be displayed.
11. The drop-down list will be updated to remove the deleted resource group.
12. Repeat the process to delete additional resource groups if needed.

## Notes

- This tool is designed for deleting Azure resource groups only. Exercise caution when using it to avoid unintended deletions.
- Make sure you have appropriate permissions to delete resource groups in your Azure subscription.
- The tool utilizes the `Remove-AzResourceGroup` cmdlet, which permanently deletes the specified resource group and all the resources contained within it. Be mindful of the consequences before confirming the deletion.

## License

This project is licensed under the [MIT License](LICENSE).

