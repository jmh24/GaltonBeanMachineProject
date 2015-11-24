# GaltonBeanMachineProject 

This is the code for a Galton Bean Machine. This is a demonstration of probability.

## Console output

### Getting the README file started.

This is how to change to the T drive.

```
C:\Users\LAB>cd T:
T:\

C:\Users\LAB>T:

T:\>cd DiscreteStructures

T:\DiscreteStructures>cd GaltonBeanMachineProject


```
This is where we add the README file.

```

T:\DiscreteStructures\GaltonBeanMachineProject>echo # GaltonBeanMachineProject >
> README.md

```
This is how to get GitHub on track with our local Eclipse file, so that it can now be pushed and pulled to the
repository.

```

T:\DiscreteStructures\GaltonBeanMachineProject>git init
Initialized empty Git repository in T:/DiscreteStructures/GaltonBeanMachine
Project/.git/

T:\DiscreteStructures\GaltonBeanMachineProject>git add README.md

T:\DiscreteStructures\GaltonBeanMachineProject>git commit -m "first commit"

```
Tell the local machine who is editing the repository

```

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'LAB@STF126L-PC.(none)')

T:\DiscreteStructures\GaltonBeanMachineProject>git config user.name "Jaclyn Hamm
ond

T:\DiscreteStructures\GaltonBeanMachineProject>git config user.email "jaclynmh06
24@yahoo.com"

```
Since the last commit didn't go through due to the machine asking who I am, commit again

```
T:\DiscreteStructures\GaltonBeanMachineProject>git commit -m "first commit"
[master (root-commit) 80fb50b] first commit
 1 file changed, 1 insertion(+)
 create mode 100644 README.md

```
Connect the local repository to the repository you created on GitHub for the project

```

T:\DiscreteStructures\GaltonBeanMachineProject>git remote add origin https://git
hub.com/jmh24/GaltonBeanMachineProject.git

T:\DiscreteStructures\GaltonBeanMachineProject>git push -u origin master
Username for 'https://github.com': jmh24
Password for 'https://jmh24@github.com':
Counting objects: 3, done.
Writing objects: 100% (3/3), 247 bytes | 0 bytes/s, done.
Total 3 (delta 0), reused 0 (delta 0)
To https://github.com/jmh24/GaltonBeanMachineProject.git
 * [new branch]      master -> master
Branch master set up to track remote branch master from origin.

T:\DiscreteStructures\GaltonBeanMachineProject>