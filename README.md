# ExcelRead
Fetch data from multiple excel files in c#

Files path, columns to select and constraints are taken from app.config

In FilteredData.cs in AppCode filtered data is fetched from multiple files in the form of datatable via OleDB SQL command using async/await and Task.WhenAll

In FilterUsingLINQ.cs in AppCode data is fetched from multiple files and then filtered by iterating through the data.
Tried to using LINQ for filter but failed because of a error of type cast while applying LINQ on DataTable.
