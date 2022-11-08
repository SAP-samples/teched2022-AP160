This repository contains the material for the SAP TechEd 2022 session - Design and Develop Extensions on SAP Service and Sales Cloud Version 2 Using SAP AppGyver

Overview This session introduces attendees to Design and Develop extensions in AppGyver and Embed extension as a mashup in SAP Sales and Service Cloud Version 2. In this session you learn about:

The hands-on session will involve two exercises.

* Design and Develop extension in AppGyver and Embed as Mash up in SAP Sales and Service Cloud Version 2
* Embed a pre-delivered Mashup in SAP Sales and Service Cloud Version 2


Design and Develop extension in AppGyver and Embed as Mash up in SAP Sales and Service Cloud Version 2
-----------------------------------------------------------------------------------------------------------------------

1. log in to SAP Service Cloud Version 2 or SAP Sales Cloud Version 2.

2. Navigate to the app switcher, and choose AppGyver.


![196336426-951f9368-cffa-4fc0-b772-32e13fbd8616](https://user-images.githubusercontent.com/114897342/196701140-4f597e67-2f8c-4221-9483-8b2547a4f60f.gif)

3. A new browser tab opens, displaying the AppGyver lobby



![196337870-571a4437-84b3-4157-9809-3a15624dafd3](https://user-images.githubusercontent.com/114897342/196701334-80e58b5b-28e1-435a-b339-e8761fe8a236.png)


Designing and Developing AppGyver Extensions
-----------------------------------------------------------------------------------------------------------------------
1. Click Create to start a new project. Enter a Project Name* and a Short Description for your project, and click Create.
<img width="1506" alt="196338720-48bbce42-a9c4-4c1a-8dc1-a8becbad7af6" src="https://user-images.githubusercontent.com/114897342/196702022-224a67e1-9502-45d2-b26f-7249ea5274ee.png">


2. A pop-up is displayed as shown below.

![196338203-da85f68c-8d86-4120-91a1-b425181a1e50](https://user-images.githubusercontent.com/114897342/196702312-1052a66d-f517-4ff4-85e3-e93ca819345a.png)

3. Once the app is created, you can see the UI Canvas.


<img width="1510" alt="196339150-fa111a23-279e-42a9-97af-444d050cece5" src="https://user-images.githubusercontent.com/114897342/196702407-9bbcba09-2a91-4e5f-ad77-12ad7627799b.png">

4. Go to the Auth tab to enable Authentication. Click Enable Authentication.

![196342880-5c778529-ffb1-4a6e-bdbe-02a4ec4d47e2](https://user-images.githubusercontent.com/114897342/196702512-bea4f10c-81eb-4b7d-9184-5567bce1f27e.png)

5. All the available authentication methods are displayed. Choose SAP BTP authentication from the authentication methods.

![196342946-739e808e-8150-43f3-8995-c0161e20f64b](https://user-images.githubusercontent.com/114897342/196702791-49a9db84-071f-41b5-9bf3-836180383ca3.png)

6. A pop-up similar to the one below is displayed.

![196343083-60d9ebc1-6c3a-42b8-994d-23b2ee00496c](https://user-images.githubusercontent.com/114897342/196703335-50da826f-d7a6-4970-bece-8cedc8961b19.png)

7. Click OK. image
![196343154-852ad308-8b54-41d9-865c-89e7adb10011](https://user-images.githubusercontent.com/114897342/196703455-80ab43bf-584f-4893-bcdd-56ae076fbdfc.png)

8. Click Only Web in BPT configuration and the Save BTP Configuration button.

![196343237-b996fa5b-9ec1-4ba4-9e4c-5281f38ac93a](https://user-images.githubusercontent.com/114897342/196703660-9f4680f1-9474-4044-9654-840b38b8dad5.png)


9. Navigate to the Data tab, Integrate with SAP Service and Sales Cloud Version 2 using BTP destinations and REST API content in your SAP AppGyver App. Select the ADD INTEGRATION.


![196343422-3a667025-c976-43cb-8938-13e2cfbf66d0](https://user-images.githubusercontent.com/114897342/196704000-07c2326c-f993-4908-b543-a6fef56be525.png)

10. On the Add Integration page, click BTP DESTINATIONS.

![196343467-a42dc73c-09b9-4a0b-aed5-566698ef06b9](https://user-images.githubusercontent.com/114897342/196704134-5a1addc0-d1cf-4f74-b953-faf3f2200777.png)


11. You will see a list of BTP Destinations.Note: BTP Destinations listed here are the destinations to your own SAP Service and Sales Cloud Version 2 API destination as it is set up on the BTP sub-account by the SAP AppGyver support team when the SAP Service and Sales Cloud Version 2 system is provisioned.

![image](https://user-images.githubusercontent.com/114897342/200280171-6461b065-d07d-44a7-9d07-85a1d706ce62.png)


12. Click on DESTINATION "S4HANACLOUD_CUSTRETURNS"

Click on "INSTALL INTGRATION"
![image](https://user-images.githubusercontent.com/114897342/200292529-685b2c31-8254-483e-a3fa-641a8899c8fb.png)

Click on "ENABLE DATA ENTRY" and SAVE
<img width="1506" alt="image" src="https://user-images.githubusercontent.com/114897342/200292888-0b732eb7-0d76-43e1-9ae6-95e4cd30588b.png">

<img width="1502" alt="196344152-cd6dbb6f-7d37-4bea-ace1-c8909159c5a7" src="https://user-images.githubusercontent.com/114897342/196704914-41fa6067-51f7-4cd2-8aa4-df4fff5669ad.png">

Repeat the same for DESTINATION "S4HANACLOUD_SO"
<img width="1501" alt="196344105-1f9e788d-1e04-460b-b3fd-72ad09339758" src="https://user-images.githubusercontent.com/114897342/196704683-d7ad35e7-5de5-43aa-ad9a-399a6ce54869.png">


13. Click on UI Canvas and go to Market Place
![196349784-093f4794-cbdf-4865-8757-4579e5f1d03a](https://user-images.githubusercontent.com/114897342/196705212-8bcab432-dc56-45fd-abb5-dab8e01daeb6.png)

14. Search for "Soft tabs"
<img width="1509" alt="image" src="https://user-images.githubusercontent.com/114897342/200294301-eb9eeead-78bb-4c8a-aa36-56791677e9d0.png">



![196350050-989661cc-0843-47f1-a9c4-d64f798beb43](https://user-images.githubusercontent.com/114897342/196705386-4cf67d32-9d57-4ebd-b8a9-3258e76e5d51.png)

15. Click on the "Soft tab" and INSTALL

<img width="1506" alt="image" src="https://user-images.githubusercontent.com/114897342/200294591-f5e25c55-0597-4ed1-bfd0-6835cbea1636.png">

Click on SAVE

16. You can now see "Soft tabs" in the Installed
![196350825-12e6f390-cd16-4130-af24-d4a338ecd389](https://user-images.githubusercontent.com/114897342/196705835-111d09a2-4c15-404f-99f6-3d73ed776a37.png)

17. Remove "Headline" and Text "Lorem ipsum dolor sit amet, consetetur sadipscing elitr"
![196351162-d74b5473-a782-4be2-96c5-edcf9a1d1454](https://user-images.githubusercontent.com/114897342/196705955-f74f9c64-1b5d-4474-9886-f7967562a261.png)

18. Pull "Soft tabs" on the UI Canvas
![196352118-f7316905-fb2a-4d79-a4e8-f85cce462262](https://user-images.githubusercontent.com/114897342/196706057-8d2200ea-3e69-4fdb-b966-4a0c852ed23b.png)

19. Click on VARIABLES
![196352299-a15f567a-5126-4f55-bba2-85be234c1da0](https://user-images.githubusercontent.com/114897342/196706217-6b186a63-5806-49cb-a720-8bd5116a62b3.png)

20. Go to PAGE VARIABLES and Click on "ADD PAGE VARIABLE"
![196356117-92515220-d4ed-4e10-9124-3e26800e8d30](https://user-images.githubusercontent.com/114897342/196706481-179d9309-7ff9-4b7f-9d60-84c46f1a3d88.png)

21. Rename "variable 1" to "orders", Variable value type = "List" and List Item Type = "Object"

![196356409-3b278e0a-5c97-4c54-8b6c-583e939e45fd](https://user-images.githubusercontent.com/114897342/196706599-47ce18c3-187a-4e56-8e52-97d3d2a7ee0f.png)


22. Add New Property as "label"


![196356812-d075ed97-0300-48ff-9f1d-1a5930bf1a40](https://user-images.githubusercontent.com/114897342/196706872-d647242d-20d0-4695-967c-139c5046592b.png)


23. Add Initial value and Click SAVE


![196358489-0ce26026-b204-44d5-a914-276cc717dafd](https://user-images.githubusercontent.com/114897342/196706977-e82d7201-8e6c-4535-94c7-eeb24cfcc630.png)


24. Add one more Page Variable and rename it to selected_tab and Click SAVE
![196359354-450cde49-2822-4d13-b304-2d2fa8971501](https://user-images.githubusercontent.com/114897342/196707072-bc691e1f-3322-4d53-9fef-4c5098551cfd.png)


25. Go back to the View and Click on Tabs in Properties



![196359772-59ec267d-da26-4088-853c-f92655f830ae](https://user-images.githubusercontent.com/114897342/196707306-146dddb5-c245-4573-bd3d-6e0d2a710db5.png)


26. Bind it with the Page variable "orders"
![196360117-1e49c158-ff85-4b5c-8f26-3474e657de7a](https://user-images.githubusercontent.com/114897342/196707391-8d790dca-9c71-4e8d-9e91-f5bc12ea13f2.png)


27. Add Logic to "Soft tabs 1" image

![196360792-78a4a6e9-7a8b-495e-8474-b7475b3d894c](https://user-images.githubusercontent.com/114897342/196707463-3f612330-fa03-4859-ad53-abe34d6f4d1c.png)

28. Drag "Recieve event" into LOGIC and go to Event Source

![196361121-f05a2fa9-ba77-4231-b71d-21f3ce49aed6](https://user-images.githubusercontent.com/114897342/196707538-f323f017-9ae5-48d9-a3e5-6e39e79a0632.png)


29. Set page variable and connect Event to Page variable
![196361608-5381eb23-5c7b-44dc-9b70-0e73accea59b](https://user-images.githubusercontent.com/114897342/196707611-4b4279d6-3bb0-4d41-8297-f75adf175cf5.png)


30. Choose a Variable name

![196361796-821c4491-4718-481d-bb4c-acaa89bd466e](https://user-images.githubusercontent.com/114897342/196707773-91d375c4-7637-4322-acc4-1a91408e2938.png)


31. Choose the Assigned value
![196362016-d5d8bf82-2ccb-4989-97d2-9ee3b3299a5b](https://user-images.githubusercontent.com/114897342/196707886-3b218af3-85f5-4f4f-b4c1-c008adc40a1e.png)


32. Drag and Drop "Input Field" into the UI Canvas

<img width="1510" alt="image" src="https://user-images.githubusercontent.com/114897342/200467460-3231c3a7-8fd3-4f1d-bccc-d7df0a5a75fa.png">


33. Go to Variables and then click on "ADD DATA VARIABLES".One for the Service Order and One for the Customer's Return

<img width="1508" alt="196407213-aa09a4be-b1e3-4708-93ab-23a0119a1201" src="https://user-images.githubusercontent.com/114897342/196708950-8cce7c93-f861-4828-a06a-bfda5b155e6f.png">

34. Drag and Drop the container and Rename it as Service Orders


![196400015-d851919a-8aa9-4004-999b-297bff2b8420](https://user-images.githubusercontent.com/114897342/196708130-1a14af08-9230-4534-b122-f7821525282f.png)


35. Set Visible property with the following formula

![image](https://user-images.githubusercontent.com/114897342/200282719-86fa1c73-8551-44f6-b404-cb355eb1507c.png)


36. Drag and Drop Text inside the container and rename it as Service Order
![196400685-7ede93b3-8415-40ef-a752-0d252ef8a2e7](https://user-images.githubusercontent.com/114897342/196708432-3fa9792c-9466-482d-9913-7a8bb3721c4d.png)


37. Drag and Drop the Row inside the container and set the layout as 6 Cells

<img width="1509" alt="image" src="https://user-images.githubusercontent.com/114897342/200467833-939d2132-1052-4206-ae8f-d934beba563f.png">


38. Drag and Drop "List Section Header" in each of these cells as shown below

<img width="1509" alt="image" src="https://user-images.githubusercontent.com/114897342/200468177-3a91b3d2-e5cb-4c14-becc-10b73e5a25a9.png">


Drag and Drop one more Row inside the container and set the layout as 6 Cells

<img width="1506" alt="image" src="https://user-images.githubusercontent.com/114897342/200468495-bd96e721-b247-43f0-95f3-7b21969891d0.png">

Go to "PROPERTIES" and Click on "Repeat with" and Bind with Data Variable
<img width="1506" alt="image" src="https://user-images.githubusercontent.com/114897342/200305913-56dc1e73-0e23-426e-b2fa-c08b34761790.png">

<img width="854" alt="image" src="https://user-images.githubusercontent.com/114897342/200305666-d0793c86-5594-4ba6-b990-9704a0b75360.png">





39. Search for "Link Button" in the marketplace and Install

![196405978-54e364ac-451d-4154-b218-29b266051d0b](https://user-images.githubusercontent.com/114897342/196708727-704376fe-8d3a-493a-9b36-b9933d407ca1.png)


40. Drag and Drop the Link button inside the first cell and List Item in rest of the 5 cells

<img width="1510" alt="image" src="https://user-images.githubusercontent.com/114897342/200298879-a79a03ca-a282-4884-8fbb-3139bcd40381.png">

For all the List Item, Remove the "Secondary label" from "Label" to Space and Arrow Visible to "False" (This is an optional activity)

41. Go to Variable and Click on "APP VARIABLE" and "ADD APP VARIABLE" as shown below
<img width="1497" alt="image" src="https://user-images.githubusercontent.com/114897342/200468761-6bc2b913-9cb9-4726-b689-6772912cc606.png">


Click on "PAGE PARAMETERS" and "ADD PARAMETER" as shown below
<img width="1505" alt="image" src="https://user-images.githubusercontent.com/114897342/200468833-4ad3e4df-616a-4ef4-af12-4df4d1d9da84.png">


Click on "Show logic for S/4 HANA TRANSACTIONS SEARCH" at the bottom section of the screen
<img width="1501" alt="image" src="https://user-images.githubusercontent.com/114897342/200468871-88215cdb-88c7-4cb6-8772-74bd217a1abb.png">


Drag "Set app variable" from the left section of the screen to the Logic block and connect Event to Variables as show below
<img width="1499" alt="image" src="https://user-images.githubusercontent.com/114897342/200301064-4993f0be-db16-45d5-bb9a-32058434c7e3.png">

Set Variable name to Salesorg
<img width="858" alt="image" src="https://user-images.githubusercontent.com/114897342/200468918-4a4109d5-7dc9-4ff1-bc35-76d5b24043de.png">

Set Assigned value to pgAccountID
<img width="850" alt="image" src="https://user-images.githubusercontent.com/114897342/200468962-814dfca6-a800-4a38-b1eb-23c68bf0963f.png">

Your screen should look like below
<img width="1509" alt="image" src="https://user-images.githubusercontent.com/114897342/200469019-484deb87-af4a-44dc-adc2-d2b10fcf2f31.png">


42. Choose the Service Order Data Variable and Click on Filter Condition
<img width="1502" alt="image" src="https://user-images.githubusercontent.com/114897342/200469245-d7f6e2f6-36f3-493a-a05a-c91f8731529b.png">

<img width="855" alt="image" src="https://user-images.githubusercontent.com/114897342/200469282-fa3f1410-2c0a-4604-bbde-36e8b9ba5d32.png">




43. Go to the Row of the List Item and bind individual fields as shown below

Service Order:
Click on Link Button and go to Label on the left side
<img width="1501" alt="image" src="https://user-images.githubusercontent.com/114897342/200303788-81d3e1d1-04de-4193-889d-b7c5d0014ba8.png">

Bind the label to the Service Order
<img width="850" alt="image" src="https://user-images.githubusercontent.com/114897342/200303899-c8e829e4-e6fd-459c-a52c-9ae667d8b107.png">


Description:
<img width="1504" alt="image" src="https://user-images.githubusercontent.com/114897342/200304065-f40dbc5e-9cdb-43b9-9a05-6d3bc2476a9d.png">
<img width="854" alt="image" src="https://user-images.githubusercontent.com/114897342/200304093-b5faffd3-fda1-40f7-bd7e-f3501f9e18dd.png">


Requested Start Date:
<img width="1505" alt="image" src="https://user-images.githubusercontent.com/114897342/200304183-e3e8957f-de77-4e1a-aca2-92b0d8211009.png">
<img width="1232" alt="image" src="https://user-images.githubusercontent.com/114897342/200304236-534adc79-1e0d-42b0-b99b-3c82bf710240.png">

Formula: FORMAT_DATETIME_LOCAL(DATETIME(NUMBER(REPLACE_ALL(REPLACE_ALL(repeated.current.RequestedServiceStartDateTime, "/Date(",""), ")/",""))),"DD.MM.YYYY")

Requested End Date:
<img width="1510" alt="image" src="https://user-images.githubusercontent.com/114897342/200304326-1816b4d0-53dd-498d-8f7c-22e0ce7d4bd9.png">
<img width="1231" alt="image" src="https://user-images.githubusercontent.com/114897342/200304368-b5092acb-bf6a-42d8-8d89-d1e0e89d1733.png">

Formula: FORMAT_DATETIME_LOCAL(DATETIME(NUMBER(REPLACE_ALL(REPLACE_ALL(repeated.current.RequestedServiceEndDateTime, "/Date(",""), ")/",""))),"DD.MM.YYYY")

Order Status:
<img width="1510" alt="image" src="https://user-images.githubusercontent.com/114897342/200304442-3e442b58-5f76-4ffc-b34c-18f12ab220d1.png">
<img width="1238" alt="image" src="https://user-images.githubusercontent.com/114897342/200304487-dd5604e6-6c88-47ed-a609-4081e94e91c7.png">

Formula: IF(repeated.current.ServiceOrderIsCompleted == "X","Completed","In Progress")

Release Status:
<img width="1506" alt="image" src="https://user-images.githubusercontent.com/114897342/200304590-c41aa228-4d62-418c-beda-78c639bb1c47.png">
<img width="1231" alt="image" src="https://user-images.githubusercontent.com/114897342/200304632-bf38f82d-1565-4a1f-8d16-bdd6e8d0c28b.png">

Formula: IF(repeated.current.ServiceOrderIsReleased == "X" || repeated.current.ServiceOrderIsCompleted == 'X',"Released","Open")


NOTE: THIS APP IS PRECOMPLETED TILL THIS STEP AND IS AN OPTION ACTIVITY. HANDS-ON EXERCISE WILL BEGIN FROM THE BELOW STEP.


**CUSTOMER RETURNS:**

1) Pull the container into the Canvas From the Left Option Bar
<img width="1502" alt="image" src="https://user-images.githubusercontent.com/114897342/200471995-c6d26e67-d00b-459a-b801-2e1f998f446a.png">

2) Rename the Container as "Customer Returns"
<img width="1511" alt="image" src="https://user-images.githubusercontent.com/114897342/200472130-94d88ee6-2efe-43f6-8a76-8315f4acf5d3.png">

3) Drag and Drop "Text" inside the Container and Rename it as "Customer Returns"
<img width="1507" alt="image" src="https://user-images.githubusercontent.com/114897342/200472371-1cc7f871-2b5b-4bee-bc24-528c6ebdba13.png">

4) Drag and Drop two "Row" inside the Container
<img width="1510" alt="image" src="https://user-images.githubusercontent.com/114897342/200472537-772c9137-9182-4802-b5cd-014d93542350.png">

5) Click on First and Second Row (Row 3 and Row 4) and Set to 5 Cells in Layout
<img width="1512" alt="image" src="https://user-images.githubusercontent.com/114897342/200472652-85450ff6-043e-4269-b982-346ec30e91bd.png">
<img width="1508" alt="image" src="https://user-images.githubusercontent.com/114897342/200472732-3379171e-0c87-48e0-8a4d-726a3d116881.png">

6) For First Row (Row 3), Drag and Drop "List Section Header" into each of the Cells and Rename as Shown Below
<img width="1510" alt="image" src="https://user-images.githubusercontent.com/114897342/200472957-84d7a718-888c-42e5-ac2a-6e9c24b789fe.png">

7) For Seconf Row (Row 4), 

For the First Cell, Drag and Drop "Link Button"
<img width="1509" alt="image" src="https://user-images.githubusercontent.com/114897342/200473365-458929d0-b3e2-4d26-8bea-fc149f02f3da.png">

For the Second Cell on wards, Drag and Drop "List Item" into the Cells
<img width="1502" alt="image" src="https://user-images.githubusercontent.com/114897342/200473486-c2f57f91-baa4-4043-9aa7-005193c715a5.png">

Remove "Secondary Label" and Set "Arrow Visible" to "False" in Properties( This is an optional activity)
![image](https://user-images.githubusercontent.com/114897342/200473856-58648556-eaf2-4a10-a716-2c94becda8b9.png)

8) Choose Second Row (Row 4) and Click on "Repeat with" in Properties

![image](https://user-images.githubusercontent.com/114897342/200474027-4387067d-3cfa-45a0-8a72-0ecdefff9dac.png)

and Bind this Row with the Data variable "A_Customer Return1" 
![image](https://user-images.githubusercontent.com/114897342/200474119-d846928b-f222-4dd0-8b05-d539e9ea1bab.png)




Continue to - [Exercise 2](../ex2/README.md)
