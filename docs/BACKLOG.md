# Home Assistant dashboard backlog

The work on this project happens in its Claude project. This file is what the voice app reads when Ben asks "how's the dashboard going?", so keep it current there.

Format: one checklist line per item, in priority order (top is next). Tick an item (`- [x]`) or move it under Done when finished. Put items you have set aside under Parked. Write "waits on Ben" on an item that needs his decision. Optional: `docs/NEEDS-BEN.md` with numbered asks for Ben, which voice status also reads.

## Now

- [ ] Fix Showbie homework tasks dropping off early: TaskMate caps task expiry at 7 days, so homework due more than a week out (e.g. Maths Week 9, due Fri 4 Dec) vanishes before its due date
- [ ] Confirm the first full week of Freddie's pocket money settles correctly (Sunday 29 Nov, 8pm notification to Ben and Izzy)
- [ ] Record the go/no-go decision after the 14-day soak (earliest gate was Mon 23 Nov) and close the open pilot tests (waits on Ben)
- [ ] Decide the wall screen: 21.5 inch Android screen in the back room, cable run and sightline still to confirm (waits on Ben)
- [ ] Protect the kids tablet battery: charge only between about 20 and 80 percent with a smart plug
- [ ] Tidy stale comments in the dash YAML packages that still mention the retired meals calendar

## Parked

- [ ] Photo-frame mode when the screens are idle (WallPanel), with clock, next event and bins on top
- [ ] Wake the screens on presence (mmWave sensor) instead of the tablet camera
- [ ] Different layouts by time of day (school-morning view, evening view)
- [ ] Octopus Energy cheap-rate and peak-rate prompts on the wall
- [ ] Countdowns (half term, birthdays, trips) and a family message board
- [ ] Move repeated card templates into template sensors so the wall dashboard is smaller and easier to change

## Done

- [x] Freddie's weekday "20 minutes reading" now shows all day (any time) instead of only after school, so it no longer drops off his card at 6:30pm (27 Nov)
- [x] Freddie's TaskMate card split into Homework, Daily routine and Extra chores sections, with the "if you like" label hidden (24 Nov)
- [x] TaskMate upgraded to 7.12.1, after a backup, to get headed sections (24 Nov)
- [x] Showbie tasks worth 2 stars each, and fixed tasks vanishing overnight (24 Nov)
- [x] Generic homework chore removed; pocket money now counts Showbie tasks, 2 a week Monday to Friday by 8pm (24 Nov)
- [x] Showbie homework sync: hourly Gmail check on weekdays, 12:47 to 20:47, adds each new homework item to Freddie's TaskMate list until it is done or due (24 Nov)
- [x] Freddie's printable weekly chores sheet (22 Nov)
- [x] Freddie's pocket money: £2 a week, -£1 each for missed homework, guitar under 2 or reading under 3, settled Sunday 8pm, running total on the kids tablet and wall (22 Nov, live from 23 Nov)
- [x] Weekly homework and guitar targets with a +10 bonus for Freddie (16 Nov)
- [x] All-day events now show on the kids' agenda cards (16 Nov)
- [x] Reward shop open all day on non-school days; morning routine window runs to 08:30 (14 Nov)
- [x] Met Office weather warnings banner on the wall (Surrey and Greater London) (11 Nov)
- [x] Meals: weekly meals list and recipe library (book, page, nights) replace the meals calendar (11 Nov)
- [x] School-run weather prompts for drop-off and pick-up (11 Nov)
- [x] Wall, kids and parents dashboards built and applied (calendars, people locations, school run, bins, chores and rewards, alerts, guest mode) on the Samsung Galaxy Tab A11+ pilot (31 Oct)
- [x] Solution design and build plan (11 to 12 Oct)
