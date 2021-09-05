# ETG-IMS-ASSIGNMENT
This repository contains multiple functions and JSON files for inventory management system.<br/>

**IDE USED IS VSCODE Jupyter Notebook**
<br/>

**To download working code only download Final Function folder**<br/>

**Working of code is as follows:**<br/>
<br/>
1.RUN ALL THE CELLS OF THE CODE EXCEPT In[42] and In[43] if want to see precious transactions else new transactions will be available in the SalesRecord.json and PersonRecord.json<br/>

2.After In[48] cell is there a sample to show the working of the code after step 1 is followed.<br/>

3.filename(as parameter in function) are the names of the JSON files.<br/>

**STEPS TO PERFORM A SINGLE TRANSACTION**
<br/>
1. Perform step 1 from earlier<br/>
2. check=readfile("records.json")<br/>
3. display(check)<br/>
4. purchase(check)<br/>
5. GenerateReceipt("PersonRecord.json")<br/>
6. GenerateSalesRecord("salesRecord.json") #This will show sales done till that time,max sold product till that time,total sale value till that time.<br/>
7. IF YOU WANT TO SEE HOW INDIVIDUAL FUNCTIONS ARE WORKING THEN THERE ARE NOTEBOOKS IN INDIVIDUAL FUNCTIONS(INDEPENDENT OF OTHER FUNCTIONS).<br/>
<br/>
**To see working of each individual Function also download INDIVIDUAL FUNCTIONS folder**<br/>




#**INDIVIDUAL FUNCTIONS**
<br/>
1. AddInAlreadyCreatedJSON.pynb: This is to add a new record in already existing record.json file.<br/>
2. CreateNewJSON.ipynb: This is to create a new record.json file from scratch and add all the records in the inventory from zero.<br/>
3. Display.ipynb: This is to display all the records of the records.json file.<br/>
4. GenerateReceiptIndividual: This is to generate the receipt for the products customer bought and also record it in personrecords.json file.<br/>
5. MaxSoldProduct.ipynb: This will return details of the max sold product.<br/>
6. RemoveFromInventory.ipynb: This is to remove record from inventory having values <=0.<br/>
7. SalesRecordIndividual: This will record all the purchases in salesrecord.json file.<br/>
8. purchase.ipynb: This is just earlier version of GenerateReceiptIndividual.<br/>
9. Person Records JSON File will have the records of Customer buying things from store.<br/>
10.Records JSON file will have Records of the items available in the Inventory.<br/>
11.Sales Record JSON will have all the records of the items sold in a day.<br/>
 
#**Final Function**
<br/>
1.Person Records JSON File will have the records of Customer buying things from store.<br/>
2.Records JSON file will have Records of the items available in the Inventory.<br/>
3.Sales Record JSON will have all the records of the items sold in a day.<br/>
4.Having All In One notebook have all the functions to access and modify the JSON Files.<br/>


NOTE:**RUN THE CELL SALESRECORDS={} AND PERRECEIPT={} ONLY ONCE AS IT WILL EMPTY THE RECORDS AND ALL THE PURCHASE RECORDS MIGHT BE LOST IF CREATEFILE() FUNCTION WASN'T CALLED TO STORE IT IN LOCAL FILE**

**Having all in one file is attached below:**

[HavingAllInOne.pdf](https://github.com/heisenberg-7/ETG-IMS-ASSIGNMENT/files/7111103/HavingAllInOne.pdf)





