## Auto Triggering Flow
- **Status** -Pending
- **Name** -Initially
- **Follow Up Date** - Today +2
  
In my project, it was used to trigger an event when a Lead is captured manually. The automation automatically creates an alert named **Initial**, sets the status to **Pending**, and creates a task for follow-up due in **Today + 2 days**,last after all the event an **Email Alert** will be send to Admin/Mananger

## Screen Flow
- **Account** (Account Name, Industry, Number of Employee)
- **Contact** (First Name, Last Name, Email Address)
- **Opportunities** (Opp Name, Stage, Close Date, Amount)

In the Screen Flow, I created a form using the **Account**, **Contact**, and **Opportunity** objects to capture lead information efficiently. This also allows clean and accurate reporting based only on the data entered through the screen. Once the process is completed, a task is automatically created to ensure the admin follows up on the pending activity.

## Validation Rule
I used a Validation Rule to ensure that all important data is entered correctly. For example, when the **Stage = Closed Won** and the **Amount = 0**, the record cannot be saved until the error is corrected.

 ## Approval Process
The Approval Process is configured to ensure that when there is a new Opportunity, the record is locked and cannot be edited by anyone except the Manager or designated Salesforce Admin users. In addition, when the Amount is greater than 500,000 and the Stage is **Closed Won**, the record must be approved by the Manager.

## Dashboard
I created a dashboard using filtered Opportunity reports. The dashboard displays the number of opportunities, revenue over time, opportunities by stage, and the total sum of amounts using a matrix report.

## SaleforceAdmin ## ZeroCoding ## StayTuneForMore ✅
