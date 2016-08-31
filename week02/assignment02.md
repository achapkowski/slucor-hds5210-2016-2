_SLUCOR HDS5210 - Programming for Health Data Science - 2016 Fall_

Week 2 (Aug 31) Exercises
===
References:
* http://www.tldp.org/LDP/Bash-Beginners-Guide/html/Bash-Beginners-Guide.html
* https://en.wikipedia.org/wiki/Unix_philosophy
* http://datascienceatthecommandline.com/
* http://datascienceatthecommandline.com/#tools

#1 - Git setup
---
Make sure that you've followed the instructions from class to setup the Juypter environment can access your GitHub.com account.

https://github.com/paulboal/slucor-hds5210-2016-2/blob/master/week02/setup-github.ipynb

#2 - Create a GitHub repository
---

Starting at http://github.com follow these instructions to create a new repository:

1. Click the green `New repository` button on the right side of the screen most of the way down.
2. Name your repository `hds5210-week02`
3. Make it a private repository _if that option is available_
4. Check _Initialize this repository with a README_
5. Click `Create repository`

If you were able to create a private repository, follow these additional steps.
1. Click `Settings` in the upper-right
2. Click `Collaborators` on the left
3. Add `paulboal` and `ewesthus` to your list of collaborators

#3 - Clone this repository and add a new .ipynb file
---
Go into Jupyter and follow these instructions to clone this repository and then create a new notebook inside of it.

1. Click the `Launch Shell` button
2. Click `Connect`
3. Type in your gitlab username and `P@SSw0rd` for you password to login
4. Follow the commands below using your own gitlab username

```
cd notebooks
git clone git@github.com:paulboal/hds5210-week02.git
```

5. Back in Jupyter, choose `File->Open`
6. Navigate into your new project directory
7. Click `New` and select `Python 3`
8. Click `Untitled` at the top to give the notebook name: "week02-`username`"
Do all the rest of these exercises within that new notebook you created.

#4 - Python Exercise
---
In that new notebook, solve the following problem:

According to http://health.costhelper.com/tonsil-removal.html, the average cost of a tonsillectomy is $5,442 for someone paying out of pocket without insurance.  The out of pocket cost for someone with a typical insurance plan is about $2,000.  If 2% of 10 to 14 year old kids in Missouri get their tonsils removed this year, and only 50% of those families are covered by insurance, what is the total out of pocket cost for tonsillectomies for Missouri families for this year.  

Use https://suburbanstats.org/population/how-many-people-live-in-missouri as your source for the number of 10 to 14 year olds in Missouri.

As usual, show your work and thought process through readable code and comments as needed.

#5 - Commit and push your work to gitlab
---

1. Make sure you notebook changes above are saved.
2. Click the `Launch Shell` button
3. Click `Connect`
4. Type in your gitlab username and `P@SSw0rd` for you password to login
5. Follow the commands below using your own gitlab username
```
git cd ~/notebooks/hds5210-week02/
git add week02-paulboal.ipynb
git commit -a -m "Adding homwork"
git push
```
