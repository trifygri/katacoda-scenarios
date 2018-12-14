# katacoda-scenarios (darwin)
*the text that follows is work in progress. It has probably errors. Use at your own risk*

  https://www.katacoda.com/
## how to set up your environment
1. create a scenario directory on your machine and add to git

  ```
  mkdir katacoda-scenarios
  cd katacoda-scenarios
  echo "# katacoda-scenarios" >> README.md
  git init
  git add README.md
  git commit -m "first commit"
  git remote add origin https://github/your_username/katacoda-scenarios.githubgit push -u origin master
  ```
1. create a profile (account) on

  https://katacoda.com/signup
1. if you take the security risk, install the katacoda cli on your system by executing

 `curl -s https://cli.katacoda.com | sudo sh`

 (Golang static compiled binary installed into /usr/local/bin)

 https://katacoda.com/cli

1. Create a Github Webhook

  https://katacoda.com/docs/configure-git
1. create a new scenarios

  `katacoda c s`

  and name it i.e.
  **first**

1. make your changes to the template files and

  `git add .`

   them and push by

  `katacoda push`
1. now you have your first katacoda scenario published

  https://katacoda.com/your_username/first
