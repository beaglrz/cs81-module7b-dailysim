# Reflection – Daily Schedule Simulator

## What was your approach to designing the schedule?
My approach was to break my day into simple, realistic events and display them one at a time in order. I used setTimeout to control timing and appended new lines to the page so the schedule gradually built up, simulating a real daily routine.

## What was one challenge or unexpected behavior you encountered?
One challenge I faced was figuring out how setTimeout worked inside the loop. At first, I thought the events would show up right after each other, but I learned that each delay is set up on its own and depends on where it is in the loop. Once I understood how the timing was worked out, the order and behavior of the events became clearer.

## What does this assignment teach you about async code?
This assignment showed me that async code runs later instead of right away. Using setTimeout helped me understand how JavaScript can delay actions and control when things happen on the page.

## What creative element did you add?
The creative element I added was coming up with a realistic daily routine and using timing to match how a real day flows. Each event appears with a delay, which connects the code’s behavior to real-world timing and shows how asynchronous code controls when things happen rather than running everything at once.

## How does this project simulate or differ from real-world schedules?
This project simulates a real schedule by showing events one after another, rather than all at once, which is how a day really unfolds. But it is not exactly like real life because the events happen faster and always at the same time apart, while real schedules can change, happen at the same time, or be late.

