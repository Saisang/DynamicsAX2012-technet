---
title: (RUS) Set up a register for incomes and expenses that do not influence the tax base
TOCTitle: (RUS) Set up a register for incomes and expenses that do not influence the tax base
ms:assetid: e4108a63-d764-4d0d-8323-ad028ee239fc
ms:mtpsurl: https://technet.microsoft.com/library/JJ839693(v=AX.60)
ms:contentKeyID: 50396839
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- set up a register
- incomes and expenses
- influence tax base
- tax base
audience: Application User
ms.search.region: Russia
---

# (RUS) Set up a register for incomes and expenses that do not influence the tax base 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

The **Incomes and expenses that do not influence the tax base** register contains information about income and expenses that do not affect the tax base. This information is used to calculate tax difference registers.

1.  Click **General ledger** \> **Setup** \> **Profit tax** \> **Registers**.

2.  Create a register, and then in the **Register type** field, select **Incomes and expenses that do not influence the tax base**.

3.  In the **Register code** field, enter an identification code for the register.

4.  In the **Register name** field, update the register name, if required.

5.  In the **Period types** field, select the period that the register is generated for, from the following options:
    
      - **Months** – The register is generated for a month.
    
      - **Quarter** – The register is generated for a quarter.
    
      - **Half-Yearly** – The register is generated for a half year.
    
      - **Years** – The register is generated for a calendar year.
    
      - **Nine months** – The register is generated for a period of nine months.

6.  Click the **Hide** FastTab.

7.  In the **Available fields:** list, select the fields to exclude from the register, and move those fields to the **Selected fields** list.

8.  In the **Selected fields** list, select the check box for each field to exclude from the register.

9.  Click **Expense codes**, and then click **New** to create an expense code.

10. In the **Expense code** field, select the expense code that is set up for the income and expenses that do not affect the tax base register.

11. Click the **Exceptions** FastTab, and then click **Add** to specify the ledger accounts to exclude from the register.

12. In the **Valid for** field, select the ledger accounts to exclude from the register, from the following options:
    
      - **Table** – The vouchers from the ledger accounts that are selected in the **Debit account** and **Credit account** fields are excluded from the register.
    
      - **Group** – The vouchers from the ledger accounts in the group that is selected in the **Debit account** and **Credit account** fields are excluded from the register.
    
      - **All** – The vouchers from the ledger accounts that are selected in the **Debit account** and **Credit account** fields are excluded from the register.

13. In the **Debit account** and **Credit account** fields, select the codes of the ledger accounts to exclude from the register.

14. Click the **Exception dimension** FastTab, and then select the dimensions to exclude from the register.

## See also

[(RUS) Tax registers (form)](https://technet.microsoft.com/library/jj853195\(v=ax.60\))

[(RUS) Calculate registers](rus-calculate-registers.md)

  


