## I can't create a labs tenant!

![New tenant limit](https://cdn.auth0.com/website/auth0-labs/od/faqs/new-tenant-limit.png)

Auth0 accounts created after October 31, 2023 are now limited to one development/staging environment and one production environment. You can use the default tenant (starts with `dev-`) for these labs. We always recommend using a fresh development tenant to ensure all configurations are at their defaults. 

## I accidentally closed or lost the CodeTour panel

If you've accidentally closed or lost the CodeTour panel, you can reopen it. Expand the CodeTour section in the right panel of your Codespace and select the step that you completed. The CodeTour panel will reappear.

![Reopen CodeTour](https://cdn.auth0.com/website/auth0-labs/od/faqs/reopen-codetour.gif)


## I signed into the wrong Auth0 tenant

You can check which tenant you are signed into at the bottom of the Codespaces window. If you are signed into the wrong tenant, click this area and two options will pop up at the top of the window. Simply select **Switch tenant** and you can select the correct tenant in the tab that opens.

![Switch Tenants](https://cdn.auth0.com/website/auth0-labs/od/faqs/switch-tenants.gif)

## I’m missing an .env file for my application / My application doesn’t launch

Sometimes your application won't launch correctly because you don't have a configuration set up in a `.env` file. The `.env` file is created by the Auth0 Labs extension, but it will only be created if you are logged in to the correct tenant (See: [*I signed into the wrong tenant*](#i-signed-into-the-wrong-auth0-tenant)) and you have named your application exactly as instructed by the lab.

#### For all other lab issues, contact [educationondemand@okta.com](mailto:educationondemand@okta.com). For general training questions, contact [training@okta.com](mailto:training@okta.com).

