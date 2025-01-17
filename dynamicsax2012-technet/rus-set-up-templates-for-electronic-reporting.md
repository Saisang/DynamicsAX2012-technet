---
title: (RUS) Set up templates for electronic reporting
TOCTitle: (RUS) Set up templates for electronic reporting
ms:assetid: 2dd13388-bc71-4edc-aa6b-c7983a0e6d74
ms:mtpsurl: https://technet.microsoft.com/library/JJ677494(v=AX.60)
ms:contentKeyID: 49384799
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- reporting
- templates
- electronic reporting
- document template
audience: Application User
ms.search.region: Russia
---

# (RUS) Set up templates for electronic reporting 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You must configure a document template for each type of report that is submitted electronically to the tax authorities. The structure of the electronic file defines the list of sections, the content of those sections, and the order in which the sections are loaded.

Templates are configured in two steps:

1.  Set up the template structure in the **Document templates** form.

2.  Set up the template requisites in the **Requisites setup** form.

You can set up document templates for reports that are submitted in text format and XML format.

## Set up a template for text format

1.  Click **General ledger** \> **Setup** \> **Financial reports generator** \> **Document templates**.

2.  Click **New**, and then in the **Template** and **Name** fields, enter an identification number and a name for the template.

3.  In the **Format version** field, select a format version.

4.  In the **Report code** field, select a report code if you set up a report that is generated by using the Financial reports generator.

5.  In the **File name** field, select the file name and path and of the report template file.

6.  In the **Format** field, select the format code for the requisite.

7.  On the **Structure** FastTab, click **New** to create a section.

8.  In the **Section** and **Name** fields, enter an identification number and a name for the document section.

9.  If the version of the requisite format is earlier than 4, do the following:
    
      - In the **Delimiter "before"** field, select the delimiter code that is inserted before this section.
    
      - In the **Delimiter "after"** field, select the delimiter code that is inserted after the section.
    
      - In the **Section number** field, enter the section number.
    
      - Select the **Content** check box to indicate that the section is a parent section for all main report data sections.
        

        > [!NOTE]
        > <P>The fields that are mentioned in the preceding list are available only if the version of the requisite format is earlier than 4.</P>



10. Select the **On the next page** check box for sections that require two or more pages in the Microsoft Excel template.
    

    > [!NOTE]
    > <P>Some text format versions include sections that span two or more worksheets in the Excel template. In these cases, you must make sure that the worksheets are in the correct order when you create the dynamic requisites. The first worksheet must be followed by the next worksheet of the same section. Otherwise, the values of the requisites are selected incorrectly. If several sections are contained in the same Excel template, the <STRONG>On the next page</STRONG> check box is selected automatically to guarantee that other sections in the template are also searched after one section is found.</P>



11. Click **Add**, and then select the **Select** check box for the standard section that is added to the template. Click **OK**.
    

    > [!NOTE]
    > <P>To arrange the sections in the tree, select a section, and then click <STRONG>Up</STRONG> to move the section one position up in the tree, or click <STRONG>Down</STRONG> to move the section one position down.</P>



12. You can also import several requisites or create several identical sections.
    
      - Click **Import** to add several requisites to a section. For more information, see [(RUS) Requisites import (form)](https://technet.microsoft.com/library/jj710744\(v=ax.60\)).
    
      - To create several identical sections, on the **Structure** FastTab, click **New**. Then, in the tree, select the section to copy. Click **Copy**, and then in the **From template** field, select the section to copy. Click **OK**.
        

        > [!NOTE]
        > <P>If the section contains a dynamic table, you must create a separate auxiliary section for the dynamic table, the dynamic table totals, and any other requisites from this section. These sections are child sections of the main section in the information part of the report.</P>



## Set up a template for XML format

1.  Click **General ledger** \> **Setup** \> **Financial reports generator** \> **Document templates**.

2.  Click **New**, and then in the **Template** and **Name** fields, enter an identification number and a name for the template.

3.  In the **Format version** field, select a format version.

4.  In the **Report code** field, select a report code if you set up a report that is generated by using the Financial reports generator.

5.  In the **File name** field, select the path and name of the report template file.

6.  In the **Format** field, select the format code for the requisite.

7.  In the **File name** field, select the path and name of the report template file.

8.  Click **Functions** \> **Update structure**.

9.  Select the **Delete template content** check box to delete the content in the template.

10. Click **OK** to create the report structure automatically.
    

    > [!NOTE]
    > <P>You can view the template structure that is created on the <STRONG>Structure</STRONG> FastTab in the <STRONG>Document templates</STRONG> form. Each section in the template structure corresponds to an element in the XML schema definition (XSD) for the document.</P>



11. Select the **Optional section** check box for sections that are not included in the electronic file.
    

    > [!NOTE]
    > <P>If you select the <STRONG>Optional section</STRONG> check box for a section, the section is added to the electronic report file only if there are values in the appropriate fields. You must select this check box to include requisites in optional sections.</P>



## See also

[(RUS) Document templates (form)](https://technet.microsoft.com/library/jj923585\(v=ax.60\))

[(RUS) Requisites setup (form)](https://technet.microsoft.com/library/jj710719\(v=ax.60\))

[(RUS) Set up simple cell type requisites](rus-set-up-simple-cell-type-requisites.md)

[(RUS) Add standard sections (form)](https://technet.microsoft.com/library/jj710685\(v=ax.60\))

  


