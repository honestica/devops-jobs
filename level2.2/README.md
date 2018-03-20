# level 2.2

Now that you're able to run the app on an Ubuntu 16.04 LTS, you realize that you need to be able to deploy a staging environment and a production environment for this app since it's going to be in agile mode. Therefore, you want to make sure staging and production are identical setups.

Here is our plan: capture the pre-requisites identified in level 2.1 and include them in a configuration management tool.

- Capture the pre-requisites install steps in a configuration management recipe/playbook/etc in a way that it can be run against an Ubuntu 16.04 LTS remotely (specify any potential requirements for this step itself).
- Include also the script from level 1 (or the steps it represents) into this configuration management recipe/playbook/etc
- describe how this can be run on a fresh Ubuntu 16.04 environment and in one command get a functional web app.