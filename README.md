# bikesharing
Practice and Challenge Assignment for Module 14

## Purpose
Now that we've gotten a good idea of how to create our story, there is still some more work to be done to convince investors that a bike-sharing program in Des Moines is a solid business proposal. To solidify the proposal, one of the key stakeholders would like to see a bike trip analysis.

For this analysis, you’ll use Pandas to change the "tripduration" column from an integer to a datetime datatype. Then, using the converted datatype, you’ll create a set of visualizations to:

* Show the length of time that bikes are checked out for all riders and genders
* Show the number of bike trips for all riders and genders for each hour of each day of the week
* Show the number of bike trips for each type of user and gender for each day of the week.

Finally, you’ll add these new visualizations to the two you created in this module for your final presentation and analysis to pitch to investors.


## Link to Dashboard
[Access my story from this link.](https://public.tableau.com/views/bikesharing_16434877477600/CitibikeReport?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link)


## Results
The Checkout Times tells us that most trips will last 5 minutes, with most checkouts peaking at 146,752 bikes. This means that most rides will only for brief moments.

* Checkout Times

![Checkout Times](https://github.com/Itgotworse26/bikesharing/blob/main/Images/Story%201%20Checkout%20Times.png)


Gender and Checkout Times shows that even though male riders outnumber female riders even at their respective peaks (108,087 at 5 minutes in versus 34,151 at 6 minutes in), their peaks are close to each other's. This means that peak times are not too different.

* Gender and Checkout Times

![Gender and Checkout Times](https://github.com/Itgotworse26/bikesharing/blob/main/Images/Story%202%20Gender%20and%20Checkout%20Times.png)


The peak stopptime according to Stoptimes by Hour is 6 PM on Thursday with 44,901 check-ins. If maintenance is going to be performed on the bike fleet, Thursday evening to Friday Morning would be the busiest as that is when the most bikes will be checked in.

* Stoptimes by Hour

![Stoptimes by Hour](https://github.com/Itgotworse26/bikesharing/blob/main/Images/Story%203%20Stoptimes%20by%20Hour.png)


Stopttimes by Gender shows that for female and male users, 6 PM is the peak stoptime, with 11,335 and 30,746 check-ins respectively. Meanwhile, unknown genders peak at 5,670 check-ins in Saturday at 12 PM. This means that Saturday is when there are the most one-time or first-time users, especially ones that did not take the time to properly fill out their registration.

* Stopttimes by Gender

![Stopttimes by Gender](https://github.com/Itgotworse26/bikesharing/blob/main/Images/Story%204%20Stoptimes%20by%20Gender.png)


Starttimes by Usertype shows that checkouts for subscribers peak on Thursday with 259,316 Male, 88,282 female, and 6,082 unknown users.  Checkouts for customers peak on Saturday with 49,285 Male, 27,527 female, and 55,375 unknown users. As already shown by the Stopttimes by Gender above, this means that most one-time or first-time customers will check out bikes on Saturday. 

* Starttimes by Usertype

![Starttimes by Usertype](https://github.com/Itgotworse26/bikesharing/blob/main/Images/Story%205%20Starttimes%20by%20Usertype.png)


Usertypes by Gender demonstrates that the 1,372,601 male suscribers outnumber the 493,752 female and 34,006 unknown subscribers. However, the 191,525 unknown customers outnumber the 157,671 male and 94,679 female customers. Once again, it shows that one-time or first-time non-subscribers are probably not taking the time to fill out their information.

* Usertypes by Gender

![Usertypes by Gender](https://github.com/Itgotworse26/bikesharing/blob/main/Images/Story%206%20Usertypes%20by%20Gender.png)


The Map of Usertypes shows that most customer users start in Staten Island with Central Park being the next greatest start station; the pedestrian nature of both places could explain why must non-subscribers check out bikes at those stations. Both locations not being friendly for outside cars means that most one-time or first-time users will check out bikes from stations there. 

* Map of Usertypes

![Map of Usertypes](https://github.com/Itgotworse26/bikesharing/blob/main/Images/Story%207%20Map%20of%20Usertypes.png)


## Summary
The data demonstrates that the Des Moines chain of Citibike should move forward with a couple of suggestions.

First off, we should re-examine if the marketing of Citibikes is gendered. There is a noticeable gap in male and female users. Kate and I will have to interview both female users and non-users about Citibike and why or why not did they choose the service. 

Next up is choosing our maintenance time. We know that while Thursday evening has the most check-ins, Saturday is when there are the most one-time or first-time users. We can choose either a time when most of the fleet has already been checked in or when there has been the most one-time or first-time users. I would perfer choosing a time when most of the bike fleet has been checked in, but Kate should make a suggestion when another time is useful.

Making sure that one-time or first-time users are correctly filling out their registration is another big priority. While users not correctly filling out their forms might seem like a small issue, it might lead to neglect in accountability of our bike fleet if allowed to persist. We should examine if the registration is too clunky or unwieldy and revamp it so that one-time or first-time users can easily fill it out. If the registration process can be streamlined, it might lead to additional subscibers, or at the very least, more accountability of the Citibike fleet. 

Finally, we should choose locations that are not car-friendly. We can observe that most customer users are starting from stations in Staten Island and Central Park; locations not known for being accesible by outside vehicles. Being able to identify similar locations in Des Moines could lead to a boon of one-time or first-time users, who then might turn into long-term suscribers.  