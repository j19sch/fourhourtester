---
layout: solution
title:  Interpretation
date:   2016-11-20 19:39:45 +0530
categories: solution
contributor: Sandeep Garg
---

<!-- exercise title will be added automatically when generating page -->

## Briefing

The exercise asked to apply "Mary had a little lamb" to the **second sentence** of the quote, I applied it to the first sentence as well. Honestly, The reason was, I actually **overlooked** that. But, still, that turned out to be helpful.

## Exercise

1. You **can** add reminders in Google Calendar....
You can add reminders in Google Calendar but you **shouldn't** do that.

2. **You** can add reminders in Google Calendar....
**Only You** can add reminders in Google Calendar, nobody else.

3. **You can** add reminders in Google Calendar....
**Earlier you couldn't** add Reminders. Either only Goals or Events, but now you can add Reminders as well.

4. You can **add reminders** in Google Calendar....
You can **add only Reminders** only in Google Calendar. **Not Events or Goals**

5. You can add reminders **in Google Calendar**....
You can add reminders in Google Calendar only, **no other application has this feature**.

6. You can **add reminders** in Google Calendar....
You can **just add Reminders** , may not be able to **delete or update** those reminders.

7. You can **add reminders** in Google Calendar....
You **Cannot Import** from other calendars ( **different platform, iPhone Calendar** ), You have to Add

8. You can **add reminders** in Google Calendar....
You **Cannot Import** from other calendars ( **From a different Google account** ), You have to Add

9. Reminders **carry over to the next day**...
**By Default?** Even if you **don't opt for 'Repeat Everyday' option** while setting up a Reminder, Reminder will be carried over to the next day

10. Reminders carry over to the **next day...**
**Only Next Day** , may not be at the same time

11. **Reminders carry over** to the next day...
It **doesn't necessarily mean that original reminder will go away,** that will show up on the Calendar for previous days as well

12. **Reminders carry over to the next day**...
It may result in **conflicting**** with other Reminder already setup for Next Day **at the** Same Time **OR** Overriding an existing Reminder **for the Next Day at the Same time OR** Corrupting (data loss) both Reminders for the next day**

13. Reminders carry over to the **next day**...
What if I am in a **different Time Zone** (time differences) when Reminder carried over?

14. ...until you mark them as **done**....
" **Done**" can be achieved by **Deleting / Updating** that reminder?

15. ...until you mark them as **done**....
"Done" can also be achieved by tapping " **MARK AS DONE**" option in the Calendar App

16. ... **until you mark them as done**...
**Using the same medium** from where you created it (yours google account on Laptop, Your Mobile's Calendar App)

17. ... **until you mark them as done...**
**From at least one platform** from where you created it (yours google account on Laptop, Your Mobile's Calendar App)



## Evaluation

1. **Has your interpretation of the sentence become richer through this exercise?**

Yes, Though I already studied "Mary had..." heuristic in past. It always helped in exploring Context, Constraints, Learning about how to read Requirements and Testing Opportunities

2. **How different could two implementations be, if their developers did not share all of these interpretations?**

Considering the following Interpretations

1. You can add reminders in Google Calendar....You cannot Import from other calendars; you have to Add
2. Reminders carry over to the next day...What if I am in a different Time Zone (time differences) when Reminder carried over?
3. Reminders carry over to the next day.... It may result in conflicting with other Reminder already setup for Next Day at the Same Time OR Overriding an existing Reminder for the Next Day at the Same time OR Corrupting (data loss) both Reminders for the next day

While developing (Thinking, Designing Solution and Programming, BEFORE start coding), If developers (more precisely in Agile Teams, if team doesn't work on different interpretations) the end solution may not serve the purpose for which it is intended. Also, it may not have features, fault tolerance, charisma as compared to other comparable products in the market

3. **Based on your different interpretations, where do you think are good places to look for bugs?**

- Reminder CRUD Operations
- Setting Reminder Frequencies
- Conflicting Reminders - Application Behaviour
- Data Corruption
- Sync Feature
- Time Zones
- Import Reminders from other account and vice versa Export

---

#### Sources
- Bit explored the Calendar application on my anDroid phone
- https://www.youtube.com/watch?v=HVsySz-h9r4
- https://git-scm.com/book/en/v2/Getting-Started-First-Time-Git-Setup
- https://github.com/Kunena/Kunena-Forum/wiki/Create-a-new-branch-with-git-and-manage-branches