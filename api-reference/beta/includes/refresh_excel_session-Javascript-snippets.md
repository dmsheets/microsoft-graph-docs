
```Javascript

const options = {
	authProvider,
};

const client = Client.init(options);

const refreshSession = {

};

let res = await client.api('/me/drive/items/{id}/workbook/refreshSession')
	.version('beta')
	.post(refreshSession);

```