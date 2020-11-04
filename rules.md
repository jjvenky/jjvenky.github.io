---
layout: single
title: Rules
excerpt: "How we work"
modified: 2019-11-07
permalink: /rules/
header:
  overlay_image: assets/images/L305_feature.jpg
#  credit: Jason Venkiteswaran
---

# Rules and Expectations and Goals

There are any number of reasons to establish lab rules incuding safety, philosophy, and expectations. This is how I want my research group to operate:

## General Rules

* Do good science by asking questions early and often, planning ahead, and collaborating.
* Give credit where credit is due.
* Students should be the first author of papers coming from their thesis work. Authorship should be discussed early and generally follows the [ESA's Code](https://www.esa.org/about/code-of-ethics/) – see also the advice of [Schmidt 1987](https://www.jstor.org/stable/20166549), [Hunt 1991](https://10.1038/352187a0), and [Weltzin et al. 2006](https://doi.org/10.1890/1540-9295(2006)4[435:AIEAAA]2.0.CO;2)
* Be safe and help others be safe by thinking about what types of training are needed.
* Publish in [Open Access](http://www.carl-abrc.ca/advancing-research/scholarly-communication/open-access/) venues whenever possible, noting there can be different requrements from each funder.
* Deposit all publications and technical reports on a preprint server such as [bioRxiv](https://www.biorxiv.org/), [EarthArXiv](https://eartharxiv.org/), [ESSOAr](https://www.essoar.org/), etc.
* All data must be organized and stored on the group's [GitHub repository](https://github.com/biogeochem) with the metadata template completed.
* Make available all data and code for each publication via a service like [GitHub+Zenodo](https://guides.github.com/activities/citable-code/), [Pangaea](https://pangaea.de/), etc.
* Have fun.

## Specific Rules

* It is important to interact with others in the group and although our work hours can be very flexible. it is important to be around between 9:30--14:00.
* We have routine lab meetings except during the middle of field season and attendance is expceted. It is an opportunity to present ideas and plans for new research, to show and discuss new data, and to practice presentations. People spend their attention and time to help so please respect this and come prepared.
* Everyone should attend at least one conference or workshop per year if funds are available and time permits. All are expected to apply for additional funds to support attending conferences and workshops. Please send your abstract to all the coauthors at least one week in advance so no one is suprised and people can provide feedback.
* Everyone needs to complete WHMIS training. Everyone doing field work needs to complete Standard First Aid is working close to populated areas and Wildness First Aid in all other cases. Everyone using a boat needs to obtain a [Pleasure Craft Operator Card](https://www.tc.gc.ca/eng/marinesafety/debs-obs-paperwork-paperwork_operator-360.htm). Everyone needs to complete a set of risk assessment forms and provide emergency contact information to be kept on file in the department. No one does field work alone.

## Onboarding

Here is the list of onboarding things to do to help integrate new people into the research group.

### Safety

* [ ] Get a OneCard, remind Jason to email for you to have access to CCRWS and SRC buildings
* [ ] Take for Standard First Aid or Wilderness First Aid (typically by May and recently coordinated with Dean of Science office), email Jason a copy to be kept on file
* [ ] Take Canadian Firearm Safety Course, if working in the north, email Jason a copy to be kept on file
* [ ] Take WHMIS and Compressed Gas Training, [available online](https://mylearningspace.wlu.ca/d2l/lms/legacy/selfregistration.d2l?ou=6605), email Jason a copy to be kept on file
* [ ] Obtain a Pleasure Craft Operator Card, email Jason a copy to be kept on file

### Data

We use git and GitHub to keep track and control of our data, metadata, code, and papers:

* [ ] Make a [GitHub](https://github.com/) account, ask Jason to be added to the appropriate [teams](https://github.com/orgs/biogeochem/teams)
* [ ] [Create a repo on GitHub](https://docs.github.com/en/free-pro-team@latest/github/getting-started-with-github/create-a-repo) and commit a change

We use R and RStudio for organising, analysing, modelling, plotting, etc. our data, sometimes we use [Matlab](https://www.mathworks.com/products/matlab.html) and other softwares like [Jupyter](https://jupyter.org/) and [Python](https://www.python.org/) as needed:

* [ ] Download and install [R](https://cloud.r-project.org/)
* [ ] Download and install [RStudio Desktop](https://rstudio.com/products/rstudio/download/#download)
* [ ] Open RStudio to check that it works and there are no errors
* [ ] Note that Windows users may need [`Rtools`](https://cran.r-project.org/bin/windows/Rtools/) and Mac users may need [`Xcode`](https://developer.apple.com/xcode/) in order to compile R packages that are not available as pre-compiled binaries
* [ ] Install the `tidyverse` and `here` packages since they will be very handy (in RStudio, Tools -> Install Packages, type the names of the packages separated by a comma)
* [ ] New students should work through this [Introduction to R](https://datacarpentry.org/R-ecology-lesson/01-intro-to-r.html) lesson and [Stating with data](https://datacarpentry.org/R-ecology-lesson/02-starting-with-data.html) lesson
* [ ] Often small files will sneak into your repos even if you don't want them to, so *vaccinate your global gitignore* with [usethis::git_vaccinate](https://usethis.r-lib.org/reference/git_vaccinate.html)
* [ ] [Test out creating a repo on GitHub from our template](https://github.com/biogeochem/project_template), enter appropriate metadata that makes sense for your research, commit the change, and push it to GitHub

### Useful Resources

* The [Tidyverse style guide](https://style.tidyverse.org/) is a great resource and following its general recommedations will make your code easier for you to write and easier for other people to follow what you have done.
* Jenny Bryan's [Happy Git and GitHub for the useR](http://happygitwithr.com/) is an excellent reference and learning manual and everyone should walk through many of its chapters when setting up their system
* Karl Bromwn's [git/github guide: a minimal tutorial](http://kbroman.org/github_tutorial/) is also very useful
* The [Data Analysis and Visualization in R for Ecologists](http://datacarpentry.org/R-ecology-lesson/) lessons are an excellent way to learn how to employ R and RStudio to aggregate, analyse, and visualise data

### Finally

- [ ] We use [Slack](https://slack.com/intl/en-ca/) to chat and organise meetings, please ask to be added to the appropriate workspaces: [lab workspace](https://biogeochemlab.slack.com/), [formbloom](http://formbloom.slack.com/), [lugnuts](https://lugnuts.slack.com/), and [samms](https://sammsgwf.slack.com/).

