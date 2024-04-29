# Exercise 5: Azure Stack HCI Update management using Azure Portal  

In this exercise, you'll be checking for updates in Azure Stack HCI via the Azure portal, which involves leveraging Azure Arc for centralized management and update assessment. Administrators can deploy updates seamlessly across clusters, scheduling and monitoring the process for minimal disruption and optimal infrastructure performance. This integration streamlines hybrid cloud operations, enhancing agility and security across on-premises and Azure environments.

### Task 1: Update Azure Stack HCI  

1. Navigate to the Azure Stack HCI resource named **hciboxcluster** from the **AzureStackHCI resource group**.

2. On the **Azure Stack HCI** page, select **Updates** under **Operations** from the left menu.

   ![](media/hci24-11.png)

3. From the **Updates** pane, click on **One-time update**.

   ![](media/hci24-12.png)

4. In the **Install updates** pane from the **Azure Update manager**, verify the available updates and click on **Next**.

   ![](media/hci24-13.png)
  
5. Select the available updates to install and click on **Next**.

   ![](media/hci24-14.png)

6. From the **Review + Install** pane, review the selected updates and click on **Install**.

   ![](media/hci24-15.png)

7. You'll see a notification that **Installation started on 1 Azure Stack HCI systems**. Also, you'll be able to see the **In-progress** status from the **Updates** pane.

   ![](media/hci24-16.1.png)

8. Updating the Azure Stack HCI Cluster will take around 2 hours. Once it's updated successfully, you'll be able to see the status as **Up-to-date** and the update readiness as **Healthy** as shown in the below screenshot.

   ![](media/hci24-17.png)

