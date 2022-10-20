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

3. A new browser tab opens, displaying the AppGyver lobby. image



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
<img width="1494" alt="196343633-48aadb73-2d9a-4216-9842-a627a11c584f" src="https://user-images.githubusercontent.com/114897342/196704401-5b123ffa-c5b9-42f2-be5c-d3b5ad9528b3.png">


12. Click on S4HANACLUD_SO AND S4HANACLOUD_CUSTRETURNS

<img width="1501" alt="196344105-1f9e788d-1e04-460b-b3fd-72ad09339758" src="https://user-images.githubusercontent.com/114897342/196704683-d7ad35e7-5de5-43aa-ad9a-399a6ce54869.png">

<img width="1502" alt="196344152-cd6dbb6f-7d37-4bea-ace1-c8909159c5a7" src="https://user-images.githubusercontent.com/114897342/196704914-41fa6067-51f7-4cd2-8aa4-df4fff5669ad.png">


13. Click on UI Canvas and go to Market Place
![196349784-093f4794-cbdf-4865-8757-4579e5f1d03a](https://user-images.githubusercontent.com/114897342/196705212-8bcab432-dc56-45fd-abb5-dab8e01daeb6.png)

14. Search for "Soft tabs"

![196350050-989661cc-0843-47f1-a9c4-d64f798beb43](https://user-images.githubusercontent.com/114897342/196705386-4cf67d32-9d57-4ebd-b8a9-3258e76e5d51.png)

15. Click on the "Soft tab" and INSTALL
![196350230-c1624871-1728-4c73-8015-ce8f8ea6736f](https://user-images.githubusercontent.com/114897342/196705504-45b7eb15-51d4-4fc0-be03-0cdffc61c0de.png)

16. You can now see "Soft tabs" in the Installed
![196350825-12e6f390-cd16-4130-af24-d4a338ecd389](https://user-images.githubusercontent.com/114897342/196705835-111d09a2-4c15-404f-99f6-3d73ed776a37.png)

17. Remove "Headline" and Text "Lorem ipsum dolor sit amet, consetetur sadipscing elitr"
![196351162-d74b5473-a782-4be2-96c5-edcf9a1d1454](https://user-images.githubusercontent.com/114897342/196705955-f74f9c64-1b5d-4474-9886-f7967562a261.png)

18. Pull "Soft tabs" on the UI Canvas
![196352118-f7316905-fb2a-4d79-a4e8-f85cce462262](https://user-images.githubusercontent.com/114897342/196706057-8d2200ea-3e69-4fdb-b966-4a0c852ed23b.png)

19. Click on VARIABLES
![196352299-a15f567a-5126-4f55-bba2-85be234c1da0](https://user-images.githubusercontent.com/114897342/196706217-6b186a63-5806-49cb-a720-8bd5116a62b3.png)

20. Go to PAGE VARIABLES and Click on "ADD PAGE VARIABLE" image
![196356117-92515220-d4ed-4e10-9124-3e26800e8d30](https://user-images.githubusercontent.com/114897342/196706481-179d9309-7ff9-4b7f-9d60-84c46f1a3d88.png)

21. Rename "variable 1" to "orders", Variable value type = "List" and List Item Type = "Object"

![196356409-3b278e0a-5c97-4c54-8b6c-583e939e45fd](https://user-images.githubusercontent.com/114897342/196706599-47ce18c3-187a-4e56-8e52-97d3d2a7ee0f.png)


22. Add New Property as "label"


![196356812-d075ed97-0300-48ff-9f1d-1a5930bf1a40](https://user-images.githubusercontent.com/114897342/196706872-d647242d-20d0-4695-967c-139c5046592b.png)


23. Add Initial value and Click SAVE image


![196358489-0ce26026-b204-44d5-a914-276cc717dafd](https://user-images.githubusercontent.com/114897342/196706977-e82d7201-8e6c-4535-94c7-eeb24cfcc630.png)


24. Add one more Page Variable and rename it to selected_tab and Click SAVE image
![196359354-450cde49-2822-4d13-b304-2d2fa8971501](https://user-images.githubusercontent.com/114897342/196707072-bc691e1f-3322-4d53-9fef-4c5098551cfd.png)


25. Go back to the View and Click on Tabs in Properties image



![196359772-59ec267d-da26-4088-853c-f92655f830ae](https://user-images.githubusercontent.com/114897342/196707306-146dddb5-c245-4573-bd3d-6e0d2a710db5.png)


26. Bind it with the Page variable "orders" image
![196360117-1e49c158-ff85-4b5c-8f26-3474e657de7a](https://user-images.githubusercontent.com/114897342/196707391-8d790dca-9c71-4e8d-9e91-f5bc12ea13f2.png)


27. Add Logic to "Soft tabs 1" image

![196360792-78a4a6e9-7a8b-495e-8474-b7475b3d894c](https://user-images.githubusercontent.com/114897342/196707463-3f612330-fa03-4859-ad53-abe34d6f4d1c.png)

28. Drag "Recieve event" into LOGIC and go to Event Source image

![196361121-f05a2fa9-ba77-4231-b71d-21f3ce49aed6](https://user-images.githubusercontent.com/114897342/196707538-f323f017-9ae5-48d9-a3e5-6e39e79a0632.png)


29. Set page variable and connect Event to Page variable image
![196361608-5381eb23-5c7b-44dc-9b70-0e73accea59b](https://user-images.githubusercontent.com/114897342/196707611-4b4279d6-3bb0-4d41-8297-f75adf175cf5.png)


30. Choose a Variable name image

![196361796-821c4491-4718-481d-bb4c-acaa89bd466e](https://user-images.githubusercontent.com/114897342/196707773-91d375c4-7637-4322-acc4-1a91408e2938.png)


31. Choose the Assigned value image
![196362016-d5d8bf82-2ccb-4989-97d2-9ee3b3299a5b](https://user-images.githubusercontent.com/114897342/196707886-3b218af3-85f5-4f4f-b4c1-c008adc40a1e.png)


32. Drag and Drop "Input Field" into the UI Canvas image

![196362661-fd840d82-6c3c-4e42-a86f-c639e5ac042c](https://user-images.githubusercontent.com/114897342/196707949-d88322b9-c92a-4c93-aed4-d5bd3bcadc15.png)

33. Go to Variables and add App Variable image

![196397455-2d32171c-fcc0-48af-9bed-c6d951fd9813](https://user-images.githubusercontent.com/114897342/196708069-3380a5dd-fc8f-4630-bd97-188953113042.png)


34. Drag and Drop the container and Rename it as Service Orders image


![196400015-d851919a-8aa9-4004-999b-297bff2b8420](https://user-images.githubusercontent.com/114897342/196708130-1a14af08-9230-4534-b122-f7821525282f.png)


35. Set Visible property with the following formula


<img width="1234" alt="196400344-fc777240-c247-4f8f-8dbf-c51b5ce97460" src="https://user-images.githubusercontent.com/114897342/196708208-ee3e4264-15d7-47d6-93dd-598bcf2486b8.png">


36. Drag and Drop Text inside the container and rename it as Service Order image
![196400685-7ede93b3-8415-40ef-a752-0d252ef8a2e7](https://user-images.githubusercontent.com/114897342/196708432-3fa9792c-9466-482d-9913-7a8bb3721c4d.png)


37. Drag and Drop the Row and set the layout as 7 Cells image

![196400979-ce55bb82-428f-451d-957f-9d379c829fea](https://user-images.githubusercontent.com/114897342/196708511-0c0550ef-b27c-4eb9-9edb-d5b837402ce3.png)


38. Drag and Drop "List Section Header" in each of these cells as shown below image

![196405356-78b1544b-9a48-4e72-bc5a-7e033ddadd72](https://user-images.githubusercontent.com/114897342/196708668-3c5019bc-edd9-4f9f-913b-45c14c780539.png)


39. Search for "Link Button" in the marketplace and Install image

![196405978-54e364ac-451d-4154-b218-29b266051d0b](https://user-images.githubusercontent.com/114897342/196708727-704376fe-8d3a-493a-9b36-b9933d407ca1.png)


40. Drag and Drop the Link button inside the first container and List Item in rest of the 6 items image
![196406904-9868e6fe-376c-44f1-89df-d314023cf991](https://user-images.githubusercontent.com/114897342/196708792-d3b4d6ef-a1f8-4e68-84b5-3224f741850d.png)


41. Go to Variables and then click on DATA VARIABLES.One for the Service Order and One for the Customer's Return

<img width="1508" alt="196407213-aa09a4be-b1e3-4708-93ab-23a0119a1201" src="https://user-images.githubusercontent.com/114897342/196708950-8cce7c93-f861-4828-a06a-bfda5b155e6f.png">


42. Choose the Service Order Data Variable and Click on Filter Condition

<img width="858" alt="196407533-f535bc65-c5ca-4600-8f87-756c13d84acd" src="https://user-images.githubusercontent.com/114897342/196709010-12a98082-fff9-4772-aa40-4b4974bd44cb.png">

Repeat the above step for the Customer Return as well.

43. Go to the Row of the List Item and bind individual fields as shown below

Service Order list item: 
<img width="857" alt="196407999-4fb530c5-d4c1-4bb4-896b-abe58b002f4f" src="https://user-images.githubusercontent.com/114897342/196709398-9b0ea0b1-73ec-4a72-aa3e-2b92c9e81154.png">


Description:
<img width="852" alt="196408078-e6631f86-b8cb-469d-ab2d-aa8cf52c2525" src="https://user-images.githubusercontent.com/114897342/196709425-f9e9d267-8ac6-4c7d-a2ae-6b7bf72cadf0.png">




Net Value:
<img width="1222" alt="196408198-9956505d-6846-4531-b82e-034aafb63151" src="https://user-images.githubusercontent.com/114897342/196709576-6c230bf3-407a-4833-a34f-b924bb76cc81.png">

Requested Start Date: 

<img width="1186" alt="196408297-deaae91c-c644-42a2-bc96-51bf82bd19fe" src="https://user-images.githubusercontent.com/114897342/196709690-6b110f55-394e-4efc-a0bb-65ea8d750ce8.png">


Requested End Date: 
<img width="1198" alt="196408368-6275add8-dfb2-42bf-991e-998ba480167e" src="https://user-images.githubusercontent.com/114897342/196709782-07fc94a3-db2b-4368-a78f-bbd0e679fa77.png">



Order Status: 
<img width="1199" alt="196408459-4e924b0d-4e9f-4d58-8369-56bb87b8c4d8" src="https://user-images.githubusercontent.com/114897342/196709833-f03b6b9b-83e6-4a27-b9a8-9a0e3a5b1010.png">



Release Status: 
<img width="1208" alt="196408533-d0e880b0-57d1-4fb0-9984-d07c3408fde7" src="https://user-images.githubusercontent.com/114897342/196709990-6ccf3c7e-a5f6-451e-85a0-56521d47af04.png">

44. Repeat steps 36 to 43 to Customer Returns.

45. Now go to Launch. Click on "OPEN APP PREVIEW PORTAL" and Open the app

<img width="1505" alt="196409510-0cc22813-ee21-4935-a688-a8f3e1e1698b" src="https://user-images.githubusercontent.com/114897342/196710181-fbd40011-a5ed-4a80-b1a6-994bd066b13b.png">


<img width="1495" alt="196409554-16b8258b-3611-49c9-9a52-4c4f83cc54e2" src="https://user-images.githubusercontent.com/114897342/196710280-eaa9c2ee-9a7b-4162-9981-a8086c7bc351.png">






## Embed a pre-delivered Mashup in SAP Sales and Service Cloud Version 2 

1. Log in to SAP Service Cloud Version 2 or SAP Sales Cloud Version 2.

2. Navigate to Settings.
<img width="1680" alt="image" src="https://user-images.githubusercontent.com/84871522/196828012-064a7722-72ff-4162-9ee5-c2b872441433.png">

3. Navigate to Mashup Authoring. 
<img width="1676" alt="image" src="https://user-images.githubusercontent.com/84871522/196828261-75ed2669-cf0f-4667-b9c6-db9b62d8f2fa.png">

4. You will find the Mashup added in the list. This will be the mashup that we will be embedding in Agent Desktop. 
<img width="1673" alt="image" src="https://user-images.githubusercontent.com/84871522/196828404-c5e1d53f-adcd-45a2-8826-513de9d7f45f.png">

5. Navigate to the module switcher, and choose Agent Desktop.
<img width="1677" alt="image" src="https://user-images.githubusercontent.com/84871522/196828450-23b91a9b-ba26-4da1-87ff-50199abe0717.png">

6. A new tab opens, displaying the Agent Desktop.
<img width="1673" alt="image" src="https://user-images.githubusercontent.com/84871522/196828481-bdcd5c8a-16b4-4a46-9f53-cf27e917b8a9.png">

7. Search the Account and Click on "Confirm" button for the account name.
<img width="1664" alt="image" src="https://user-images.githubusercontent.com/84871522/196870284-558ddce1-01ba-4ffe-a243-4cbf31ddb5ba.png">

8. Click on the "Confirm" button for the contact. 
<img width="1658" alt="image" src="https://user-images.githubusercontent.com/84871522/196870354-1f6d0504-5299-4920-a1e8-bc6fca41d003.png">

9. A new tab opens, displaying the Customer Hub. 
<img width="1664" alt="image" src="https://user-images.githubusercontent.com/84871522/196870574-a9f6a2db-caa1-4514-9217-a958e3e63681.png">

10. Click on the User Profile -> Start Adaptation. 
<img width="1653" alt="image" src="https://user-images.githubusercontent.com/84871522/196870623-a909066c-1520-4077-924d-18a423beaa0c.png">

11. The application will be displayed in adaptation mode.
<img width="1660" alt="image" src="https://user-images.githubusercontent.com/84871522/196870730-857874e9-b94e-478e-b01e-cd6e7bdab474.png">

12. Hover over the "What would you like to do?" section and Click on the Edit (pencil) icon.
<img width="1664" alt="image" src="https://user-images.githubusercontent.com/84871522/196870974-365fa40a-34ac-4128-807e-5263331c9167.png">

13. "Section Items" pop up would be displayed. Here, click on the "Create Button" (+) icon.
<img width="1659" alt="image" src="https://user-images.githubusercontent.com/84871522/196871045-3dedbb86-de28-4441-9066-08bfe4348e14.png">

14. A new popup "Add Button" opens. Add the Button Name and Event name for the button. Then click "Apply". 
<img width="1674" alt="image" src="https://user-images.githubusercontent.com/84871522/196871267-70303fdb-c67e-452d-aa8b-f93287648355.png">

15. The new button will be added in the "What would you like to do?" section. 
<img width="1659" alt="image" src="https://user-images.githubusercontent.com/84871522/196871405-370c3448-14a5-4b5d-8497-938597f436e3.png">

16. Hover over the tabs section and Click on the Edit (pencil) icon. 
<img width="1657" alt="image" src="https://user-images.githubusercontent.com/84871522/196871483-a6c479dd-10b5-4ffb-b479-9dcbd0dc4c9a.png">

17. "Edit Tabs" popup would be displayed. Here, click on the "Create Tab" (+) icon.
<img width="1656" alt="image" src="https://user-images.githubusercontent.com/84871522/196871806-3badabe9-f56b-479f-8f9b-3f35d298c1f2.png">

18. Add new tab name and click ">" button. 
<img width="1659" alt="image" src="https://user-images.githubusercontent.com/84871522/196872379-f87ccafd-8922-4610-a984-7c2b9f7e47a0.png">

19. Check the "Show on Event Trigger" checkbox and select the Event we added in Step 14. Then click "Apply".
<img width="1662" alt="image" src="https://user-images.githubusercontent.com/84871522/196872499-4b1ed260-b4a7-41e1-b7b6-0363bece64e5.png">

20. The new tab will be added.
<img width="1656" alt="image" src="https://user-images.githubusercontent.com/84871522/196872619-555514ab-4f47-44f8-a6f7-3b671fe41470.png">

21. Click on the newly added tab in the above step and Click on the Edit (pencil icon) inside the tab.
<img width="1661" alt="image" src="https://user-images.githubusercontent.com/84871522/196872706-82d6d44b-4f11-46d9-a222-039c6e34f8a0.png">

22. "Configure Tab" pop up will be displayed. Click on the ">" for Add Mashup. 
<img width="1657" alt="image" src="https://user-images.githubusercontent.com/84871522/196872802-fd442939-7815-49e7-985b-40f05713e77a.png">

23. A new pop up showing all the Mashups would display. 
<img width="1672" alt="image" src="https://user-images.githubusercontent.com/84871522/196872904-93254c8c-c758-4b50-922b-bd71374c7371.png">

24. Search for the Mashup we searched in step 4 and embed by clicking on ">" in front of the mashup name.
<img width="1656" alt="image" src="https://user-images.githubusercontent.com/84871522/196874051-3df06b74-d705-41f1-8337-c1e94adb0308.png">

25. "Edit Properties" pop would display. Then click "Apply". 
<img width="1664" alt="image" src="https://user-images.githubusercontent.com/84871522/196874289-2631f96a-e65e-4044-a125-491e11d56ec7.png">

26. The selected mashup would be displayed in the tab. Then end the Adaptation mode by clicking the "End Session" button on the orange bar on top of the page.
<img width="1667" alt="image" src="https://user-images.githubusercontent.com/84871522/196874583-83b54eff-a941-47fd-8ea8-8da74b534dfa.png"> 

27. Now, when you click on the new button we added in step 15 then the new tab which we added in step 20 will be displayed along with the selected Mashup. Your Mashup is embedded!!!
<img width="1661" alt="image" src="https://user-images.githubusercontent.com/84871522/196875002-0cd33617-3966-4400-a7da-86b19cce836b.png">
