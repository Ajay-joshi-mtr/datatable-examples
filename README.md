# datatable-customized
Using DataTables plug-in for jQuery https://datatables.net

<a href="https://dtexample.000webhostapp.com/DataTable.htm" target="_blank">Demo</a>

Having functionalities such as : 
1. Search ✅
2. Sort ✅
3. Expand Row
4. Edit Row (Inline) ✅
5. Edit Multiple Rows (Inline) ✅
6. Fix Column/s
7. Custom Coloring
8. Column Visibility
9. Multiple Header Rows (With/Without Colspan)


## Example of Table Meta format that should be returned by GetTableMeta request
```javascript
{"Column":[
{"Name":"ORD_NUM","Editable":true,"Searchable":true,"Class":"ORD_NUM"},{"Name":"ORD_AMOUNT","Editable":true,"Searchable":true,"Class":"ORD_AMOUNT"},{"Name":"ADVANCE_AMOUNT","Editable":true,"Searchable":true,"Class":"ADVANCE_AMOUNT"},{"Name":"ORD_DATE","Editable":true,"Searchable":true,"Class":"ORD_DATE"},{"Name":"CUST_CODE","Editable":true,"Searchable":true,"Class":"CUST_CODE"},{"Name":"AGENT_CODE","Editable":true,"Searchable":true,"Class":"AGENT_CODE"},{"Name":"ORD_DESCRIPTION","Editable":true,"Searchable":true,"Class":"ORD_DESCRIPTION"},{"Name":"ID","Editable":false,"Searchable":false,"Class":"ID"}
],
"Name":"TableNameHere"}
```
## Example of Table Data format that should be returned by GetTableData request
```javascript
{"draw":1,"recordsTotal":34,"recordsFiltered":34,"data":[{"ID":1,"ORD_NUM":"200100","ORD_AMOUNT":"1000","ADVANCE_AMOUNT":"600","ORD_DATE":"8/1/2008 12:00:00 AM","CUST_CODE":"C00013","AGENT_CODE":"A003  ","ORD_DESCRIPTION":"TYU"},{"ID":2,"ORD_NUM":"200101","ORD_AMOUNT":"3212","ADVANCE_AMOUNT":"1000","ORD_DATE":"7/15/2008 12:00:00 AM","CUST_CODE":"C00001","AGENT_CODE":"A008  ","ORD_DESCRIPTION":"TYU"}]}
```
## Example of UpdateTableData request that should be handled appropriately on Server's side 
```javascript
Form Data : ORD_NUM=200103&ORD_AMOUNT=15001&ADVANCE_AMOUNT=700&ORD_DATE=5/15/2008 12:00:00 AM&CUST_CODE=C00021&AGENT_CODE=A005  &ORD_DESCRIPTION=SODe&rowid=4
```



## Support

Reach out to me at one of the following places!

- LinkedIn at <a href="https://www.linkedin.com/in/shubham-sinha7" target="_blank">`here`</a>
