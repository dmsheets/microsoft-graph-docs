
```Cs

GraphServiceClient graphClient = new GraphServiceClient( authProvider );

var rows = await graphClient.Me.Drive.Items["{id}"].Workbook.Tables["{id|name}"].Rows
	.Request()
	.Skip(5)
	.Top(5)
	.GetAsync();

```