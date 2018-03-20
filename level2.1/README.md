# level 2.1

Now that the app runs locally, you obviously know that you need to deploy it in the production cluster. After a lot thought and hesitation, you decide to attempt to run the dockerized application in production. Given that the only OS you accept in a production environment is Ubuntu 16.04 LTS, you decide to run validate that you can run the app on a fresh Ubuntu 16.04 LTS environment.

Here is our plan: Get a fresh Ubuntu 16.04 and get the app to run on it

- Spin up an Ubuntu 16.04 LTS (on a cloud provider, using vagrant, using virtualbox, using proxmox, whatever ...)
- Setup all pre-requisites
- use the script from level 1 to clone and run the app