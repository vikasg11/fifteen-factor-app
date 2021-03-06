### I.	Codebase
One codebase is tracked in version control. There is only one codebase per application, but there will be many deploys of the application.
The codebase is the same across all deploys, although different versions may be active in each deployment. For example, a developer has some commits not yet deployed to staging; staging has some commits not yet deployed to production.

![15FactorApp-CodeBase.jpg](./images/15FactorApp-CodeBase.jpg)

For a quick start, you can create or clone the existing repository.

#### Clone an exisiting Git Repository -
```sh
  $ git clone git@github.com:vikasg11/15-factor-app.git
  $ cd fifteen-factor-app
```


#### Create a new Git Repository -
```sh
  $ git init
```
This command should be run from the root of the application. Add the necessary files from your preferred framework to the folder and commit.

```sh
  $ git add .
  $ git commit -m "Inital commit for the application"
```
Finally, you can add a remote and push our commits to the remote if you wish to:

```sh
  $ git remote add origin https://github.com/<username>/fifteen-factor-app.git
  $ git push -u origin master
```