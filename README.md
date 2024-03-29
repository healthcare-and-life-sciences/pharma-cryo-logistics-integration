
# A-HLS Pharma Cryo Logistics Integration FlexCard Documentation

## Overview

For Personalized Medicines, it is critical that proper Chain of Custody (COD) and logistics tracking is available to ensure that patients are treated within the required time line with the drug product containing the cells or formulation meant specifically for them, whether it’s their own cells (autologous therapies) or donor cells (allogeneic therapies with some matching), to avoid safety consequences such as product rejection or anaphylactic shock.

![](/images/pharma-cryo-logistics-fc.png)

---

## Business Objective

This accelerator provides the necessary API/Schema defintion to quickly integrate with leading Cryo Courier Services. Automating integration with courier services can be particularly important for cell and gene therapies due to their time and temperature-sensitive nature and complex logistic chains.

## Business Value and Benefits

-    **Improving compliance**: Integrating with QuickSTAT ("Quick") and WorldCourier ("World") can help sponsor manufacturers comply with regulatory requirements for the shipping and handling of cryo, such as Good Distribution Practice (GDP) and Good Manufacturing Practice (GMP) guidelines. This can help to avoid costly regulatory issues and recalls.
-    **Enhancing patient safety**: Integrating with Quick and World can help sponsor pharma to ensure that cell and gene therapies are delivered to the right patient at the right time and place, minimizing the risk of adverse events or incorrect administration.
-    **Improving customer experience**: Integrating with Quick and World can provide sponsor manufacturers with real-time tracking information and updates on the status of their shipment, improving the overall customer experience by increasing transparency and reducing uncertainty.
-    **Increased efficiency**: Integrating with Quick and World can help sponsor manufacturers reduce the time and cost associated with manual data entry, as well as minimizing the risk of errors that can cause delays in the shipment process.
-    **Competitive advantage**: Integrating with Quick and World can help businesses differentiate themselves from competitors by offering more reliable and efficient shipping of cell and gene therapies, which is critical in a highly competitive market. This can also help to build a brand reputation for quality and consistency.

---

## Industry Focus and Workflow

### Primary Industry:

-    Pharma
-    MedTech

### Primary User Persona:

-    Care Coordinator
-    MFG and Logistics Coordinator

---

## Package Includes:

### **FlexCard (1)**

-    Chain_of_Custody

---

## Configuration Requirements

### Pre-Install Configuration Steps:

1. For this FlexCard, you will need a data source which is not included in this data pack. This source can be from a third-party or a custom object in Salesforce. For demo purposes, this data pack includes static test data in the FlexCard.
2. Once you have a source, you will need to configure Integration Procedures and/or DataRaptors accordingly, and add those to the FlexCard and remove the static data. 
3. For more information regarding Integration Procedures, refer to this Trailhead: https://trailhead.salesforce.com/content/learn/modules/omnistudio-integration-procedures

#### Install the Data Pack

1. Follow the download steps in the "Download Now" flow presented on the HLS Accelerators website for this Accelerator which downloads the following GitHub repository on your machine: **[https://github.com/healthcare-and-life-sciences/pharma-cryo-logistics-integration]**

2. Then, complete the following steps to import them into your Salesforce org.

     1. To Import, in your destination Salesforce org, Click on **App Launcher** → Search for '**OmniStudio FlexCards**' and click on it.
     2. Click on '**Import**' on the right side.
     3. Select '**Upload Files**' - When the window opens, select the json file from the GitHub repository that you downloaded and stored on your machine. Click '**Open**' then click '**Next**' 3 times.
     4. When prompted to Activate the FlexCard, choose **Activate Later**.

### Post-Install Configuration Steps:

1. If you aren't already on the FlexCards tab, click on **App Launcher** → Search for “FlexCards”

     1. Navigate to the recently installed FlexCard in the list view
     2. Open the FlexCard
     3. Click **Activate** and select the appropriate Publish Options
     4. For more information regarding activating FlexCards, please see this article: https://help.salesforce.com/s/articleView?id=sf.os_activateconfigureand_publish_flexcards_24744.htm&type=5

2. Add the installed FlexCard to the lightning page layout of your choosing.

3. Refer to the following articles for more information regarding adding FlexCards to a Lightning or Experience page:

     1. https://help.salesforce.com/s/articleView?id=sf.os_add_a_flexcard_to_a_lightning_page.htm&type=5
     2. https://help.salesforce.com/s/articleView?id=sf.os_add_a_flexcard_to_an_experience_page.htm&type=5

---

## Assumptions

1. A customer has licenses for Health Cloud with core OmniStudio, or the HINS Managed Package with OmniStudio. These solutions have all been installed and are functional.
2. A customer is assuming Salesforce Lightning Experience — not Classic.
3. Data Model elements that are part of the HINS (Vlocity) Managed package or core OmniStudio with Health Cloud are all available.
4. The Accelerator uses the Lightning Design System standards and look. Customers may want to apply their own branding which can be achieved.

---

## Revision History

-    **Revision Short Description (Month Day, Year)**

     -    Initial (March 21, 2023)
     -    Revised (April 3, 2023)
