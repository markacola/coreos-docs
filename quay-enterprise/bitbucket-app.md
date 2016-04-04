# Creating an OAuth Application in BitBucket

- Log into BitBucket
- Visit the Settings page for your organization
- Click the "OAuth" tab under "Access Management"
- Click the Add Consumer button:

<img src="img/bb-add-consumer.png" class="image-center"/>

- Enter your registry's URL as the `URL`
- Enter `https://{REGISTRY URL HERE}/oauth2/bitbucket/callback` as the `Callback URL`.
- Grant permissions on the repositories and webhooks:

<img src="img/bb-app-permissions.png" class="image-center"/>

- Save the application
- Note down the `Client ID` and `Client Secret`.

<img src="img/bb-app-info.png" class="image-center"/>
