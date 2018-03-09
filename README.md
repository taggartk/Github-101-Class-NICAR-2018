# Github-101-Class-NICAR-2018
Materials for Github 101 for journalists taught at IRE/NICAR conference in March 2018

### Some newsrooms that share their methodologies:

* [538](https://github.com/fivethirtyeight/data)
* [ProPublica](https://github.com/propublica)
* [USA Today](https://github.com/USATODAY)
* [BuzzFeed News](https://github.com/BuzzFeedNews)

### What this class will cover: 

* What is GitHub? Why is it useful for journalists? 

  1. Learn from/build upon other people’s work! Use other reporters’ analyses and download data for your own stories.
  
      Examples:
     * BuzzFeed News' '[Trump World](https://github.com/BuzzFeedNews/trumpworld)', a list of more than 1,500 people and organizations connected to the  administration.
     * ProPublica's [Facebook Political Ad Collector](https://github.com/propublica/facebook-political-ads)
  
  2. Share your own work with the world!
  
  3. Track changes — helpful for the same reasons you might want to go back to an earlier draft in a story. But also helpful if you want to track changes to a dataset you regularly update to see what’s new.

### Hands on exercises

**1. Make your own project (‘repo’).**

* Add some text to the readme

    A readme is the landing page of your repo, where you explain what’s in the repo and any caveats people should be aware      of before diving into your data and analysis.

* ‘Commit’ changes

* Make a branch

* Make a pull request, check out the differences and if everything looks good, merge with master.

Now turn to your neighbor and make a branch on their repo. Suggest changes or add language to their readme. And make a pull request.

**2. Checking out differences in new data**

  The [`SAM_Exclusions_Public_Extract_2017-01-17.CSV.zip`](SAM_Exclusions_Public_Extract_2017-01-17.CSV.zip) file contains data about entities that were prohibited from receiving federal contracts as of January 1, 2017. 

  To make things easier for this class, we've pulled out a slice of that data to work with:
  
  1) [`FEMA.csv`](FEMA.csv) contains all individuals and firms the Federal Emergency Managment Agency (FEMA) added to this list. 
  2) [`FEMA_SAMnum.csv`](FEMA_SAMnum.csv) contains the unique identifier for each of those entities
  
  If you want to dig into this further, the most recent data can be downloaded [here](https://catalog.data.gov/dataset/system-for-award-management-sam-exclusions-extract-data-package).
  
  We're going to make a new branch to add data from March 3, 2018. You can download that data [here](https://drive.google.com/drive/folders/1zNmfmNE6VVPOXklYtrO0_adb5GmWECnV?usp=sharing).

### Resources:

* This [guide](https://guides.github.com/activities/hello-world/) from Github is a good introduction to the ideas and terms you'll need to know.

* An [example](https://github.com/dannguyen/simplestuff-sqlite) of how to show your work to the world if you use SQL (also a good resource if you're trying to learn SQL).

* Here's a [guide](https://guides.github.com/features/mastering-markdown/) to using Markdown.
