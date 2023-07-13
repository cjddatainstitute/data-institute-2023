# Data Institute 2023
For students of [The Data Institute](https://cjddatainstitute.org/), a collaboration between the Center for Journalism & Democracy and the Ida B. Wells Society for Investigative Reporting.

We'll use this page to add all the materials used to teach the [2023 Data Institute](https://cjddatainstitute.org/2023/): slides, exercises, links, and homework. This is not an online course and won't have all the context or instruction to be a standalone class.

Want to use our slides? Our teaching materials fall under the [Creative Commons license](https://creativecommons.org/licenses/by-nc-nd/3.0/us/).

# Curriculum

## Table of Contents
- [Install Party](#welcome-reception--install-party)

Week 1:
- [Day 1: Intro to Data Journalism, Spreadsheets, Best Practices](#day-1)
- [Day 2: Evaluating data, Open Refine, Analyzing One Variable](#day-2)
- [Day 3: Intro to Mapping, Common Calculations in News, Analyzing Two Variables, Statistics](#day-3)
- [Day 4: Visualizing Data, Charts and Maps](#day-4)
- [Day 5: Intro to Code, How Websites Work, HTML, CSS](#day-5)


Week 2:
- [Day 6: Intro to Design, Type, Layout & Color, Making a Webpage with Github](#day-6)
- [Day 7: Web Scraping, Fundamentals of Programming](#day-7)
- [Day 8: Even More Web Scraping](#day-8)
- [Day 9: Field Trip / TBD!](#day-9)
- [Day 10:  Final Presentations](#day-10)

## Welcome Reception & Install Party

**ACCOUNTS**
<ul>
  <li><a href="https://github.com/join?source=header-home">Github.com</a><br>(Make sure to confirm your e-mail address)</li>
  <li><a href="https://accounts.google.com/SignUp?service=wise&amp;continue=https%3A%2F%2Fdrive.google.com%2F%23&amp;ltmpl=drive">Google.com</a></li>
  <li><a href="https://app.datawrapper.de/signin">Datawrapper</a></li>
</ul>

**SOFTWARE**
- <a href="https://www.google.com/chrome/browser/desktop/">Google Chrome</a> - Everything we'll be teaching you about previewing and testing code will work in other browsers like Firefox, Safari, and Internet Explorer, but each browser designs how it works a little differently. Since we'll be demoing everything in Chrome, it'll be easiest for you to follow along.
- Slack (<a href="https://itunes.apple.com/app/slack/id803453959?ls=1&amp;mt=12">Mac</a>, <a href="https://slack.com/ssb/download-win">Windows</a>) - All of you should have received an invite to join the Data Institute Slack. If you've never used Slack before, it's basically a place where you can message with a group of people. You need both an account (which you should be able to set up based on your email invitation) and we want you to download the desktop app (which you can do by clicking on the Mac or Windows link above).
- Sublime Text (<a href="https://download.sublimetext.com/Sublime%20Text%20Build%203211.dmg">Mac</a>, <a href="https://download.sublimetext.com/Sublime%20Text%20Build%203211%20Setup.exe">Windows</a>) - This app is where we're going to be writing all our code. It's completely free, and will occassionally ask you if you'd like to pay, but payment is not required. For both beginners and experts, Sublime is one of the best apps for coding.
- <a href="https://desktop.github.com/">Github Desktop App</a> - an app to simplify your Github experience.
- Tabula (<a href="https://github.com/tabulapdf/tabula/releases/download/v1.2.1/tabula-mac-1.2.1.zip">Mac</a>, <a href="https://github.com/tabulapdf/tabula/releases/download/v1.2.1/tabula-win-1.2.1.zip">Windows</a>) - Your best friend for when you have a huge stack of data tables in PDF format and need to turn it into actual data you can use.
- Open Refine (<a href="https://openrefine.org/post_download?version=3.7.3&platform=mac">Mac</a>, <a href="https://openrefine.org/post_download?version=3.7.3&platform=win-with-java">Windows</a>) - A great tool to help you clean data (ex: it can recognize that "Saint Paul" and "St. Paul" maybe refer to the same city in Minnesota)
	- If you're on a Mac, and you get the error that Google/Open Refine is damaged, [follow these instructions](open-refine-troubleshooting.md).

<hr/>

## Day 1
Monday, July 10

### Intro to Data Journalism
<a href="https://propublica.s3.amazonaws.com/data-institute/intro-to-data-2023.pdf"><img width="300" src="https://propublica.s3.amazonaws.com/data-institute/intro-to-data.jpg"></a>

<a href="https://propublica.s3.amazonaws.com/data-institute/intro-to-spreadsheets%202023.pdf"><img width="300" src="https://propublica.s3.amazonaws.com/data-institute/intro-to-spreadsheets.jpg"></a>

<a href="https://propublica.s3.amazonaws.com/data-institute/finding-data-2023.pdf"><img width="300" src="https://propublica.s3.amazonaws.com/data-institute/finding-data.jpg"></a>

<a href="https://propublica.s3.amazonaws.com/data-institute/loading-data%202023.pdf"><img width="300" src="https://propublica.s3.amazonaws.com/data-institute/loading-data.jpg"></a>

<a href="https://propublica.s3.amazonaws.com/data-institute/best-practices-2023.pdf"><img width="300" src="https://propublica.s3.amazonaws.com/data-institute/best-practices.jpg"></a>

<a href="https://projects.propublica.org/graphics/images/data-institute/presentations/2019/string-functions.pdf"><img width="300" src="https://projects.propublica.org/graphics/images/data-institute/presentations/2019/string-functions.jpg"></a>

## Day 2
Tuesday, July 11

<a href="https://propublica.s3.amazonaws.com/data-institute/evaluating-data-2023.pdf"><img width="300" src="https://propublica.s3.amazonaws.com/data-institute/evaluating-data.jpg"></a>
<a href="https://propublica.s3.amazonaws.com/data-institute/open-refine-2023.pdf"><img width="300" src="https://propublica.s3.amazonaws.com/data-institute/open-refine.jpg"></a>
<a href="https://propublica.s3.amazonaws.com/data-institute/analysis-one-var-23.pdf"><img width="300" src="https://projects.propublica.org/graphics/images/data-institute/presentations/2019/one-var.jpg"></a>

## Day 3
Wednesday, July 12

Basic Geographic Data
- [John Snow's map](https://upload.wikimedia.org/wikipedia/commons/2/27/Snow-cholera-map-1.jpg)
- [Census Geocoder](https://geocoding.geo.census.gov/geocoder/locations/addressbatch?form)
- [Maryland zip codes](https://data.imap.maryland.gov/datasets/maryland::maryland-political-boundaries-zip-codes-5-digit/explore?location=38.977456%2C-77.408308%2C8.94)

<a href="https://propublica.s3.amazonaws.com/data-institute/analysis-two-vars-23.pdf"><img width="300" src="https://projects.propublica.org/graphics/images/data-institute/presentations/2019/two-vars.jpg"></a>
<a href="https://propublica.s3.amazonaws.com/data-institute/mms-2023.pdf"><img width="300" src="https://propublica.s3.amazonaws.com/data-institute/mms.png"></a>

## Day 4
Thursday, July 13

### Visualizing Data, Charts and Maps

<a href="https://docs.google.com/presentation/d/1gkFt1MwdqwxSnhease3RJH_AtA61qEGyTUKJCo4C28Q/edit?usp=sharing"><img width="300" src="https://github.com/cjddatainstitute/data-institute-2023/blob/main/assets/day-4-thumbnail.png"></a>

Intro to visualiziing data
- [Creating your first chart](https://academy.datawrapper.de/article/245-how-to-create-your-first-datawrapper-chart)
- [Creating your first map](https://academy.datawrapper.de/article/268-how-to-create-your-first-choropleth-map)
  - [Florida county unemployment](https://docs.google.com/spreadsheets/d/1m2CevE363ZqqYHSBpB8nYeKReX52TdVkJ_eXZCTG_7k/edit#gid=266177519)
- [More resources, reading and inspiration](https://docs.google.com/document/d/1MNRiSy0wQapCfu4PjSlvRobXIR4taB47gtr5v2g8uBo/edit?usp=sharing)

## Day 5
Friday, July 14

## Day 6
Monday, July 17

## Day 7
Tuesday, July 18

## Day 8
Wednesday, July 19

## Day 9
Thursday, July 20

## Day 10
Friday, July 21
