
```Javascript

const options = {
	authProvider,
};

const client = Client.init(options);

const calendar = {
  name: "Volunteer"
};

let res = await client.api('/me/calendars')
	.version('beta')
	.post({calendar : calendar});

```