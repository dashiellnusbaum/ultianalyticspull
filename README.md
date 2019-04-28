# AUDL Pull <img align="right" width="100" height="100" src="images/logo.png">

Use *AUDL Pull* to grab, clean, and enhance all of the available UltiAnalytics data for AUDL seasons 2014 to 2019. It comes with *individual-stats* which will tabulate player stats like goals, assists, blocks, and over 20 others! 

## Description

This project grabs AUDL data from the UltiAnalytics website using a pre-webscraped list of file paths. Data for each team and year are returned separately. Enhancements and regularizations are performed on the raw CSV to make them "analysis ready." The command-line interface allows for the latest year of data to be pulled instead of all years.

## Features

- Formatted for use with super fast and awesome Python Pandas!
- Auto-matched player names for over 4,000 usernames!
- Fixes to data entry errors!
- Standardized team names!
- Extra columns to distinguish games, quarters, points, and even possessions!
- Individual player stats!
- All Game Scores Ever Played!
- All AUDL Team info and logos!
- Grab Current Rosters!
- Grab Reported Active Rosters!
- Playoff/Regular season ***coming soon***
- Merged Game Stats ***coming soon***

## Usage

```bash
python audlpull.py
```

then 

```bash
python individualstats.py
```

That's it! 

## Requirements
- Python >= 3.0
- Internet connection ;)
- Python libraries: glob,urllib,argparse,pandas,numpy,csv (pretty standard stuff)

## Citations

Doing something cool with *AUDL Pull*? Let me know!

Here's a list of work 

- Articles in Ultiworld 
 - [Predicting Breakout Stars of 2019](https://ultiworld.com/2019/03/29/predicting-audls-breakout-stars-stats/)
 - [Accessing MVP Candidates of 2018](https://ultiworld.com/2017/10/03/assessing-audl-mvp-candidates/)
- SOTG Stats social media posts
 - [Twitter](https://twitter.com/sotgstats), [Instagram](https://instagram.com/statsofthegame/), [Facebook](https://www.facebook.com/sotgstats/)
 - Advancing Analytics in Ultimate. See, for example: 
  - Net Stats - https://twitter.com/sotgstats/status/1111381496789504002
  - Handler Number - https://twitter.com/sotgstats/status/885529847623274496
  - Individual Efficiency Boost - https://twitter.com/sotgstats/status/870357352725315584
  - Individual Efficiency Decrease/Drain - https://twitter.com/sotgstats/status/871448880323473410
  - Possession Conversion - https://twitter.com/sotgstats/status/870008776748695554
 - Performing Predicative Analysis
  - https://twitter.com/sotgstats/status/935987429747675141
  - https://twitter.com/sotgstats/status/900458814528528384
  - https://twitter.com/sotgstats/status/1013669331874516992
 - Novel Visualizations
  - https://twitter.com/sotgstats/status/1116326922500345856
  - https://twitter.com/sotgstats/status/1115600848694829057
  - https://twitter.com/sotgstats/status/962909472590041096
  - https://twitter.com/sotgstats/status/919763130561024000
  - https://twitter.com/sotgstats/status/918887852024500225
  - https://twitter.com/sotgstats/status/910299788922511361
  - https://twitter.com/sotgstats/status/895377402255355904
  - https://twitter.com/sotgstats/status/885894880874172418
  - https://twitter.com/sotgstats/status/1000192420460531712
  - https://twitter.com/sotgstats/status/1089294636089294848
- AUDL Stats App under development
- Other Works
 - [Overlooked Stars of 2018](https://afbcary.github.io/audl-stats/)