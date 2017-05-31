---
layout: soc-project
image: /images/tumtum.jpg
title: Tum Tum Tracker
mentor:
- "Pratik Lodha"
- "Sajal Narang"
category: "Development"
weight: 175
ribbon: progress
stipend: INR 3000
mentees:
- Shubham Anand (frontend)
- Shubhang Bhatnagar (frontend)
- Arsh Akhtar Ansari (backend)
- Alok Kumar (backend)
- Rajarshi Saha
- Owais Chunawala
contact:
- Facebook- <a target="_blank" href="www.facebook.com/sajalnarang">Sajal Narang</a>
- <a target="_blank" href="https://tum-tum-tracker.slack.com/signup">Slack</a> (Sign in using iitb.ac.in email)
---

The aim of this project is to create a crowd-sourced Android application to dynamically track the location of Tum-Tums in the institute and display them on a map in the same app.

<!--break-->

The idea is to place passive RFID tags inside all buses that are to be tracked. Once a user that has NFC enabled enters the bus, his phone detects the tag and starts sending the phone's location to the server, till the phone disconnects from the tag. This location is then displayed on the app. The aim is to make the system more reliable and also to understand patterns in the usage of such buses. There have been attempts in the past to make such a tracker but they all used heavy hardware and thus incurred large costs. This is the first attempt at crowd-sourcing the location data. If you have any doubts or are interested in the project, join the Slack team whose link is given above.

### Week 0
* **Frontend** - Forked the Android Studio Project, Added google Maps API to the app
* **Backend** - Got familiar with Django, Made Database Design for the project

### Week 1
* **Frontend** - Solved issues on the app repository on Github
* **Backend** - Created database to store bus ID, NFC data and location, and used APIs to fetch the data
