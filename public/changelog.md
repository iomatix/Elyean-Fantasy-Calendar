# 2.0
## TBD
* Automated build system
* The entire UI has been overhauled with many alterations that come with the changes below.
* REWORKED! Overhauled the clock and the sunrise-sundown system so that it can accomodate crazy times, and added offset hours which simply rotate the numbers around the clock face.
* REWORKED! The week system has changed to support the changes in the month system. There is now a global week, which acts as the standard week in the calendar.
* REWORKED! Months can now leap! You can control this through the interval in the month itself. Months can now also have an overriding week, for use in roman-styled calendars.
* NEW FEATURE! Intercalary timespans - Similar to months, but these timespans do not affect the week flow within a calendar, and simply acts as days without being attached to a month.
* NEW FEATURE! Leap Days - You can now have multiple leap days! This can also be a normal day that gets added to a month, or act as an intercalary leap day where it interrupts the month, inserts a day outside of the month and then continues the month as if nothing happened. Leap days can either add a day, remove a day, or add a week day to the month (again, roman styled calendars).
* REWORKED! Moons - They can now have a custom phase count, read up on the fantasy calendar wiki to understand how that works. Now you can also hide individual moons from your viewers.
* NEW FEATURE! Seasons - Completely overhauled! Instead of being attached to specific days in the year, it now has a static length. This also means that your seasons can drift if the average year length and the season length don't match.
* REWORKED! Weather - Completely overhauled the weather generation system. It support offseting the weather from the season so that the coldest day doesn't always fall on the winter solstice, for example.
* REWORKED! Locations - The location system has been reworked, and each location can now have their own sunrise and sunset times per season, and timezone adjustments when active. Weather is also directly tied to the location now, with precipitation chance and percipitation intensity becoming two different parameters.
* NEW FEATURE! Cycles - You can now create zodiac years like in the Chinese calendar with the brand new cycle system!
* NEW FEATURE! Eras - They work like A.D. and B.C. in the Gregorian calendar, where each era has a start date and lasts until a new era begins. Eras can also reset the year prematurely like in the Japanese calendar, and resetting the year count can also happen with this.
* REWORKED! Events - Events now support full markdown editing, and in-calendar display settings such as color and text styles.
* NEW FEATURE! Event conditions - Events now support multi-conditional setups, where each event can be driven by any part of the calendar to be able to be shown. Parameters include year, month, day, epoch, week day, weeks, moons, cycles, eras, era year, seasons, seeded random chance, and event-based-conditions (event chaining!).
* NEW FEATURE! Event Categories - Events can now have categories which you can filter the current visible events, and create presets for events to use when displayed.
* NEW FEATURE! Layouts - You can now display your calendar in four different ways! Styles include grid, wide, vertical, and minimalistic!
* REWORKED! Settings - Multiple settings have been brought up to speed with the rest of the calendar systems.
* NEW FEATURE! Calendar linking - You can now link calendars together! One master calendar can influence other calendars in your world, making sure that all of them are in tandem. This is a powerful feature that ensures a 1 to 1 representation between vastly different calendars.

# 1.6a
## May 1, 2019
* Fixed - Some users not being able to log in.

# 1.6
## April 30, 2019
* Added - An easy way to share your calendar with anyone, the field is located above the 'to view' or the 'to edit' button.

# 1.5d
## January 19, 2019
* Fixed - Bug that caused no-print events to be printed anyway.

# 1.5c
## January 12, 2019
* Tweaked - Moon color background implementation has been tweaked, it will hopefully work better on Mac and Linux now.

# 1.5b
## January 11, 2019
* Fixed - If moons were hidden from players, events based on the moon cycles would break all events. Now they do not do that anymore. Good moons!

# 1.5a
## October 11, 2018
* Added - An option to display year day on each day of the year. Check it out in the options tab during creation or editing your calendar.
* Fixed - A bug that causes weather to break if you were view other years than the current one.

# 1.4
## September 29, 2018
* Tweaked - All saving and editing actions now produce readable errors. I don't know why I didn't do this before but you live and you learn...

# 1.3
## September 17, 2018
* Fixed - A bug that would cause calendars to not be locally saved while logging in while creating it.

# 1.2
## September 6, 2018
* Tweaked - Added a warning about missing fields when calendar is complete to lessen confusion by newer users.

# 1.1
## August 17, 2018
* Tweaked - Weather features on non-rainy days (like dust storms and tornados) will now happen less on non-windy days.
* Fixed - Bug where "every x" events would fail to show up during negative years.
* Fixed - The "To" date in events could not be below the month and day on the "From" date, even if the "To" year was greater than the "From" year, this has now been fixed.

# 1.0
## May 15, 2018
* Added - Weather systems! You can now generate weather patterns, you can find it in the new tab with a weather icon while editing or creating a calendar.
* Added - You are also able to create your own climates that you can switch between easily.
* Added - Event repetitions every x day/month/year/weekday etc. Check it out in the event creation popup.
* Added - The ability to duplicate entire calendars.
* Fixed - A rare bug that caused the second to last month's length to not load properly.
* Added - Ability to hide upcoming days in the player view. Check the settings for this feature.
* Tweaked - The weather generation system. It works relatively the same, but more chance for wind and clouds on non-rainy/snowy days.
* Fixed - Fixed issue with from/to dates on events not working properly
* Fixed - Fixed an issue with repeating events would not show propetly in subsequent years
* Fixed - Fixed issue when changing the amount of days in a month during calendar generation causing all days to be the current day.
* Fixed - Issue with events in print view not showing the correct month.
* Fixed - An issue where weather would not be visible in player-view.
* Fixed - An issue where the print view would not display the first days correctly.
* Fixed - Small bug with visualization of settings IU.

# 0.90b
## April 28, 2018
* Added - Event cards - They can be accessed through edit view (to edit/delete events you can be arsed to find) and print view (as index cards).
* Fixed - Made all events use moon index instead of moon name to evaluate events (basically, it means that you can change moon names and moon-based events should not break now).

# 0.87d
## April 25, 2018
* Fixed - A bug where having spaces in the moon name would cause events to not display.

# 0.87a
## April 16, 2018
* Fixed - A bug that caused some moons on some calendars to turn to the same color as the dark side of the moon.
* Fixed - A bug that made events appear on all days.

# 0.85c
## April 13, 2018
* Fixed - Epoch calculation for leap years was broken. Now it is not.
* Fixed - Delete button not working.

# 0.85
## April 10, 2018
* Tweaked - Network usage vastly improved, and got a new server plan (thanks to our patrons).

# 0.84a
## April 6, 2018
* Added - You can now color your moons
* Added - Favorite icon, so that it's not a blank lil icon any more.
* Fixed - Some residual bugs related to solstices and changing dates.

# 0.82a
## April 4, 2018
* Fixed - Bugs with the clock not displaying start and end of day properly.

# 0.82
## April 3, 2018
* Tweaked - Clock display is now much neater.
* Fixed - Major bug with calendars not showing for viewers (but still worked for owners).

# 0.80a
## April 2, 2018
* Added - Events can now be created based on moon cycles.
* Tweaked - Reduced the number of moon cycles from 32 to 16 to allow for more accurate event matching.
* Tweaked - Changed first day drop down list to instead change the first day of the first year, creating a cascade effect.
* Fixed - Bug related to leap years where the first day of a year after a leap year would not advance accordingly.
* Fixed - Week numbers not being correct.

# 0.75c
## March 31, 2018
* Added - Beta feature for leap years. Please report any bugs on the discord channel.
* Added - Warning if you navigate away from an unsaved calendar.