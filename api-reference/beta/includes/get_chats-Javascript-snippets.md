
```Javascript

const options = {
	authProvider,
};

const client = Client.init(options);

let res = await client.api('/users/{id}/chats')
	.version('beta')
	.get();

```