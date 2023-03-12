# Auth0 SAML Cloudflare Zero trust

1. Sign up Auth0 (https://auth0.com/signup)

2. Create User
![](./1.usermanagement.png)

![](./2.createuser.png)

3. Create an Application → Applications > Applications

![](./3.application.jpg)

4. Give it a name eg. Cloudflare Access and select **Single Page Web Application**

![](./4.cloudflareaccess.png)


Addon SAML2 Web App → Under this Application > Addons > **Select SAML2 WEB APP**

![](./4.SAML2.png)


Select **Settings** \
Under **Application Callback URL** input  https://<your-team-name>.cloudflareaccess.com/cdn-cgi/access/callback

<your-team-name> can be found under **Cloudflare Zero Trust > Setting > General Settings**

![](./6.callback.png)
