# CS-360-Final-Project
Android Inventory App


#### Briefly summarize the requirements and goals of the app you developed. What user needs was this app designed to address?
The purpose of this app is to help the user keep track of items in their inventory. Users begin by creating an account so that they can securely log in, and upon logging in they are able to add items to their inventory list as well as the amount of items in the inventory. Item types are assigned an ID as they are added to the list. In a future release, the plan is to allow multiple users to have access to the same inventory list so that when an items amount hits zero, SMS notifications will be sent to let users know that they not longer have a particular item in their inventory.


#### What screens and features were necessary to support user needs and produce a user-centered UI for the app? How did your UI designs keep users in mind? Why were your designs successful?
The user needed to use a few screens and features to make the app functional for use. To start, the user needs to be able to log into the app. To achieve this, they must have an account, so I created a login screen with a button that would allow them to create a username and password that would be stored in a mySQL Lite database. Once the account is created, they can return to the login page to log in with those credntials. This leads them to the invenotry list page, where they can add items to the invenotry list. Adding items sends the user to a page to enter item information and count. Once an item is in the list, they can select items to edit their data and count, as well as delete the item completely. There is also an unfinished SMS notification feature that the user can access from the inventory page. I designed my UI with simplicity and design in mind. I think the app should be easiy to navigate without needing to give the user a full tutorial, and the design should be enjoyable to look at, so I did my best to acheive both with my design. 


#### How did you approach the process of coding your app? What techniques or strategies did you use? How could those be applied in the future?
Coding the app was the most challenging part of creating this app. I approached this process by looking at the requirements and using the android developers website to learn how to meet those requirements. If I was continuing to run into challenges, I resorted to tutorials on Youtube to help me figure out the problems I was having. This proved to be an effective means of learning how to solve these problems because I've found that watching someone demonstrate WHY things work the way they do to be extremely helpful in understanding how to make something happen.


#### How did you test to ensure your code was functional? Why is this process important and what did it reveal?
To ensure that my code was functional, I tested my code as often as possible. Using the Android emulator to run the application of both newer and older versions of Android ensured that the app would run on multiple versions of the OS. Since most Android users don't update their OS when the newest version is released, it's important to make sure that you test on multiple versions. Fortunatly, I did not run into any issues while doing this type of testing, so it revealed that my app was in good shape.


#### Considering the full app design and development process, from initial planning to finalization, where did you have to innovate to overcome a challenge?
My initial design for my app ended up being more complex than my final product. I initiually had more buttons on the inventory page that would allow the user to add, delete, and search for items. Given the limited amount of time that I had to create this app, I decided that a simpler approach would be a better choice. Instead of putting all of these buttons on one page, I chose to only include an "add" button on the inventory page and put the delete feature on the item page. I did not have time to implement a searching function, so that is something I would like to work on for a future release. Ultimately, I think this simpler appreoach made my apps design more attractive and gave me a good template to build off of for future development. 


#### In what specific component from your mobile app were you particularly successful in demonstrating your knowledge, skills, and experience?
While I am proud of the inventory page of my app, I wouldn't have been able to build it without understanding how to use a mySQL Lite database, which I first developed when creating the "login" and "create account" pages. I created these pages and their functionality first, and when I tested all of the possible outcomes of my actions on these pages, they were doing what I intended them to do. Acheiving these objectives was a huge step in developing the app because I had a better understanding of how to continue with the inventory functionality. 

