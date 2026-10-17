# Hey, it's great to meet you!
My name is Robert Rossman, and welcome to my portfolio! This is my capstone for my Bachelor's of Science in Computer Science and it was created in line with requirements set out in Southern New Hampshire University's CS-499 Computer Science Capstone course. 

Namely, I was tasked with writing a professional self-assessment, performing a code review, and selecting a collection of artifacts from previous courses I completed throughout my time in SNHU's computer science program. 

These artifacts were chosen to represent the following categories of computer science:
- Software Design and Engineering, 
- Algorithms and Data Structure
- Databases
  
I also enhanced these artifacts to align with the following course outcomes:
1. "Employ strategies for building collaborative environments that enable diverse audiences to support organizational decision making in the field of computer science"
2. "Design, develop, and deliver professional-quality oral, written, and visual communications that are coherent, technically sound, and appropriately adapted to specific audiences and contexts"
3. "Design and evaluate computing solutions that solve a given problem using algorithmic principles and computer science practices and standards appropriate to its solution, while managing the trade-offs involved in design choices"
4. "Demonstrate an ability to use well-founded and innovative techniques, skills, and tools in computing practices for the purpose of implementing computer solutions that deliver value and accomplish industry-specific goals"
5. "Develop a security mindset that anticipates adversarial exploits in software architecture and designs to expose potential vulnerabilities, mitigate design flaws, and ensure privacy and enhanced security of data and resources"

# Professional Self-Assessment
## Coursework
After completing the coursework throughout SNHU's computer science program, I have greatly improved as a programmer and software engineer. Prior to completing my degree, I had years of programming experience from working with C# on projects in the Unity engine, but my skillset was somewhat limited beyond this.

An important core concept I learned is that of the software development lifecycle (SDLC). The SDLC was a repeated topic throughout my coursework, and it was instrumental to learn when seeing large projects through to completion. [One such project](https://github.com/Aldinyx/CS-465) required full-stack development as I was tasked with building a static client-facing travel website that used Express HTML and JavaScript that was connected to an admin-facing Angular single-page application. This project was one that also gave me experience working with databases and data structures as “Trip” JSON objects were stored and accessed via a MongoDB database.

Along with this, I learned the value of collaboration. Not only does collaboration lead to a more efficient workflow when done right, but having more eyes on a project can help spot errors. This is important, as the earlier an error is spotted in development, the better. Correcting errors earlier mitigates costly technical debt that can come from trying to correct a foundational issue later.

With this concept of technical debt in mind, I also learned how to communicate with stakeholders and why it is so crucial. In one course, I was tasked with designing an app based on a simple user story pertaining to wanting an app that can scan food products and give a healthiness rating. After coming up with some initial design concepts, I interviewed potential users about the sorts of features they would want to see in an app of this kind. These discussions and follow-up interviews greatly shaped my decisions and final designs for the app. Ultimately, I centered my design around being highly customizable to account for a wide variety of use cases and dietary concerns.

I also learned how to build a secure system which included learning about role-based access control, the triple A's of security (Authentication, Authorization, and Accounting), and defense in depth. I also performed unit testing and saw how running automated tests consistently while developing improves security and reduces technical debt. As a result, I have developed a security-focused mindset towards development and understand the value of “shifting left” on security by making security features a core part of a system’s design as opposed to an afterthought.
## Artifacts Summary
This portfolio features a collection of artifacts from previous courses I completed throughout my time in SNHU's computer science program. 

My first artifact was chosen to display my skills in Software Engineering and Design and is a 3D scene built using OpenGL. This artifact shows off my creativity and versatility as I use simple 3D shapes to build a realistic scene from reference photographs. I enhanced this artifact by adding a reference photo display and lighting and background settings. This greatly increases the value provided by the artifact and clearly communicates the scene’s connection to the reference photographs while maintaining usability.

My second artifact was chosen to display my skills in Algorithms and Data Structures and is an event-tracking app built in Android Studio. This artifact shows off my ability to create a fully-functional app, control the flow of data in a program, and consider tradeoffs when designing algorithms. I enhanced this artifact by adding the ability to make events recur after concluding, a sorting priority feature that determines where events are displayed in a list, and an option to disable notifications for an event. These enhancements support organizational decision making by giving users more control.

My third artifact was chosen to display my skills in Databases and is an animal shelter database dashboard built using Dash. This artifact shows my experience with databases as the dashboard requires integration with MongoDB to display its results. I enhanced this artifact by expanding the dashboard to let users create new entries and update or delete existing entries. Along with these powerful new features that greatly expand the functionality of the dashboard, I implemented a layer of security that requires an authorization via a password for every attempted use of these features.

# Code Review
[![alt text](https://img.youtube.com/vi/1-JvbwLivOo/hqdefault.jpg "Watch the video")](https://www.youtube.com/embed/1-JvbwLivOo)

Before enhancing the three artifacts I selected, I conducted an informal code review. For each artifact I discuss the functionality and errors present in its original version along with my planned enhancements.

In the end, most of these enhancements were completed, but some were changed or scaled back during implementation.

# Artifact One: 3D Scene
[Link to Artifact](https://github.com/Aldinyx/CS-330/blob/main/3D%20Scene.zip)
## Screenshots
Scene with Default Lighting/Background and Reference Photo Display|Low Angle with More Dramatic Lighting|Orthographic Projection
:-------------------------:|:-------------------------:|:-------------------------:
![](https://github.com/Aldinyx/CS-330/blob/main/Screenshots/screenshot_1.png)  |  ![](https://github.com/Aldinyx/CS-330/blob/main/Screenshots/screenshot_2.png) | ![](https://github.com/Aldinyx/CS-330/blob/main/Screenshots/screenshot_3.png)
2nd Reference Photo with Red Lighting/Background|3rd Reference Photo with Green Lighting/Background|4th Reference Photo with Blue Lighting/Background
![](https://github.com/Aldinyx/CS-330/blob/main/Screenshots/screenshot_4.png) | ![](https://github.com/Aldinyx/CS-330/blob/main/Screenshots/screenshot_5.png)| ![](https://github.com/Aldinyx/CS-330/blob/main/Screenshots/screenshot_6.png)
## Narrative
### Briefly describe the artifact. What is it? When was it created?
The artifact I enhanced for the software design and engineering category of my capstone is a 3D scene I created in a Computer Graphics and Visualization course in December of 2025. It uses OpenGL to render a 3D scene built based on a series of reference photographs and features objects modeled using a combination of simple 3D shapes that are textured appropriately. The user can move the camera around the scene using the W, A, S, and D keys for horizontal movement, the Q and E keys for vertical movement, and the mouse to control the camera angle. The user can also switch between a perspective and orthographic display using the P and O keys.
### Justify the inclusion of the artifact in your ePortfolio. Why did you select this item? What specific components of the artifact showcase your skills and abilities in software development? How was the artifact improved?
I selected this item as I believe it showcases several skills, such as 3D modeling, custom texturing, lighting, and implementing interactivity while considering usability. This artifact shows these skills applied in a practical setting, with each coming together to complete the scene.

The artifact was improved by adding the ability to display some of the reference photos used to build the scene. By pressing the R key, the user can now toggle a reference photo display, and by pressing the F key, the user can cycle to the next photo. When a reference photo is displayed, the scene’s camera is positioned and angled to closely match the photo.

Additionally, the artifact was improved by adding the ability to change the lighting and background color of the scene. By pressing the L key, the user can now cycle through a series of eight lighting presets. Similarly, by pressing the B key, the user can now cycle through a series of 14 preset background colors.
### Did you meet the course outcomes you planned to meet with this enhancement in Module One? Do you have any updates to your outcome-coverage plans?
Originally, I planned on meeting course outcomes two and four with this enhancement and I feel that I have met these outcomes. I think the artifact’s value has improved significantly with the addition of the reference photo display, and lighting and background settings, which aligns it well with course outcome four. I also think the enhancements align with course outcome four as the reference photo display is communicated especially well with it being clear how the reference images shown relate to the 3D scene. On top of this, the reference photo display is shown in a separate window to avoid blocking the view of the 3D scene and increase usability. 

However, there is some room for improvement. Most glaringly to me is the absence of a way to see the controls for the scene. After the enhancements, there are more than twelve different inputs the user can use to manipulate the scene. A toggleable display with the controls that is shown when opening the scene would help greatly with this.
### Reflect on the process of enhancing and modifying the artifact. What did you learn as you were creating it and improving it? What challenges did you face?
The process of enhancing and modifying the artifact was quite difficult but also rewarding. While I had experience in OpenGL from the class I built the scene in, most of what I was attempting to accomplish was new to me. Notably, I did not know how to create a UI element that stays on screen regardless of the camera’s position as I had only worked with 3D objects. Additionally, while I already had the code to create and bind a texture, I did not know how to apply this to a UI element. I had many smaller challenges too, such as needing to figure out I had to use forward declaration due to having two headers include one another.

My biggest diversion came from trying to display the reference photos in a separate window. I completed most of the code for this, even having a window scaled based on the main window and positioned directly beside it, but I struggled with drawing the photos on the second window. While polishing the artifact, I discovered that my issue involved neglecting to share resources from the main window when creating the new window. This troubleshooting process also helped me implement the lighting and background settings by increasing my familiarity with GLFW functions.

# Artifact Two: Event-Tracking App
[Link to Artifact](https://github.com/Aldinyx/CS-360/blob/main/Event-Tracking%20App.zip)
## Screenshots
Login Screen               |Event List Screen with Sorted Events|Event Details Screen
:-------------------------:|:-------------------------:|:-------------------------:
![](https://github.com/Aldinyx/CS-360/blob/main/Screenshots/login_screen.png)  |  ![](https://github.com/Aldinyx/CS-360/blob/main/Screenshots/sorted_events_screen.png) | ![](https://github.com/Aldinyx/CS-360/blob/main/Screenshots/basic_event_details.png)
Recurring Events Setting|Sorting Priority Setting|Notification Setting
![](https://github.com/Aldinyx/CS-360/blob/main/Screenshots/recurrence_period.png) | ![](https://github.com/Aldinyx/CS-360/blob/main/Screenshots/sorting_priority_setting.png)| ![](https://github.com/Aldinyx/CS-360/blob/main/Screenshots/notification_setting.png)

## Narrative
### Briefly describe the artifact. What is it? When was it created?
The artifact I enhanced for the algorithms and data structure category of my capstone is an event-tracking app I created in SNHU's CS-360: Mobile Architecture & Programming course in April of 2026. It was built using Android Studio and lets the user track events that have a title, date, and time. Events are listed on a Main activity screen and new events can be created by tapping a plus icon. Once an event is created, it can be edited or deleted by tapping it in the list. The app also checks periodically if an event is happening on the current day and will send an SMS notification for each one that is.

The app also features a simple login screen that allows users to create a login with a username and password combination or login with an existing combination. On first login, the app will also request the necessary permissions to send SMS notifications. Importantly, the app will still function even if these permissions are denied.
### Justify the inclusion of the artifact in your ePortfolio. Why did you select this item? What specific components of the artifact showcase your skills and abilities in software development? How was the artifact improved?
I selected this item because I believe it shows a breadth of skills and many of its core features involve algorithms and data structures. The app showcases my skills as a software developer through its logical flow that makes it accessible and easy to use. Ultimately, the data structures I created to store events and logins come together with the algorithms I use to manipulate them to form a simple, general-purpose application.

The artifact was primarily improved by adding three new features to events. One of these is the ability to make an event recurring. When creating or editing an event, there is now a new text field labeled “Days Till event Recurs.” This text field accepts a number and, if set to a value greater than zero, will make the event “recur” the set number of days later upon its conclusion. To implement this, I refactored the code to use two services that each have their own looping timer. One timer is slower and loops every 6 hours, while one is faster and loops every minute. The slower timer is used to send SMS notifications and store any events concluding within a day. These stored events are then used by the faster timer to check if any events that are known to conclude soon have concluded in the past minute. Upon an event’s conclusion, it is either deleted or its date is incremented by its set “Days Till Event Recurs” value.

The second new feature added to events is the ability to sort events by priority. When creating or editing an event, there is a new NumberPicker labeled “Sorting Priority” that allows the user to pick a number from one to five. This number will then determine the placement of the event on the main event list screen, with higher priority events being listed before lower priority events. This was done by creating a custom Comparator class that compares events using their sorting priority, sorting the list of events using this Comparator, and reversing the sorted list so that the events appear in descending order of priority rather than ascending.

The last new feature added to events is a simple notification setting picker. By default, events will send an SMS text notification on the day they conclude. With this setting, users can now also set an event to send no notification upon its conclusion. This uses a picker as opposed to a simple toggle to account for the possibility of future notification settings.
### Did you meet the course outcomes you planned to meet with this enhancement in Module One? Do you have any updates to your outcome-coverage plans?
I planned to meet course outcomes one, two, and three with this enhancement. I feel that I have adequately met course outcome one, as the app already supported organizational decision-making to some degree prior to any enhancements. The improvements further this goal by giving even more opportunities for organization with sorting priorities and the automation possibilities using recurring events.

I also feel I met course outcome two, as the app is clean and communicates its function well. However, some of its implementation could still probably be clearer or otherwise allow for more customization. Namely, the notification feature is still rigid, and more could be done to ensure the app is adapted to more audiences. This could include adding an option for push notifications or giving more options pertaining to when the user should be notified of an upcoming event.

Lastly, I feel that I have met course outcome three as the new recurring event and sorting priority features both required an adherence to algorithmic principles and a consideration of trade-offs. Efforts were also made to reduce the number of intensive operations happening frequently by splitting up checks into a slower and faster timer.
### Reflect on the process of enhancing and modifying the artifact. What did you learn as you were creating it and improving it? What challenges did you face?
The process of enhancing and modifying the artifact was characterized by a series of small improvements and course-corrections over time. I was able to complete all the features I planned to, but the exact implementation of these features differs from my initial conception. 

For instance, I initially used a NumberPicker with custom values for the recurring event option. This NumberPicker featured values like “Recur Every Day,” “Recur Every Week,” and “Recur Every Year.” This is more convenient than the current implementation in several ways, but I was troubled by the number of edge cases that were not covered. For example, while adding options for recurring every one to six days and every week may work well enough for most situations, what if a user wants an event that recurs every week and a half? It became apparent that offering the ability to input any number of days increased functionality. Usability could perhaps be increased while maintaining functionality if this field were to be coupled with a NumberPicker that allows the user to specify between days, months, and years.

The sorting priority feature required less iteration, but it differs significantly from my initial conception. Originally, I imagined sorting events by categories or symbols, but it was unclear how this would manifest in the event list. Partially due to this lack of clarity, it made more sense to make the feature's effect on sorting more explicit by trading out the sorting “categories” for a numerical priority. I think this final implementation is both easier to understand and more useful.

# Artifact Three: Animal Shelter Database Dashboard
[Link to Artifact](https://github.com/Aldinyx/CS-340)
## Screenshots
## Narrative
# Briefly describe the artifact. What is it? When was it created?
The artifact I enhanced for the databases category of my capstone is database dashboard for a fictional rescue-animal training company I created for SNHU’s CS-340: Client/Server Development course in February of 2026. It was built using PyMongo and JupyterLab to interface with a MongoDB animal shelter database. Additionally, a CRUD (Create, Read, Update, Delete) module was created and used for the project. 

Dash is also used to display a user-friendly dashboard. This dashboard features radio buttons that let the user filter for types of rescue dogs and a data table for selecting and viewing animal entries. There is also a pie chart that displays the quantities of the breeds of animals currently being shown in the data table and a map that shows the geolocation of the currently selected animal.

# Justify the inclusion of the artifact in your ePortfolio. Why did you select this item? What specific components of the artifact showcase your skills and abilities in software development? How was the artifact improved?
I selected this artifact because it shows clear integration and manipulation of a database for practical purposes. Not only does this artifact show my knowledge of databases, but it also shows my proficiency with several tools through the integration of MongoDB, JupyterLab, and Dash. 

I also felt that this artifact was a good choice as it had plenty of room for sensible improvements. Despite an entire CRUD module being created for this project, the original version of the Dash dashboard only really made use of the “Read” functionality. To create a new entry, update an existing entry, or delete an existing entry, one would need to run commands in the terminal. Given that the idea behind the project was to help a rescue-animal training company sort through animal shelter data, this was not very user friendly or efficient.

Thus, my improvements primarily involved allowing the user to Create, Update, and Delete entries via the Dash dashboard and augmenting these additions with some new security features. On the dashboard, there is now a column of text input boxes with labels corresponding to the values of entries in the table. When an entry is selected, these input boxes are automatically filled with the entry’s information. Users can edit these input boxes and then press one of three new buttons to either create a new entry with the input values, update the selected entry with the input values, or delete the selected entry. When one of these buttons is pressed, the data table on the dashboard is updated accordingly.

To add a layer of security, these buttons are considered admin features. For a button to work, the user must type a valid password in a new Admin Authorization text input box. This forces each admin action to be authorized, preventing a potential malicious actor from having full privileges simply by accessing the dashboard. There is also a text display that informs the user of whether their attempted action succeeded or failed.
# Did you meet the course outcomes you planned to meet with this enhancement in Module One? Do you have any updates to your outcome-coverage plans?
I planned to meet course outcomes four and five with this enhancement. I feel that I have met course outcome four, as the new features on the dashboard demonstrate my ability to use innovative tools. Beyond this, the enhancements deliver significant value by providing a user-friendly way to access previously neglected CRUD methods.

I feel that I have met course outcome five as the powerful new admin features have been coupled with a layer of security. By forcing users to authorize every admin action, I am adhering to a Defense in Depth mindset. This is furthered by having the Admin Authorization input box clear after every button press, thus preventing an unauthorized user from accessing admin features if a dashboard with a valid entered authorization password is left unattended.
# Reflect on the process of enhancing and modifying the artifact. What did you learn as you were creating it and improving it? What challenges did you face?
The process of enhancing and modifying this artifact was surprisingly difficult at times. This project was originally built in a virtual machine supplied by the course I built it in. Perhaps my biggest challenge was getting the artifact running on my own device as it required many installations and dependencies, like the Austin Animal Shelter dataset, Python, Jupyter Lab, MongoDB, a MongoDB Command Line Database Tool to use the “mongoimport” command, Mongo Shell, PyMongo, and Dash.

After getting the project running, things were still not entirely simple. I quickly decided to use a series of input boxes as this would likely be the best way to let the user edit all values of an entry. This required me to broaden my understanding of how Dash callbacks work. I eventually figured out that updating each input box required including it as an output for a callback triggered by selecting an entry in the data table. 

The Create, Update, and Delete functions corresponding to the new buttons also gave me difficulties as I had several errors involving the syntax of the inputs, outputs, and states of the callbacks. I particularly ran into challenges when trying to make the admin buttons both refresh the filter to update the data table and clear the Admin Authorization input. I eventually realized that Dash does not permit multiple callbacks having the same list of outputs by default and that to I needed to use the “allow_duplicate” argument to resolve this.

Enhancing the artifact also gave me experience with UI design and HTML. I found I needed to move around various parts of the dashboard’s layout to keep it visually coherent and accommodate the new features. Visual clarity also motivated my addition of the text display indicating the result of pressing the admin buttons as this feature was not part of my initial enhancement plan.


