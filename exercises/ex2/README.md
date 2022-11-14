# Embed a pre-delivered Mashup in SAP Sales and Service Cloud Version 2
The following exercise will provide detailed steps to embed a AppGyver Mashup in SAP Sales and Service Cloud Version 2.

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

## Embed a pre-delivered Mashup
During the next steps, we will embed a pre-delivered AppGyver Mashup in SAP Sales and Service Cloud Version 2.

1. Navigate to Settings. <br/>
   ![image](https://user-images.githubusercontent.com/84871522/199808023-b1958666-8c09-4317-b991-89e3ae87a4cb.png)

2. Navigate to Mashup Authoring. <br/>
   ![image](https://user-images.githubusercontent.com/84871522/199808231-c991038e-2232-453c-b1ee-40c23cc60f34.png)

3. Ensure that the pre-delivered mashup "TechEd Demo - Service Order Create" is available in the list. This will be the mashup that we will be embedding in Agent Desktop. <br/>
   ![image](https://user-images.githubusercontent.com/84871522/199808381-4f3e250c-4f5f-4009-a435-246e5cfab19b.png)

4. Navigate to the module switcher, and choose Agent Desktop. <br/>
   ![image](https://user-images.githubusercontent.com/84871522/199808586-dcdf0a93-c27e-4d11-a5a6-b668ce599079.png)

5. A new tab opens, displaying the Agent Desktop. <br/>
   ![image](https://user-images.githubusercontent.com/84871522/199808932-a71a79d0-cc83-4eee-ad6f-8910a99a008a.png)

6. Search for the Account "Delbont" and Click on "Confirm" button for the account name. <br/>
   ![image](https://user-images.githubusercontent.com/84871522/199809064-20e2ce92-91fb-4990-93bf-8a7e85d88b34.png)

7. A new tab opens, displaying the "Customer Hub". <br/>
   ![image](https://user-images.githubusercontent.com/84871522/199809388-d49aa9a1-d16f-4180-8607-664495576735.png)

8. Click on the User Profile -> Start Adaptation. <br/>
   ![image](https://user-images.githubusercontent.com/84871522/199809514-1efe9435-004d-4aea-9d68-f123361a4f8b.png)

9. The application will be displayed in adaptation mode. <br/>
    ![image](https://user-images.githubusercontent.com/84871522/199809634-4d9cd954-6c30-451d-aab0-b0e40e22f1c9.png)

10. Hover over the "What would you like to do?" section and Click on the Edit (pencil) icon. <br/>
    ![image](https://user-images.githubusercontent.com/84871522/199809748-c40eae98-c8e0-4c0d-b67a-a134ca40811b.png)

11. "Section Items" pop up would be displayed. Here, click on the "Create Button" (+) icon. <br/>
    ![image](https://user-images.githubusercontent.com/84871522/199809844-cda1ac84-9098-4fa3-98a4-eb5ff2b4a22e.png)

12. A new popup "Add Buttons" opens. Add the Button Name and Event name for the button. Then click "Apply". <br/>
    ![image](https://user-images.githubusercontent.com/84871522/199810150-5738d2c6-669c-47c1-b7fc-50cbf64b7849.png)

13. The new button will be added in the "What would you like to do?" section. <br/>
    ![image](https://user-images.githubusercontent.com/84871522/199810251-b5f64c89-422b-4558-b3bf-a73ca5cc3c0b.png)

14. Hover over the tabs section and Click on the Edit (pencil) icon. <br/>
    ![image](https://user-images.githubusercontent.com/84871522/199810974-5d58284b-698a-47d4-9da9-904c7074da57.png)

15. "Edit Tabs" popup would be displayed. Here, click on the "Create Tab" (+) icon. <br/>
    ![image](https://user-images.githubusercontent.com/84871522/199811281-c0919ba4-9407-475d-b963-dab2537263e1.png)

16. Add new tab name and click ">" button displayed in front of it. <br/>
    ![image](https://user-images.githubusercontent.com/84871522/199811438-4e85eb11-1f94-4fc9-9880-68850cce2fff.png)

17. Check the "Show on Event Trigger" checkbox and select the Event we added in Step 13. Then click "Apply". <br/>
    ![image](https://user-images.githubusercontent.com/84871522/199811601-88d66bca-7fa2-4cfd-9b09-7229c6403c8c.png)

18. The new tab will be added. <br/>
    ![image](https://user-images.githubusercontent.com/84871522/199811738-c6a4aebb-1881-4552-9a3e-ab72eece0984.png)

19. Click on the newly added tab in the above step and Click on the Edit (pencil) icon displayed for the tab. <br/>
    ![image](https://user-images.githubusercontent.com/84871522/199811954-c9ff0edf-c990-4f43-aec4-f4da0b0ba48e.png)

20. "Configure Tab" pop up will be displayed. Click on the ">" displayed in front of Add Mashup. <br/>
    ![image](https://user-images.githubusercontent.com/84871522/199812063-69d6ecf2-337d-4a15-b75e-0fa6c1bd5633.png)

21. A new pop up showing all the Mashups would display. <br/>
    ![image](https://user-images.githubusercontent.com/84871522/199812167-a23db0fa-cc0d-41eb-acc9-83b15d41ea50.png)

22. Search for the Mashup we searched in step 4 and click on ">" displayed in front of the mashup name. <br/>
    ![image](https://user-images.githubusercontent.com/84871522/199812399-bf728c25-7a94-4be9-8f41-dda0107be597.png)

23. "Edit Properties" pop up would display. For "sap-soldtoparty" parameter, select "Fields/Default External Business Partner ID". <br/>
    ![image](https://user-images.githubusercontent.com/84871522/199812668-2d7b9ff6-f760-457d-9777-a5a2ca04bee1.png)

24. Click Apply in the "Edit Properties" pop up. <br/>
    ![image](https://user-images.githubusercontent.com/84871522/199813798-72d0137d-9b48-4309-a3a6-e14c7d2a488e.png)

25. The selected mashup would be displayed in the tab. Then end the Adaptation mode by clicking the "End Session" button on the orange bar on top of the page. <br/>
    ![image](https://user-images.githubusercontent.com/84871522/199814061-d5d8d3d1-a299-405a-b141-de817a4d632c.png)

26. Now, whenever you click on the new button we added in step 14 then the new tab which we added in step 19 will be displayed along with the selected Mashup. Your Mashup is embedded!!!
    ![image](https://user-images.githubusercontent.com/84871522/199814158-3d88d57c-6132-4e03-a1aa-39b9fb3f7505.png)
