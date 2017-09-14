# google-drive-search-files
PHP script which search files in your Google drive

## Install:

**Turn on the Drive API**

1. Use [this wizard](https://console.developers.google.com/start/api?id=drive) to create or select a project in the Google Developers Console and automatically turn on the API. Click **Continue**, then **Go to credentials**.
2. On the **Add credentials to your project** page, click the **Cancel** button.
3. At the top of the page, select the **OAuth consent screen** tab. Select an **Email address**, enter a **Product name** if not already set, and click the **Save** button.
4. Select the **Credentials** tab, click the **Create credentials** button and select **OAuth client ID**.
5. Select the application type **Other**, enter the name "Drive API Quickstart", and click the **Create** button.
6. Click **OK** to dismiss the resulting dialog.
7. Click the **download** (Download JSON) button to the right of the client ID.
8. Move this file to your working directory and rename it *client_secret.json*.
9. Install php 7 cli, composer.
9. `composer install`.
10. `php findfile.php {filename}`.