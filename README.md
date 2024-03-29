## I can't create a labs tenant!

![New tenant limit](https://cdn.auth0.com/website/auth0-labs/od/faqs/new-tenant-limit.png)

Free tier Auth0 accounts created after October 31, 2023 are now limited to one development/staging environment and one production environment. You can use the default tenant (starts with `dev-`) for these labs. We always recommend using a fresh development tenant to ensure all configurations are at their defaults. 

## I accidentally closed or lost the CodeTour panel

If you've accidentally closed or lost the CodeTour panel, you can reopen it. Expand the CodeTour section in the right panel of your Codespace and select the step that you completed. The CodeTour panel will reappear.

![Reopen CodeTour](https://cdn.auth0.com/website/auth0-labs/od/faqs/reopen-codetour.gif)


## I signed into the wrong Auth0 tenant

You can check which tenant you are signed into at the bottom of the Codespaces window. If you are signed into the wrong tenant, click this area and two options will pop up at the top of the window. Simply select **Switch tenant** and you can select the correct tenant in the tab that opens.

![Switch Tenants](https://cdn.auth0.com/website/auth0-labs/od/faqs/switch-tenants.gif)

## I’m missing an .env file for my application / My application doesn’t launch

Sometimes your application won't launch correctly because you don't have a configuration set up in a `.env` file. The `.env` file is created by the Auth0 Labs extension, but it will only be created if you are logged in to the correct tenant (See: [*I signed into the wrong tenant*](#i-signed-into-the-wrong-auth0-tenant)) and you have named your application exactly as instructed by the lab.

In order to re-run the command that will create the `.env` file, open VSCode’s Command Palette (CMD+SHIFT+P on Mac or CTRL+SHIFT+P on Windows), type in **Auth0**, and select **Auth0: Configure Local Environment**. 

![Switch Tenants](https://cdn.auth0.com/website/auth0-labs/od/faqs/config-local.png)

You can then check if the `.env` file was successfully created (in `src/web-app` for the Web App,  `src/api` for the API, and `src/spa-app` for the SPA app).

## I'm getting a 503 when I attempt to visit my app

This may be due to the Codespaces port-forwarding service being down. You can check GitHub's Codespace service status [here](https://www.githubstatus.com/). 

You can work around this by opening your Codespace in the VSCode Desktop application (you will need to download [VSCode](https://code.visualstudio.com/) to your local machine if you do not already have it):
1. From your Codespace, open the Command Palette by pressing `CTRL`+`SHIFT`+`P` (Windows) or `CMD`+`SHIFT`+`P` (Mac)
2. Type in VSCode and select the following **Open in VS Code Desktop**:
    ![VSCode Command Palette](https://cdn.auth0.com/website/a0fun/v2/vscode-command-palette.png)
3. This will open VS Code and pop up a message that you can close your browser window.
4. If you don't already have the GitHub Codespaces extension installed, VSCode will prompt you to do so.
5. Once your Codespace is open in VSCode, proceed with the lab as normal.

#### For all other lab issues, contact [educationondemand@okta.com](mailto:educationondemand@okta.com). For general training questions, contact [training@okta.com](mailto:training@okta.com).

