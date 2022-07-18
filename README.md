# Race-Day
https://www.codecademy.com/courses/introduction-to-javascript/projects/race-day

<b>Codecademy’s annual race is just around the corner! This year, we have a lot of participants. You have been hired to write a program that will register runners for the race and give them instructions on race day.

As a timeline, registration would look like this:registration-timeline

Here’s how our registration works. There are adult runners (over 18 years of age) and youth runners (under 18 years of age). They can register early or late. Runners are assigned a race number and start time based on their age and registration.
</b>

<ul>
Race number:

<li>Early adults receive a race number at or above 1000.</li>
<li>All others receive a number below 1000.</li>
</ul>

<ul>
Start time:

<li>Adult registrants run at 9:30 am or 11:00 am.</li>
<li>Early adults run at 9:30 am.</li>
<li>Late adults run at 11:00 am.</li.
<li>Youth registrants run at 12:30 pm (regardless of registration).</li>
</ul>

But we didn’t plan for runners that are exactly 18! We’ll handle that by the end of the project.

<ul>
<li>
Race numbers are assigned randomly. We’ve provided the necessary code at the top of the file.

Check off this task after reading that line.

You can read the hint if you want to learn how it works!
</li>

<li>
Create a variable that indicates whether a runner registered early or not.

Set it equal to a Boolean value. You’ll change this later as you test different runner conditions.
</li>

<li>
Create a variable for the runner’s age and set it equal to a number.

You’ll change this later as you test different runner conditions.
</li>

<li>
Create a control flow statement that checks whether the runner is an adult AND registered early.

Add 1000 to their raceNumber if this is true.
</li>

<li>
Create a separate control flow statement below the first (starting with if again). This statement will check age and registration time to determine race time.

For runners over 18 who registered early, log a statement to the console telling them that they will race at 9:30 am. Include their raceNumber.
</li>

<li>
“Late adults run at 11:00 am”

Since we already checked for early adults we can write a statement like this: else if runner is over 18 AND did not register early they will race at 11:00am

Write the corresponding else if statement.

Within that, log a string to the console telling them that they will race at 11:00 am. Include their raceNumber.
</li>

<li>
“Youth registrants run at 12:30 pm (regardless of registration)”

For people who are under 18, log a statement to the console telling them that they will race at 12:30 pm. Include their raceNumber.
</li>

<li>
Enter different combinations of values for the two variables you created and run your code several times. Verify that the correct statements are printing to the console!

You can check your work using the examples provided in the hint.
</li>

<li>
Don’t forget about runners exactly 18 years old!

Add an else statement that logs a statement to the console telling the runner to see the registration desk.
</li>
</ul>
