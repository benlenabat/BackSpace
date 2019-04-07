# Overview

## Intended Users

The intended users of Backspace are anyone with the desire to venture into space, with the financial backing to support it. 
These users may be risk takers or thrill seekers, the same people who enjoy skydiving or other potentially dangerous activities. 
Other users we intend to use our application are curious scientists who are enthralled about space exploration, and wish to experience it.

## Major Functionality

* Browse available flights for purchase, based on your current planet, and which planet you would like to visit

* You can look at the flight list in two different views, either a calender view or a list of flights most recent being first

* Track the ongoing flights that Backspace has launched, with information on their ETA and current status

* Choose from a selction of flight classes, and apply any additional ammenities we desire

* Review your booking, prior to finalizing your purchase (including your current location, destination and travel class chosen)

* Purchase a flight ticket within the app, as well as apply any promotional coupons

* Browse through a catalog of information on the associated planets that Backspace offers.

## Team Members and Special Skills Learned

* Ben: Understanding how to override methods that I havent written and adding complexity

* Evan: Cross-product integration

* Sam

* Max

* Aaron: Testing expert

# Demonstration

[Click Here](https://www.youtube.com/watch?time_continue=2&v=GzHzq5wqY1I)

# Postmortem

* Overall architecture: 3-tier system, prety standard

* What went well: Functionality between different people's code worked better then expected

* What went wrong: Non-deterministic parts of the program and testing, also an imported calender view was impossible to test

* What would we do differently: Start with 1 flight object instead of 2 and define objects more broadly

* How large is the project: Larger then any project any of us have worked on in the past.
We have 3 sections, Booking the flight is quite large with flight status and planet list being roughly the same size.

* What took the most time: Data integration was tough and quite lengthy.
The interaction between seperate chunks of code (planetlist -> book a flight to that planet) was easier then expected

* Are they any outstanding bugs: Not that we are aware of :worried:

* 
