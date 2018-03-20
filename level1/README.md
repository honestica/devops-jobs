# The backstory

One of the developers on the team went through a rails tutorial on friday night and loved it. He/She decided to implement a new tool in it. By monday morning 10am, he/she had a rails-based webapp that solves a crucial need for the support team, that had been raised the previous week. The manager of the support team saw the app and went running to the company CTO who pulled you (the devops in charge!) in with this inquiry : "Can you deploy this app by the end of the day?".

Here is our plan:
- The app the developer provided is : https://github.com/honestica/docker-compose-rails-dev-example
- The developer provided a dockerfile and a docker-compose file saying that they were super easy to use and to get going with. Let's validate this claim ...

# Level 1

- follow the instruction in the repo provided to setup any pre-requisites
- clone the app repo
- Deploy the app locally and make sure it runs at : `http://localhost:3000`
- Include whatever commands you needed to clone the repo and modify or launch the app, into a shell script that can be used on a fresh environment where the pre-requisites are already installed.