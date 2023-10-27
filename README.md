                                             Capstone 2: Analyzing Transjakarta bus journeys during April 2023.

# **Background.**

Transjakarta is the first Bus Rapid Transit (BRT) transportation system in Southeast and South Asia operating since 2004 in Jakarta, Indonesia. TransJakarta was designed as a mass transportation mode to support the capital's hectic activities. With the longest track in the world (251.2 km), as well as having 260 bus stops spread across 13 corridors, Transjakarta which initially operates from 05.00 -  22.00 WIB, now operates 24 hours. With increasingly extensive routes and ease of use, Transjakarta has become the leading and favorite transportation for Jakartans. However, this good thing also goes hand in hand with many things that must be handled, including various problems, such as sexual violence that still often occurs to women, accumulation of passengers at bus stops, crowded passengers on the bus, and pickpocketing.

# **Problem Statement.**

Transjakarta wants to evaluate the trip for one month in April 2023, to improve services to passengers.

# **The Data**

This data is passenger data for the month of April 2023. It consists of 37,900 rows and 22 columns as follows:

1.	transID: Unique transaction id for every transaction
2.	payCardID: Customers main identifier. The card customers use as a ticket for entrance and exit.
3.	payCardBank: Customers card bank issuer name
4.	payCardName: Customers name that is embedded in the card.
5.	payCardSex: Customers sex that is embedded in the card
6.	payCardBirthDate: Customers birth year
7.	corridorID: Corridor ID / Route ID as key for route grouping.
8.	corridorName: Corridor Name / Route Name contains Start and Finish for each route.
9.	direction: 0 for Go, 1 for Back. Direction of the route.
10.	tapInStops: Tap In (entrance) Stops ID for identifying stops name
11.	tapInStopsName: Tap In (entrance) Stops Name where customers tap in.
12.	tapInStopsLat: Latitude of Tap In Stops
13.	tapInStopsLon: Longitude of Tap In Stops
14.	stopStartSeq: Sequence of the stops, 1st stop, 2nd stops etc. Related to direction.
15.	tapInTime: Time of tap in. Date and time
16.	tapOutStops: Tap Out (Exit) Stops ID for identifying stops name
17.	tapOutStopsName: Tap out (exit) Stops Name where customers tap out.
18.	tapOutStopsLat: Latitude of Tap Out Stops
19.	tapOutStopsLon: Longitude of Tap Out Stops
20.	stopEndSeq: Sequence of the stops, 1st stop, 2nd stops etc. Related to direction.
21.	tapOutTime: Time of tap out. Date and time
22.	payAmount: The number of what customers pay. Some are free. Some not.

# **Tableau.**

Data visualization in the form of stories in [Tableau](https://public.tableau.com/views/Transjakarta_/Story2?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link)
