
```Cs

GraphServiceClient graphClient = new GraphServiceClient( authProvider );

await graphClient.Me.Drive.Items["{id}"].Workbook.Tables["{id|name}"].Sort
	.Clear()
	.Request()
	.PostAsync()

```