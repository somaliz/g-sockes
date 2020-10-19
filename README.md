
### Setup Process

* Install requirements

* Run "python2 ./g_socks.py --setup" and follow the instructions
  * [Create a Google API Project](https://console.developers.google.com/projectcreate)
  * [Create OAuth client ID credentials for the project](https://console.developers.google.com/apis/credentials)
  * [Download the JSON for those credentials](https://console.developers.google.com/apis/credentials)
  * Move the credentials file to the google_socks directory and name it "client_secrets.json"
  * Next, the setup script will give you a Google link and ask for a secret
  * Follow the link, authorize the script to use the API, and receive the secret
  * Paste the secret back into the setup script's prompt
  * [Copy the provided python code into the g_socks.py file below "# PASTE NEW CREDENTIALS HERE"](https://github.com/somaliz/g_socks/blob/master/g_socks.py#L28)
  * [Enable the Google Drive API](https://console.developers.google.com/apis/api/drive.googleapis.com/overview)
  * All done!
* Read the help information here: "python ./g_socks.py -h"

### Requirements 
    pip2 install google-auth google-auth-oauthlib google-auth-httplib2 python-dateutil google-api-python-client

