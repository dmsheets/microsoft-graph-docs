
```Javascript

const options = {
	authProvider,
};

const client = Client.init(options);

let res = await client.api('/users/{userId}/drives')
	.version('beta')
	.get();

```