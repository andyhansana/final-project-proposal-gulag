# final-project-proposal-the-gulag



Q1:	What does your application do?
	
A1:	Our application is a reminder web app that reminds the user how much time they have to park and the 
	location of the user’s parked car. The application will incorporate an NFC tag sticker for the user 
	to stick to the inside of their car. The user can tap the NFC tag with their phone to run a script 
	using Apple Shortcuts. Our web application uses a sub-application in Apple Shortcuts which will also 
	send a POST request to our web application. The web application handles the user login credentials 
	along with location data and processes the data into the app and sends back a response to the user. 
	The response will notify the user when to move their car from street sweeping in the Chicagoland area, 
	how much time they have left to move, and the location of the car itself. 



Q2:	What makes it different than a CRUD app? I.e., what functionality does it provide that is not just a 
	user interface layer on top of a database of user information, and the ability to view / add to / change 
	that information?

A2:	This is different from a CRUD app because it implements an NFC tag sticker to run a script with Apple 
	Shortcuts, and Apple Shortcuts communicates with our web application. Our web application acts as a HTTP 
	server for Apple Shortcuts while also utilizing its own client side user login interface. 



Q3:	What security and privacy concerns do you expect you (as developers) or your users to have with this application?

A3:	Our security and privacy concerns with this application is to obtain the minimal amount of the user information 
	necessary to get our application functioning as intended. Information such as location service to keep track of 
	where their vehicle is parked, and user email/username and password. 


------------------------------





MVP To Complete by end of week 13: 
	- Pull google map to display on our webpage. 
	- Set up Supabase database to track user login credentials, authentication. 
	- If there is extra time, look into Google Maps API to check user's parked car location
	- Website allows to login, when login show user most recent place they parked, click a button that says i'm no longer parked, marks that location as vacant/not occupied by their car.
	-If theres row in database of parking events thats marked as occupied, then render google map 
	-Another button that says I just parked, once that button is clicked, ask their browser for their current location and store that as where they just parked


App Link: [Website Link](https://candid-sopapillas-7a08fe.netlify.app/)

