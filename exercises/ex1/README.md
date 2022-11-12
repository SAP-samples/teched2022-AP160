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

4. Click on "VARIABLES" to define Data Variables. <br/>
![image](https://user-images.githubusercontent.com/117337025/201445350-6d4bafa9-4772-461d-8460-1063fc91a71f.png)

5. Select "DATA VARIABLES" from Left Navigation. <br/>
![image](https://user-images.githubusercontent.com/117337025/201445385-6e7f5013-c563-444f-a4b1-cc4b2cdc6e0a.png)

6. Click on "ADD DATA VARIABLE" and select "A. <br/>
![image](https://user-images.githubusercontent.com/117337025/201445443-2e5d4a71-38bb-4a27-9a46-507546e982a1.png) <br/>
![image](https://user-images.githubusercontent.com/117337025/201445469-bd346ae7-19f1-49e6-8efa-a46facd02030.png) <br/>

7. You should see a new Data Variable "A-CustomerReturn1" in the list. <br/>
![image](https://user-images.githubusercontent.com/117337025/201445526-c8292e34-f3cc-4ccd-b995-678f7ea96150.png)

8. Pull the container into the Canvas From the Left Option Bar. <br/>
![image](https://user-images.githubusercontent.com/117337025/201440796-ae91df62-b5c7-4625-bb5a-0ec533fd1246.png)

9. Rename the Container as "Customer Returns" using "ADVANCED PROPERTIES" of the container. <br/>
![image](https://user-images.githubusercontent.com/117337025/201438498-fe980bd2-14ac-4229-8275-c62fcee69951.png)

10. Drag and Drop "Text" inside the Container and change content to "Customer Returns". <br/>
![image](https://user-images.githubusercontent.com/117337025/201440915-28c6a8e1-98a3-4a74-9ef3-f8d56217b460.png)

11. Drag and drop 2 "Row" inside the Container. The First Row will used to design the List Header and the Second Row will be used to design the List Content. <br/>
![image](https://user-images.githubusercontent.com/117337025/201441042-0080473d-42cf-485b-be89-0233e2bdd833.png)

12. Set the number of Row Cells to 5 in Layout options of the Row. <br/>
![image](https://user-images.githubusercontent.com/117337025/201441234-046b1f49-47cc-43bb-b84b-ef4554eea803.png)

13. For First Row , Drag and Drop "List Section Header" into each of the Cells and Rename as Shown Below
![image](https://user-images.githubusercontent.com/117337025/201441793-9b381464-a84b-4c2f-8a89-057242dcaaee.png)

14. We would need a Link Button for the exercise which is not part of the Core controls. Click on "MARKETPLACE".
![image](https://user-images.githubusercontent.com/117337025/201442746-6511d99f-5092-464f-8133-c155a4e14535.png)

15. Search for "Link button" in the marketplace.
![image](https://user-images.githubusercontent.com/117337025/201442806-404cf725-1ead-433a-8239-cd71b39d1da7.png)

16. Click on the "Link button" and click "Install".
![image](https://user-images.githubusercontent.com/117337025/201442916-9040b579-d4b0-4398-827d-2acc8db20f5a.png)

17. Check the "INSTALLED" tab and you will find the "Link button" installed.
![image](https://user-images.githubusercontent.com/117337025/201442999-50cd989e-47ec-415e-9138-92cb44c756c9.png)

18. For Second Row, <br/>
Drag and Drop "Link Button" to the First Cell <br/>
![image](https://user-images.githubusercontent.com/117337025/201443081-5fd62c99-eb1f-42c5-ae7e-0e5d4f35c0d3.png)<br/>

19. For the Second Cell on wards, Drag and Drop "List Item" into the Cells <br/>
![image](https://user-images.githubusercontent.com/117337025/201443138-8c223d8e-1f9b-47da-aea7-d6370685336c.png)<br/>
Remove "Secondary Label" and Set "Arrow Visible" to "False" in Properties( This is an optional activity)<br/>
![image](https://user-images.githubusercontent.com/117337025/201443209-d7e0c37c-b1f8-4065-9fa3-ca3e7408b43a.png)<br/>

20. Choose Second Row and Click on "Repeat with" in Properties. <br/>
![image](https://user-images.githubusercontent.com/117337025/201444973-ec21be86-6c8c-4c74-891c-bc1c0af7b76f.png) <br/>

21. Select "Data and Variables". <br/>
![image](https://user-images.githubusercontent.com/117337025/201445104-e64e6fa0-18e5-4d68-9df9-e4caecba251a.png) <br/>

22. Select "DATA VARIABLE". <br/>
![image](https://user-images.githubusercontent.com/117337025/201445151-9d1e846f-f4d3-4d57-8c69-d8ac12398c57.png) <br/>

23. Select "A_CustomerReturn1". <br/>
![image](https://user-images.githubusercontent.com/117337025/201445711-4b8ca366-9ec2-4fc5-9dfc-7d087987cd4c.png) <br/>

24. Click "Save".
![image](https://user-images.githubusercontent.com/117337025/201445724-830d8260-1e23-45e8-a9de-9990211e3e0b.png) <br/>

25. You would see the List Data now showing as Repeated Rows. <br/>
![image](https://user-images.githubusercontent.com/117337025/201446015-efc619c5-6a6e-48ae-b525-e4525402d6b5.png)

26. We will bind the "Return Order" column data. Click on the data cell for "Return Order" column. <br/>
![image](https://user-images.githubusercontent.com/117337025/201446223-688fc59a-0c91-4dac-b9e5-76444c09b5e3.png) <br/>
Click on "Label" icon in the "PROPERTIES". <br/>
![image](https://user-images.githubusercontent.com/117337025/201446283-23b92106-4c43-4077-a9b5-23b389073493.png) <br/>
Click on "Data item in repeat". <br/>
![image](https://user-images.githubusercontent.com/117337025/201446328-6e4223e7-c23f-431f-8e88-4efcaace1817.png) <br/>
Select "current". <br/>
![image](https://user-images.githubusercontent.com/117337025/201446358-4835119c-0e46-4894-b1e6-0c498d2d5da1.png) <br/>
In the "Select repeat data property", scroll and select "CustomerReturn" under "current". <br/>
![image](https://user-images.githubusercontent.com/117337025/201446427-23eadd9f-b30a-4da8-a1cf-9f9ba04c5de1.png)
Set preview values as "Return" and click "SAVE". <br/>
![image](https://user-images.githubusercontent.com/117337025/201446464-fb0eb0b8-7672-4568-8e7f-41eefa4253dc.png)

27. Similarly, bind the "Purchase Order" column data. Click on the data cell for "Purchase Order" column. <br/>
![image](https://user-images.githubusercontent.com/117337025/201446609-83406285-f6e5-476a-87b4-84833c336793.png) <br/>
Click on "Label" icon in the "PROPERTIES". <br/>
Click on "Data item in repeat". <br/>
Select "current". <br/>
In the "Select repeat data property", scroll and select "PurchaseOrderByCustomer" under "current". <br/>
Set preview values as "Purchase Order" and click "SAVE". <br/>

28. We will now bind a Formula to the "Net Value" column data. Click on the data cell for "Net Value" column. <br/>
![image](https://user-images.githubusercontent.com/117337025/201446946-4d9530ba-89cb-4a3c-9687-66082508bdb0.png) <br/>
Click on "Label" icon in the "PROPERTIES". <br/>
Click on "Formula". <br/>
![image](https://user-images.githubusercontent.com/117337025/201447015-195122cc-4713-4972-b64a-05308bc405d3.png) <br/>
Click on "Formula" again. <br/>
![image](https://user-images.githubusercontent.com/117337025/201447042-429da76e-47f6-45e0-a9db-08c313c883c1.png) <br/>
Enter the following Formula to show value as Amount + Currency. <br/>
```
repeated.current.TotalNetAmount + " " + repeated.current.TransactionCurrency
```
![image](https://user-images.githubusercontent.com/117337025/201447153-834ecab8-3c4f-4752-b860-87f41ec15e82.png) <br/>
Click on "SAVE". <br/>
Set preview values as "Purchase Order" and click "SAVE". <br/>
![image](https://user-images.githubusercontent.com/117337025/201447219-ffbc4cd1-ac52-40da-8ce1-812a14877d66.png) <br/>

29. Similarly, bind the "Customer Return Date" column data. Click on the data cell for "Customer Return Date" column. <br/>
![image](https://user-images.githubusercontent.com/117337025/201447437-5e8ec1ba-7ed0-485c-b385-e5e95d21a952.png) <br/>
Click on "Label" icon in the "PROPERTIES". <br/>
Click on "Formula". <br/>
Click on "Formula" again. <br/>
Enter the following Formula to show only the Return Date. <br/>
```
FORMAT_DATETIME_LOCAL(DATETIME(NUMBER(REPLACE_ALL(REPLACE_ALL(repeated.current.CustomerReturnDate, "/Date(",""), ")/",""))),"DD.MM.YYYY")
```
Click on "SAVE". <br/>
Set preview values as "01.01.1970" and click "SAVE". <br/>

30. Similarly, bind the "Overall Status" column data. Click on the data cell for "Overall Status" column. <br/>
![image](https://user-images.githubusercontent.com/117337025/201447499-ba1d0052-0f5c-478f-b2fb-f769a0029acb.png) <br/>
Click on "Label" icon in the "PROPERTIES". <br/>
Click on "Formula". <br/>
Click on "Formula" again. <br/>
Enter the following Formula to show Statusy. <br/>
```
IF(repeated.current.OverallSDProcessStatus == "A","Open",IF(repeated.current.OverallSDProcessStatus == "B","In Process",IF(repeated.current.OverallSDProcessStatus == "C","Completed","")))
```
Click on "SAVE". <br/>
Set preview values as "Open" and click "SAVE". <br/>

31. We need to install "Open URL" to be able to open a URL on click of the Return Column. <br/>
Go to the "MARKETPLACE" and Search "Open URL". <br/>
![image](https://user-images.githubusercontent.com/114897342/200475287-f256853f-821c-42ca-b0f4-77aa4e5e6edf.png) <br/>

"INSTALL" the Open URL. <br/>
![image](https://user-images.githubusercontent.com/114897342/200475360-79333214-9819-4e44-9ab4-fc9609a12ee1.png)

32. We will configure the "Return" link button to open URL. <br/>
Click on data cell of "Return" column. <br/>
![image](https://user-images.githubusercontent.com/117337025/201447829-2bbf67fb-9314-410c-9fc5-ab0afe424df3.png) <br/>

Click on "Add logic to LINK BUTTON1". <br/>
![image](https://user-images.githubusercontent.com/117337025/201447875-e5a33272-8bde-40d4-9427-bd203282dc9d.png) <br/>

Drag and Drop "Open URL" into the LOGIC. <br/>
![image](https://user-images.githubusercontent.com/117337025/201448061-686a931e-0be5-4f3e-975f-d2349ce634a4.png) <br/>
Click on the "URL to open" icon in "PROPERTIES" and click on "Formula". <br/>
Click on "Formula" again and enter the following formula. Please note that the double quotes also should be part of the formula. <br/>
```
"https://my300047.s4hana.ondemand.com/ui#ReturnsOrder-edit?sap-app-origin-hint=&/CustomerReturn/"+repeated.current.CustomerReturn+"/edit"
```
![image](https://user-images.githubusercontent.com/117337025/201448212-e047bc30-dca8-4627-bb30-4b920f55fe93.png) <br/>
Click in "SAVE". <br/>
Now, connect EVENT to Open URL <br/>
![image](https://user-images.githubusercontent.com/117337025/201448455-aa961cdb-4547-484a-8a1b-5b7ca4f823cc.png) <br/>
Collapse the Logic Editor. <br/>

34. We will now assign user input to the app variable. <br/>
Select the "Sales Ord" input field. <br/>
![image](https://user-images.githubusercontent.com/117337025/201449004-b8cf3c84-e893-45b6-8246-8b77a909eda4.png) <br/>
Bind the "Value" to "SalesOrg" (Data and Variables -> App Variable -> SalesOrg -> SAVE). <br/>

35. Change the "VIEW" to "VARIABLES" on top and navigate to "DATA VARIABLES".
![image](https://user-images.githubusercontent.com/117337025/201448633-13a0a4d3-424f-45c1-b3fa-19ae2ded2c19.png) <br/>

36. We will now add Filter to the Customer Returns Data Variable. <br/>
Select "A_CustomerReturn1" and clck on "Filter Condition" in the right panel. <br/>
![image](https://user-images.githubusercontent.com/117337025/201448698-66b73db3-7815-49cf-906b-57ef527dfa31.png) <br/>
Select "Object with properties". <br/>
![image](https://user-images.githubusercontent.com/117337025/201448743-8ebbad53-c35a-4974-8361-cee6a1684885.png) <br/>
Click on "ADD CONDITION". <br/>
![image](https://user-images.githubusercontent.com/117337025/201448774-0057cc61-44d4-4920-be2a-7a749d637092.png) <br/>
Select "Property" as "SalesOrganization" and "Compared Value" as "SalesOrg" (Data and Variables -> App Variable -> SalesOrg -> SAVE) .
![image](https://user-images.githubusercontent.com/117337025/201448925-633c7842-c7e0-4115-bd42-eb842cd90e24.png) <br/>
Click on "SAVE".

37. Click on "SAVE" on top to save the project. <br/>
![image](https://user-images.githubusercontent.com/117337025/201449164-1086fa10-8bd3-4d09-89f1-5d1660610b35.png) <br/>

38. We are now ready to test the extension. Cick on "LAUNCH" in the top menu and click on "OPEN APP PREVIEW PORTAL". <br/>
![image](https://user-images.githubusercontent.com/117337025/201449206-cdcd940b-3302-4624-bdee-5b187d77ff46.png) <br/>

39. The App launches in a new tab. Click on "Service Order and Customer Returns- AP160_Exercise". <br/>
![image](https://user-images.githubusercontent.com/117337025/201449275-c56bc118-3e83-49cd-b398-f8231b355982.png) <br/>
Enter "1710" in the "Sales Org" input Field". <br/>
![image](https://user-images.githubusercontent.com/117337025/201449324-1cd1c853-93b5-4e6c-a2e6-a16650d7a5f1.png) <br/>
Click on "Service Orders". <br/>
![image](https://user-images.githubusercontent.com/117337025/201449350-1b46472b-b86b-45ce-af37-66fa06c5c04a.png) <br/>
Click on "Customer Returns". <br/>


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
