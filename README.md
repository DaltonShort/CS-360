Briefly summarize the requirements and goals of the app you developed. What user needs was this app designed to address?
          The goal was to keep track of items in storage and notify the user when the count is low through an sms text. The requirements started with a dtabase with two tables. individual sreen for login with option to create login if none has been made yet. A screen that specififcally uses a grid to display the items in inventory. mechanisms for adding/removing Items, increase or decrease the amount in storage, and a mechanism to alert the user when the inventory is low or 0 which was sms notification here. The user needs were structured information that is stored locally and allows the user full control to track items coming and going. 

What screens and features were necessary to support user needs and produce a user-centered UI for the app? How did your UI designs keep users in mind? Why were your designs successful?

          In addition to the screens listed in the requirements, I also developed a fragment for the account creation, and an additional screen to ask for permissions so it doesn't interrupt the startup flow of the app. The UI design kept users in mind and my design semi-successful by focusing on simplicity and readbility.
          The app was never intended for a huge company. The app was intended for small home businesses like pc building. The user could track tools, components, test components, other supplies all through data stored on a local device all in one simple screen with moderate protection to that data.

How did you approach the process of coding your app? What techniques or strategies did you use? How could those be applied in the future?
          I found the way that worked best for me was to start designing first. I think that in a mobile application, intuitiveness is the most important aspect. The app needs to be easy to navigate and comfortable. Keep buttons on the lower half of the screen because it's easier to hit with your thumb and stuff like that. I went through and made all the
          Layout files first. I made one for each of the required screens and filled them with necessary components one by one. Wrapping up the UI phase of designing is implementing how the user gets to each screen. Make the map easy to follow and reach common areas quickly. Once the layout files are all defined, i think macro. How many packages do i need?
          From there i will start to think of java classes to be made, create the java counterparts to the layout files, and organize them into the packages. From here, the foundation has been laid, all the requirements have their place to go. What do they need to get there? Finally to end designing i came up with objects that the requirement would need and
          plan for ways to extract the data for it to operate. Now for developing, i started with the backend interaction with the UI. Actually link them all together and make the widgets do their job. If the UIs function requires data to respond, i marked a todo so when that data is available i can implement it. From there i looked at a requirement, Identified
          any classes required for that functionality and scrtpted each one out individually. Checking methods before i move on. Then after the second one, i would also add testing their interactions with one another to make the requirement. I repeated until the requirement was filled. Then iterated through the list of requirements and tied up the UI.
          I did end up to deciding to add a couple new screens and classes, but was no problem with the organization of the code. This will now be my process forever. Design top to bottom, develop bottom up.

How did you test to ensure your code was functional? Why is this process important and what did it reveal?
          I added extensive logging statements and checked the logcat often. I also added some testing functions that i later deleated. Simple functions like populating the databases with data to ensure they handle it properly and that the inventory screen properly retrieves that data for displaying.
          It is important because the app can crash with you never knowing becvause it resumed on the same screen while looking at the code. Checking the logcat and adding logging statements revealed to me that at some point, i forgot to add toString() on one of the edit texts so that caused the app to crash when the data was used because it was not formatted
          correctly.

Considering the full app design and development process, from initial planning to finalization, where did you have to innovate to overcome a challenge?
          For asking for permissions, i ran into an odd problem with the create account fragment inflating when the app asked for permissions in the startup. What i did to overcome this was make a different UI and activity for the permissions. That way nothing impedes the app's flow.

In what specific component from your mobile app were you particularly successful in demonstrating your knowledge, skills, and experience?
          I think that has to be the implementation of the databases. Creating the database with multiple tables in Android studio requires knowledge of multiple programming langauges and principles. I was able to implement a local database that was effective and organized. Split into two tables, all interfacing from the layout to the java class to the 
          methods that query the database. So i think that i was very successful in showing my knowledge, skills, and experience by creating error free code that established a well designed database and its interaction with a java application.














FIVE TABS
