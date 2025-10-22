# CS_360_Mobile_Architecture_and_Programming


Briefly summarize the requirements and goals of the app you developed. What user needs was this app designed to address?

  The app I created was a simple weight-tracking app. The app needed to use a database with 3 tables: one for usernames and passwords, one for the user's daily weigh-ins, and one to store the user's goal weight. The app needed to allow users to log in or create a new account with a username and password if one does not exist, add daily weights to the database, display those daily weights from the database in a grid, and allow the user to enter their goal weight into the database. The app should also ask for SMS permissions and send an SMS to the user once they hit their goal weight.

  This app was designed for any user who cares about tracking their weight. I anticipate most users would be overweight people trying to lose weight, but it could also be used by underweight people trying to gain weight, or fitness enthusiasts who just want to track their progress and ensure they are continuing to hit their goals.

What screens and features were necessary to support user needs and produce a user-centered UI for the app? How did your UI designs keep users in mind? Why were your designs successful?

  This app was designed using 3 separate screens. The first screen is the accounts screen, where users can log in or create a new profile using a username and password. This is the main screen that the app will open up to by default. The middle screen is the main focus of the app. This is where the user can enter their daily weight, and also where the user's previous daily weights will be displayed, showing the user their progress. The 3rd and final screen is where the user can enter and view their goal weight. This screen is also where the user can enter their phone number, which will prompt them to accept or deny SMS permissions so that they can receive an SMS alert when they have reached their goal weight.

  The UI design was intentionally simple and kept the main functionalities separated from each other. This allowed the user to mainly focus on the middle screen, where they would be entering and viewing their daily weights. This is where the user will spend most of their time and will only need to check the other screens sparingly. This keeps the app focused and without any unnecessary clutter or distractions.

How did you approach the process of coding your app? What techniques or strategies did you use? How could those techniques or strategies be applied in the future?

  I approached the process of coding the app by first analyzing the guidelines and rubric to break down all the elements I would need to incorporate and how the functionalities would work. During this phase I also hand-drew some sketches to come up with a basic UI design to reference later. After that, I used Android Studio to create the actual UI elements and see how they would look when the app was running by using the device emulator. After the UI elements were mostly finalized, I then focused on making the app fully functional, adding in the logic and backend code. I found this process to be helpful so I can get one aspect down at a time and work on the app piece by piece. I would continue to use this approach in future projects.

How did you test to ensure your code was functional? Why is this process important, and what did it reveal?

  I used the device emulator constantly to check functionality and make sure changing one thing didn't break another and that all the functionalities worked as I intended. This was incredibly useful as there were instances where certain functionalities would stop working after I tweaked something and I didn't know why. Running the app often using the device emulator helped me catch these issues frequently. I would then look at the logcat to see what the potential issue was, and use that information to fix what was wrong.

Consider the full app design and development process from initial planning to finalization. Where did you have to innovate to overcome a challenge?

  There were several times where I had to innovate and change my approach to how I wanted to address certain issues. Sometimes I would try a certain approach and then find out that that was not the best way to tackle that particular task and have to go back and try a different method. This exposed me to different practices and proved that there are usually many different ways to achieve an objective, and some work better than others depending on the context.

In what specific component of your mobile app were you particularly successful in demonstrating your knowledge, skills, and experience?

  I found the design aspect of the app to be where I most demonstrated my knowledge, skills, and experience. By hand-drawing the app's layout, I was able to visualize what the app would look like and make sure I wasn't forgetting any elements and how they would interact with each other. This step made designing the actual app in Android Studio go much smoother since I already had an idea of how it would look, making it easier to make sure I included all of the necessary elements in the layout. This in turn made the actual development go smoother since I already had all of my elements present where I wanted them, I just had to make them function and connect them.
