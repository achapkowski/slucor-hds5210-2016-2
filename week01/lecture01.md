# Week 01 - Computing Fundamentals (Aug 24)
_Gries Ch 1, 2_

## Introductions
You can find some background on me on the SLUCOR website: http://www.slu.edu/medicine/slucor/paul-boal-bs

Tell me about each of you:
* Name
* Educational background
* Professional background
* Personal goals for this program and Course

## Course Introduction
* Solid foundation for computing
* Learn a core set of Python programming techniques
* All with a focus on data management, processing, and analysis

## Syllabus
* See (SYLLABUS.md)[../SYLLABUS.md]

# Get Everyone Setup
* GitHub.com account
* Sign in to https://jupyter.slucor.net
* Run the instructions below in a new notebook

```
%%bash
cd ~
rm -rf .ssh
ssh-keygen -t rsa -N \"\" -f ~/.ssh/id_rsa -q
cat ~/.ssh/id_rsa.pub
```

Take the value you get from above and add it as an SSH key in GitHub.com.
1. Login to GitHub.com
2. Click your profile image in the upper-right corner and choose `Your Profile`
3. Click `Edit Profile` in the upper-right corner
4. Choose `SSH and GPG Keys` from the left-hand menu
5. Click `New SSH Key` in the upper-right corner
6. Use a title of something like `SLUCOR` and then paste the text from above into the key text box.
7. Click `Add SSH Key`

```
%%bash
rm -rf slucor-hds5210-2016-2
echo -e "Host github.com\n\tStrictHostKeyChecking no\n" >> ~/.ssh/config
git clone git@github.com:paulboal/slucor-hds5210-2016-2.git
ls -l slucor-hds5210-2016-2
```

# Introducing Python
See lecture01.ipynb
