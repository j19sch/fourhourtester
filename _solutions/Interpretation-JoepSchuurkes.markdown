---
layout: solution
title:  Interpretation
date:   2016-11-14 22:06:45 +0200
categories: solution
contributor: Joep Schuurkes
---

<!-- exercise title will be added automatically when generating page -->

_"You can add reminders in Google Calendar. Reminders carry over to the next day until you mark them as done. For example, if you create a reminder to make a restaurant reservation, you'll see the reminder each day until you mark it as done."_

## Exercise
1. **Reminders** carry over to the next day until you mark them as done.<br>
Reminders, so not events? Is there something else besides reminders and events?

1. Reminders carry over to the next **day** until you mark them as done.<br>
Not hour, not week, not whatever, but day.

1. Reminders carry over to **the next day** until you mark them as done.<br>
What if I cross the international date line?

1. Reminders carry over to the next day until you **mark** them as done.<br>
What else can I do with a reminder? Edit, delete, …?

1. Reminders carry over to the next day until you mark them as **done**.<br>
What other states can a reminder be in?

1. Reminders carry over to the next day until **you** mark them as done.<br>
Can anyone/anything else than me change the status of a reminder?

1. Reminders **carry over to the next day** until you mark them as done.<br>
So when will I be reminded again? At midnight? At some configured time?

1. Reminders carry over to the next day **until you mark them as done**.<br>
Can I do anything else to have them not carry over?

1. Reminders **carry over to the next day** until you mark them as done.<br>
When is the carrying over scheduled by the app?

1. Reminders carry over to the next day until you mark **them** as done.<br>
So multi-select is available?


## Evaluation
1. **Has your interpretation of the sentence become richer through this exercise?**<br>
Yes, there is a lot more meaning to distill from the sentence than I initially thought.

1. **How different could two implementations be, if their developers did not share all of these interpretations?**<br>
There definitely could be differences because of the different states a reminder can be in and because of the distinction between the app doing the carrying over and the app re-reminding the user.

1. **Based on your different interpretations, where do you think are good places to look for bugs?**<br>
(1) crossing the international date line or changing the date of the device clock<br>
(2) state changes of a reminder: different changes by different actors (if possible) in combination with the carrying over
