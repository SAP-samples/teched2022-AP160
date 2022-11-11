# Design and Develop extension in AppGyver
The following exercise will provide detailed steps to develop a sample extension in AppGyver.

## Demo Tenants
* [my1000112.de1.demo.crm.cloud.sap](https://my1000112.de1.demo.crm.cloud.sap/)
* [my1000114.de1.demo.crm.cloud.sap](https://my1000114.de1.demo.crm.cloud.sap/)
* [my1000115.de1.demo.crm.cloud.sap](https://my1000115.de1.demo.crm.cloud.sap/)
* [my1000116.de1.demo.crm.cloud.sap](https://my1000116.de1.demo.crm.cloud.sap/)

## Authenticate and accessing AppGyver in SAP Sales and Service Cloud Version 2 
1. Access the Tenant assigned and Login using SSO. <br/>
![image](https://user-images.githubusercontent.com/117337025/201430903-b1148253-be20-4ae3-9bb0-f71647c3402f.png)

2. Use the credentials assigned to Login to SAP Sales and Service Cloud Version 2. <br/>
![image](https://user-images.githubusercontent.com/117337025/201431214-b8eed869-9442-4850-b9cd-e54424dc41f2.png)

3. Navigate to the app switcher, and choose AppGyver. <br/>
![196336426-951f9368-cffa-4fc0-b772-32e13fbd8616](https://user-images.githubusercontent.com/114897342/196701140-4f597e67-2f8c-4221-9483-8b2547a4f60f.gif)

4. A new browser tab opens, displaying the AppGyver lobby. <br/>
![image](https://user-images.githubusercontent.com/117337025/201432280-6b9517f0-9436-4754-9b9a-185a82654347.png)

## Developing Sample AppGyver Extension
During the next steps, we will extend an existing AppGyver extension and add new list to display and access Customer Returns. When you access the AppGyver lobby, you will already see 2 pre-delivered Projects. We have already deployed these projects in the interest of time.

- Service Order and Customer Returns - AP160_Exercise (Project to be used for this exercise)
- Service Order and Customer Returns (Completed Project)

If anyone is interested in developing from scratch, the following wiki [Developing new AppGyver Extensions](/develop-new-appgyver-extension.md) has detailed steps to create App, which in not in the scope of this session.

1. From the AppGyver Lobby, click to open the project: Service Order and Customer Returns - AP160_Exercise. <br/>
![image](https://user-images.githubusercontent.com/117337025/201436976-a2007623-a6df-4223-bf1a-df6e1a476f2e.png)

2. Change device preview width to "Fullscreen". <br/>
![image](https://user-images.githubusercontent.com/117337025/201437247-dbb57483-1a38-41c7-9835-a9ae656b8200.png)

3. Change the Page selection to "Empty Page". <br/>
![image](https://user-images.githubusercontent.com/117337025/201437519-9461abf7-8308-4edb-8bda-93c9c0bb97c4.png)

4. Pull the container into the Canvas From the Left Option Bar. <br/>
![image](https://user-images.githubusercontent.com/117337025/201440796-ae91df62-b5c7-4625-bb5a-0ec533fd1246.png)

5. Rename the Container as "Customer Returns" using "ADVANCED PROPERTIES" of the container. <br/>
![image](https://user-images.githubusercontent.com/117337025/201438498-fe980bd2-14ac-4229-8275-c62fcee69951.png)

6. Drag and Drop "Text" inside the Container and change content to "Customer Returns". <br/>
![image](https://user-images.githubusercontent.com/117337025/201440915-28c6a8e1-98a3-4a74-9ef3-f8d56217b460.png)

7. Drag and drop 2 "Row" inside the Container. The First Row will used to design the List Header and the Second Row will be used to design the List Content. <br/>
![image](https://user-images.githubusercontent.com/117337025/201441042-0080473d-42cf-485b-be89-0233e2bdd833.png)

8. Set the number of Row Cells to 5 in Layout options of the Row. <br/>
![image](https://user-images.githubusercontent.com/117337025/201441234-046b1f49-47cc-43bb-b84b-ef4554eea803.png)

7. For First Row , Drag and Drop "List Section Header" into each of the Cells and Rename as Shown Below
![image](https://user-images.githubusercontent.com/117337025/201441793-9b381464-a84b-4c2f-8a89-057242dcaaee.png)

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
![image](https://user-images.githubusercontent.com/114897342/200474296-1b303492-02a9-4d4f-95b2-911fda89e7be.png)
![image](https://user-images.githubusercontent.com/114897342/200474577-b6edc20f-f6be-4f08-bac2-48865a681ebb.png)

9) Now Bind each of these Five fields as below

**Return Order:**
<img width="1506" alt="image" src="https://user-images.githubusercontent.com/114897342/200474770-9fe2295f-d609-43c3-a279-0de67354f8c5.png">

![image](https://user-images.githubusercontent.com/114897342/200474891-b9c09306-49d3-41cf-acde-352fb2775642.png)

Click on Show logic for "Link BUTTON 2"
![image](https://user-images.githubusercontent.com/114897342/200475096-dd45d32b-90ba-4d40-aed0-b2bdd7b4e77a.png)

Go to the "MARKETPLACE" and Search "Open URL" 
![image](https://user-images.githubusercontent.com/114897342/200475287-f256853f-821c-42ca-b0f4-77aa4e5e6edf.png)

"INSTALL" the Open URL
![image](https://user-images.githubusercontent.com/114897342/200475360-79333214-9819-4e44-9ab4-fc9609a12ee1.png)

Drag and Drop "Open URL" into the Canvas and connect EVENT to Open URL
![image](https://user-images.githubusercontent.com/114897342/200475706-1601d965-8adf-4856-ac3c-7368ce9c67c1.png)

![image](https://user-images.githubusercontent.com/114897342/200475786-104c8cec-2e42-4a56-9137-074a6a42bd0a.png)

Formula: 
"https://my300047.s4hana.ondemand.com/ui#ReturnsOrder-edit?sap-app-origin-hint=&/CustomerReturn/"+repeated.current.CustomerReturn+"/edit"


**Purchase Order:**
<img width="1496" alt="image" src="https://user-images.githubusercontent.com/114897342/200475974-b4853b7b-5fa3-4979-8ee3-52c773f2427f.png">
<img width="852" alt="image" src="https://user-images.githubusercontent.com/114897342/200475994-cbcbb26c-4fa1-41b2-bc8c-6fe5bdcf53f4.png">


**Net Value:**
<img width="1505" alt="image" src="https://user-images.githubusercontent.com/114897342/200476103-604bc068-dba1-4843-86ed-806469d1c120.png">
<img width="1230" alt="image" src="https://user-images.githubusercontent.com/114897342/200476131-ca95d097-af62-4732-b664-b02832c59c24.png">
Formula:
repeated.current.TotalNetAmount + " " + repeated.current.TransactionCurrency


**Customer Return Date:**
<img width="1510" alt="image" src="https://user-images.githubusercontent.com/114897342/200476209-64a01722-e38e-4437-9a46-b01dffe4209b.png">
<img width="1233" alt="image" src="https://user-images.githubusercontent.com/114897342/200476222-cdd337b3-a02b-4c76-b843-b4414efe9675.png">
Formula: FORMAT_DATETIME_LOCAL(DATETIME(NUMBER(REPLACE_ALL(REPLACE_ALL(repeated.current.CustomerReturnDate, "/Date(",""), ")/",""))),"DD.MM.YYYY")


**Overall Status:**
<img width="1512" alt="image" src="https://user-images.githubusercontent.com/114897342/200476275-95f53c09-1063-41f3-a122-06b542bb9815.png">
<img width="1229" alt="image" src="https://user-images.githubusercontent.com/114897342/200476300-a1dc4c1b-9c6d-4669-a496-05013fa50e0f.png">
Formula: IF(repeated.current.OverallSDProcessStatus == "A","Open",IF(repeated.current.OverallSDProcessStatus == "B","In Process",IF(repeated.current.OverallSDProcessStatus == "C","Completed","")))


10) Go to DATA VARIABLE and Click on Filer Condition
<img width="1510" alt="image" src="https://user-images.githubusercontent.com/114897342/200476451-48d8fefa-3fae-4fbc-b3ed-1b551d3e992c.png">
<img width="870" alt="image" src="https://user-images.githubusercontent.com/114897342/200476549-d25e2dae-05a2-4627-87b6-bd5bc11a03de.png">

SAVE


12) Now Click on "LAUNCH" in the Top Menu
<img width="1501" alt="image" src="https://user-images.githubusercontent.com/114897342/200476826-750d59f4-ba33-4cb1-85a5-cbd88705c890.png">

13) Click on "OPEN APP PREVIEW PORTAL"

14) Enter Sales Org 
<img width="1504" alt="image" src="https://user-images.githubusercontent.com/114897342/200476979-d64168b6-5c8b-408a-a83b-0bfd265e7fe4.png">

15) Click on Service Orders
<img width="1504" alt="image" src="https://user-images.githubusercontent.com/114897342/200477042-fd45a569-3a66-4198-a480-2257950e4637.png">

16) Click on Customer Returns
<img width="1504" alt="image" src="https://user-images.githubusercontent.com/114897342/200477119-54943b95-67f3-4532-bfff-de5fd9de26e6.png">




Continue to - [Exercise 2](../ex2/README.md)
