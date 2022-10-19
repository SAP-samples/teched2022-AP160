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






