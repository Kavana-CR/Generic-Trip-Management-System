<h2> Generic Trip Management System </h2>
<p>Group size: 4 <br> <br>
The goal was to develop a data model that could be used appropriately for REDIS. Data Models were developed for ever changing volatile data such as traffic updates, public transportation which included bookings, seat reservations and delay notifications, hotel reservations, city based events. The aim was to provide information to users on the fly.</p> <br>
<p><b>Role 1: Assisted in realizing the Use Case. </b> <br>
Storyline: Two friends who live in New York, USA decide to attend concerts in Berlin and Munich, Germany. They plan a short trip of 4-days that includes two stops. An itinerary is made utilizing our services for booking-related requests (flight bookings, transport facilities, hotel and restaurant reservations). During their travel, they come across series of events that include – (availability/non-availability of restaurant tables, delays in their preferred transport, weather changes) – till they reach their destination. <br>
<img src="https://github.com/Kavana-CR/Generic-Trip-Management-System/blob/master/Use%20Case%20Chart.png"> </p> <br>
<b>Role 2: Assisted in coming up with user stories.</b><br>
<p><u>User Story 1: User makes an Itinerary for travelling to Germany.</u><br>
User makes an itinerary a month before the concert happens. The user books a round trip flight ticket from New York to Frankfurt. Books concert tickets in Berlin and Munich, books hotels/youth hostels to stay in Frankfurt, Berlin and Munich and books Train tickets to travel from Frankfurt to Berlin, Berlin to Munich and Munich to Frankfurt.</p> <br>
<p><u>User Story 2: User Arrives Frankfurt on 2nd March.</u><br>
User lands in Frankfurt International Airport and checks-in to a hotel. The user can get information from the trip management application about public transport and routes to get to the hotel. Once the user settles in the hotel, looks for a restaurant nearby the hotel to have dinner and then the user catches a morning train to Berlin to attend the concert.</p>
<img src="https://github.com/Kavana-CR/Generic-Trip-Management-System/blob/master/User%20Story2.PNG"> <br>
<img src="https://github.com/Kavana-CR/Generic-Trip-Management-System/blob/master/Scenario2.PNG"> <br>
<p><u>User Story 3: User Arrives Berlin on 3rd March.</u><br>
When user arrives Berlin, the user checks in to the hotel and decides to eat lunch at a restaurant and visit a few points of interest before attending the concert. As a trip management application information such as points of interests (Museums, Sight-Seeing) must be shown readily. If the travelling users have enough time before their main event then they would love to look around in the city that they’re visiting.</p><br>
<img src="https://github.com/Kavana-CR/Generic-Trip-Management-System/blob/master/User%20Story%203.PNG"> <br>
<p><u>User Story 4: User Arrives Munich on 4th March.</u><br>
When User arrives Munich, he/she checks-in to a hotel. User decides to eat at a restaurant in the hotel to save time travelling to a restaurant. The user then decides to visit a couple of point of interests before heading to the concert. The user experiences delays in public transport while heading back from the concert to the hotel. The user then checks-out of the hotel before noon the next day and heads to the central railway station of Munich. The user has close to 3 hours to wait for the train to go back to Frankfurt airport. The user decides to spend time in a restaurant inside the railway station.</p><br>
<img src="https://github.com/Kavana-CR/Generic-Trip-Management-System/blob/master/User%20Story%204.PNG"> <br>
<p><b>Role 3: Assisted in realizing the Data Models of Key-Value Data Store.<br>
Data Models Chart:<br>
<img src="https://github.com/Kavana-CR/Generic-Trip-Management-System/blob/master/datamodels.jpeg"><br>
<b>Structure of our REDIS Database:</b> <br>
<img src="https://github.com/Kavana-CR/Generic-Trip-Management-System/blob/master/Structure%20of%20Redis%20DB.png"><br>















