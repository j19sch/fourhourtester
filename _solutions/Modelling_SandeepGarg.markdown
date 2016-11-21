---
layout: Exercise
title:  Modelling
date:   2016-11-21 21:45:00 +0530
categories: Exercise
contributor: Sandeep Garg
---

<!-- exercise title will be added automatically when generating page -->

## Briefing

When I first pulled up Google Calendar (not exactly now, it was a long time back), I was wondering on Why to use this and then How to use this app. Fortunately, this exercise required me to explore the same app. 

So, coming to Why, I have reasons…the reasons as a user.

1. I use and admire such applications with a different 'taste'.  Here, 'taste' is a subjective thing but being a user, this contributes to biases. The way I look at this application, I want to use it, I want it to fulfill my desires. 

2. I usually don’t use Google Calendar and most of the time its Outlook, my official calendar. Also, even in the digital age, I use to circle dates printed on the paper calendar placed on my office desk. 

3. Also, I am a bit bad at remembering dates, and I need a calendar, with a useful Reminder facility. Something that uses Data Analytics, so for example, If I set a reminder for doing a practice session for today night 19:00 PM IST and I don't mark it Done, then Google will set it for next day (as it claims and it does certainly). Fine, but what If I don’t do next day? My desire is, that, it should have the capability to analyze my “Not Done” behavior and probably next day, remind me with the help of some Notification "You are not marking your reminders done, what's going on" :). 

After all, I am just a unique user of this app, and I am ’probably’ exploring (testing) for my best fit use. I am a user with different “wants” and my perspective of 'Quality.'

These all characteristics put my perspective as a user into a testing phenomenon called 'Persona'. I want features, that fulfill my desires, from this product. It may have those, yet It may still be of excellent quality if it doesn’t have those features. But not for me. I would keep searching and if I have to pay some amount, I will.


## Exercise


**User Tour** 

_So here are few Features I would love to have in this Calendar app_

_Setting Reminders through Voice -_ Birthdays (most forgotten), Anniversary, Bill Payment, My Training Days. So basically setting reminders. Through Voice, though (I would Love it). I don’t like typing in apps, supporting voice is needed.

_Notification diversity (Email, WhatsApp, SMS, Voice assistance)_

_Create my Calendar_ - I am curious to use this feature, and I need to know what value it adds; how different it is from my standard calendar (Curious to Explore)

_Importing and Sharing of Other Calendars_ - I want to set my dates in sync with at least my Wife and some close friends, so that we can plan something together as we are all working - yes, I can do through some Taps, no issues (It would be great to see this)

_Holidays_ - My work locations and from where people can often contact me - Voice would be excellent, but taps would work (A should have for such a brand)

_Privacy of my data_

**Note:** I didn’t explore the application yet except for setting a reminder by typing text and then using Google Now to set a reminder. Google Now is awesome

**Data Elements**: From Data elements, I interpret the "data” (input, output, stored) that this Calendar Application Takes in, process, store, transport, purge usually during CRUD operations, Migrations, Import / Export, and Reporting to name a few to start with

**Data Tour**

1. _Voice_- When I want to add a reminder, Voice will be a Data which will be processed by Application

2. _Text Data_ - Strings that I will enter to give a meaningful name to a Reminder

3. _Dates, Calendar Objects_ - Google Calendar-centric in native language / foreign language

4. _Dates, Calendar Objects_ - Other platforms 

5. _Colours_ - Colouring different calendars, dates, etc. will require application to process color codes and display accordingly

6. _Data items which we can set in Calendar Settings_ - Usually they will be fixed and sometimes will be touched, but it would be interesting to see how those settings interact with user data (Date Format, Weather Information, Video Calls, etc.)

 

**Configuration tour**

Probably one of the easy one to look at, because here I can concentrate on Settings of this app. What ‘calendar’ app is offering right now from "setting preferences” perspective. However, it would be challenging to prepare a good strategy for testing this important feature

_Display Density_

_Settings_ - Language, Country, Time Zones, Weather, etc.

_Unsubscribe Feature_

_Labs_ - Latest ideas to customize the calendar settings

## Evaluation

**_-- User Tour - What I would want to Explore, Understand, Check and then Test --_**

1. _Voice Processing Test_ - Setting reminder via Voice. It would be my preferred test, as I consider my test mission to 'evaluate application's voice processing capabilities, efficiency, and language diversity.' Maybe, I will use my Indian accent (bit neutral), Maybe I will ask my American friend in Texas to explore, then my Belgian counterpart and my Dutch friend (who sometimes don’t understand her audio recording :)). I would love to use open source tools to add value to these tests.

2. _Google App's Integration Capabilities_ - Explore the Options, channels this app gives me to add Birthdays to this calendar. On an Android phone, e.g. I have my Contacts, some have Birthdays added, Anniversaries. Can I add a reminder for someone's Birthday by saying "Go to a bakery to book a chocolate cake for Charu." The moment I stop, app start searching for a contact "Charu" (let's assume by providing me a list of all "Charu" and sorting in order such that selecting the one which is most frequent called?). Then, it adds a reminder for her Birthday today night 12:00 with an B ‘day icon".

3. _Sync Feature Test_ - Checking out how it syncs different calendar If I go to create my calendar let’s say by choosing some dates from US Holidays, India Holidays, My Vacations and my Wife vacation dates

4. _Exploring APIs used by this application_ – App making API calls while CRUD operations, Importing/Exporting over the web, Sharing calendars, etc.


**_-- Data Tour - What I would want to Explore, Understand, Check and then Test --_**

_Voice data processing test_ - It slightly overlaps with Voice Processing Test, but intention is to understand the following

1. How app weighs different voices while converting into text? How it impacts the application performance, due to different frequency of Voice data

_Text Data_

1. Entering reminders in the different languages (maybe via other interfaces) and how are they stored? 
2. What happens when these reminders are updated, deleted or overridden?

_Data items which we can set in Calendar Settings_

1. Playing with Data items in Calendar Settings would be more interesting. Video Calls, Weather Information, Date Formats, Timezone specifically
2. Adding a reminder in IST calendar, importing a reminder from EST one? Updating an event from EST timezone to IST timezone? 
3. Internationalization and Localization Testing
 

**_-- Configuration Tour_ - What I would want to Explore, Understand, Check and then Test --_**

1. _Labs ideas about_

Automatically Declining Events, Background images for different calendars, Free or Busy

2. _Calendars_

Calendars I can only view, Import, Export calendar

3. _General_

Speedy Meetings, Event Dimming, Weather, Adding Video Calls, Keyboard Shortcuts

**_Above tests are interesting from exploring application perspective with intent "how does it behave" and "what is the learning." Understanding how application is acting with different types of data, combination of data, sequence of data may help in identifying a pattern which will guide the testing_**


---

#### Sources
- As referenced FCC CUTS VIDS