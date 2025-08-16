# pet-feeder-project

Project Summary:

This project shows how I designed a simple automated pet feeder. 
The idea is to feed pets on time, control how much food is given, and send an alert if something goes wrong. 
It’s mainly about using a step-by-step problem-solving process to think through how the feeder should work.

Features:

Feed pets at set times.
Check the portion size using a bowl weight sensor.
Check the bin to see if there’s enough food left.
Send alerts if the bin is low or food wasn’t eaten.
In this version, there’s no retry for jams — if food doesn’t come out, the feeder just sends an alert.

Testing & Improvements:

I tested with example numbers for time, sensor readings, and food weight. 
At first, it didn’t alert properly if food wasn’t eaten, and the error messages were messy. 
After fixing, the feeder now clearly shows bin empty and not eaten alerts.

Future Ideas:

Some ways to make it better in the future:
•	Add battery/Power-loss alert.
•	Add retry option for certain issues in the system.
•	Add quiet hours to avoid noise at night.
•	Allow system to check for motor jam and alert staff.
•	Add log system to maintain logs and check later.









