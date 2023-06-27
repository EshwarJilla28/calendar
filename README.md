# Calendar
The Gregorian calendar is the one that is most often used. The Gregorian calendar has leap years. In a period of four hundred years, there are 303 normal years and 97 leap years. The majority of people mistakenly think that a leap year occurs every fourth year, although this is untrue.

I've first made two arrays: one with the names of all the months and one with the days in each month. Due to my desire to keep things simple, I purposefully left the first slot of both arrays empty.

The first function, inputyear(), retrieves the user input. A year must be entered by the user. 

The day number of the first day of that year is obtained using the next function, determinedaycode(), which enables us to show the date where it belongs. (Therefore, it is only used for output.)

To check if the user's input is a leap year, use the determineleapyear() function. If so, February now has 29 days instead of the previous 28.

The last function, calendar(), prints each month on the screen. I used the first for loop to loop over all months. The days of the week are then printed, followed by the name of the current month. The prompt is then positioned under the appropriate weekday using the daycode. Next, a month's worth of dates are printed. The prompt must then be positioned correctly on the weekdays as the last step.

