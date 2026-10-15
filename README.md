# Hey, it's great to meet you!
My name is Robert Rossman, and welcome to my portfolio! This is my capstone for my Bachelor's of Science in Computer Science and it was created in line with requirements set out in Southern New Hampshire University's CS-499 Computer Science Capstone course. 

Namely, I was tasked with writing a professional self-assessment, performing a code review, and selecting a collection of artifacts from previous courses I completed throughout my time in SNHU's computer science program. 

These artifacts were chosen to represent the following categories of computer science:
- Software Design and Engineering, 
- Algorithms and Data Structure
- Databases
  
I also enhanced these artifacts to align with the following course outcomes:
1. Employ strategies for building collaborative environments that enable diverse audiences to support organizational decision making in the field of computer science
2. Design, develop, and deliver professional-quality oral, written, and visual communications that are coherent, technically sound, and appropriately adapted to specific audiences and contexts
3. Design and evaluate computing solutions that solve a given problem using algorithmic principles and computer science practices and standards appropriate to its solution, while managing the trade-offs involved in design choices
4. Demonstrate an ability to use well-founded and innovative techniques, skills, and tools in computing practices for the purpose of implementing computer solutions that deliver value and accomplish industry-specific goals
5. Develop a security mindset that anticipates adversarial exploits in software architecture and designs to expose potential vulnerabilities, mitigate design flaws, and ensure privacy and enhanced security of data and resources

# Professional Self-Assessment

# Code Review
[![Watch the video](https://img.youtube.com/vi/1-JvbwLivOo/hqdefault.jpg)](https://www.youtube.com/embed/1-JvbwLivOo)

Before enhancing the three artifacts I selected, I conducted an informal code review. For each artifact I discuss the functionality and errors present in its original version along with my planned enhancements.

In the end, most of these enhancements were completed, but some were changed or scaled back during implementation.

# Artifact One: 3D Scene
## Briefly describe the artifact. What is it? When was it created?
The artifact I enhanced for the software design and engineering category of my capstone is a 3D scene I created in a Computer Graphics and Visualization course in December of 2025. It uses OpenGL to render a 3D scene built based on a series of reference photographs and features objects modeled using a combination of simple 3D shapes that are textured appropriately. The user can move the camera around the scene using the W, A, S, and D keys for horizontal movement, the Q and E keys for vertical movement, and the mouse to control the camera angle. The user can also switch between a perspective and orthographic display using the P and O keys.
## Justify the inclusion of the artifact in your ePortfolio. Why did you select this item? What specific components of the artifact showcase your skills and abilities in software development? How was the artifact improved?
I selected this item as I believe it showcases several skills, such as 3D modeling, custom texturing, lighting, and implementing interactivity while considering usability. This artifact shows these skills applied in a practical setting, with each coming together to complete the scene.

The artifact was improved by adding the ability to display some of the reference photos used to build the scene. By pressing the R key, the user can now toggle a reference photo display, and by pressing the F key, the user can cycle to the next photo. When a reference photo is displayed, the scene’s camera is positioned and angled to closely match the photo.

Additionally, the artifact was improved by adding the ability to change the lighting and background color of the scene. By pressing the L key, the user can now cycle through a series of eight lighting presets. Similarly, by pressing the B key, the user can now cycle through a series of 14 preset background colors.
## Did you meet the course outcomes you planned to meet with this enhancement in Module One? Do you have any updates to your outcome-coverage plans?
Originally, I planned on meeting course outcomes two and four with this enhancement and I feel that I have met these outcomes. I think the artifact’s value has improved significantly with the addition of the reference photo display, and lighting and background settings, which aligns it well with course outcome four. I also think the enhancements align with course outcome four as the reference photo display is communicated especially well with it being clear how the reference images shown relate to the 3D scene. On top of this, the reference photo display is shown in a separate window to avoid blocking the view of the 3D scene and increase usability. 

However, there is some room for improvement. Most glaringly to me is the absence of a way to see the controls for the scene. After the enhancements, there are more than twelve different inputs the user can use to manipulate the scene. A toggleable display with the controls that is shown when opening the scene would help greatly with this.
## Reflect on the process of enhancing and modifying the artifact. What did you learn as you were creating it and improving it? What challenges did you face?
The process of enhancing and modifying the artifact was quite difficult but also rewarding. While I had experience in OpenGL from the class I built the scene in, most of what I was attempting to accomplish was new to me. Notably, I did not know how to create a UI element that stays on screen regardless of the camera’s position as I had only worked with 3D objects. Additionally, while I already had the code to create and bind a texture, I did not know how to apply this to a UI element. I had many smaller challenges too, such as needing to figure out I had to use forward declaration due to having two headers include one another.

My biggest diversion came from trying to display the reference photos in a separate window. I completed most of the code for this, even having a window scaled based on the main window and positioned directly beside it, but I struggled with drawing the photos on the second window. While polishing the artifact, I discovered that my issue involved neglecting to share resources from the main window when creating the new window. This troubleshooting process also helped me implement the lighting and background settings by increasing my familiarity with GLFW functions.

# Artifact Two: Event-Tracking App
<div>
  <div>
    <img width="195" height="253" alt="Login Screen" src="https://github.com/user-attachments/assets/100c4114-fe8d-4f2d-b6c3-9d8aa9acead0" />
    <br>
    The app's login screen
  </div>
  <div>
    <img width="195" height="252" alt="Sorted Events Screen" src="https://github.com/user-attachments/assets/bbd6fb8f-99cf-4ae0-bdc4-fd8d576c07ea" />
    <br>
    The main Event List screen with events sorted by priority
  </div>
</div>

<div>
  <img width="195" height="384" alt="Basic Event Details" src="https://github.com/user-attachments/assets/bf11f5fe-f8bc-4e89-8518-da83a0866310" />
  The Event Details screen
</div>
<div>
  <img width="195" height="113" alt="Recurrence Period Enhancement" src="https://github.com/user-attachments/assets/5cac3ab8-8f63-4901-bf18-34ac240a6987" />
  The recurring events setting enhancement
</div>
<div>
  <img width="195" height="166" alt="Sorting Priority Setting" src="https://github.com/user-attachments/assets/3ef8590a-b7e6-4642-983e-68b35c8d7f2f" />
  The sorting priority setting enhancement
</div>
<div>
  <img width="195" height="166" alt="Notification Setting Enhancement" src="https://github.com/user-attachments/assets/bfcf6339-7b92-4ced-86ca-94d26e62c98a" />
  The notification setting enhancement
</div>



## Briefly describe the artifact. What is it? When was it created?
The artifact I enhanced for the algorithms and data structure category of my capstone is an event-tracking app I created in SNHU’s CS-360: Mobile Architecture & Programming course in April of 2026. It was built using Android Studio and lets the user track events that have a title, date, and time. Events are listed on a Main activity screen and new events can be created by tapping a plus icon. Once an event is created, it can be edited or deleted by tapping it in the list. The app also checks periodically if an event is happening on the current day and will send an SMS notification for each one that is.

The app also features a simple login screen that allows users to create a login with a username and password combination or login with an existing combination. On first login, the app will also request the necessary permissions to send SMS notifications. Importantly, the app will still function even if these permissions are denied.
## Justify the inclusion of the artifact in your ePortfolio. Why did you select this item? What specific components of the artifact showcase your skills and abilities in software development? How was the artifact improved?
I selected this item because I believe it shows a breadth of skills and many of its core features involve algorithms and data structures. The app showcases my skills as a software developer through its logical flow that makes it accessible and easy to use. Ultimately, the data structures I created to store events and logins come together with the algorithms I use to manipulate them to form a simple, general-purpose application.

The artifact was primarily improved by adding three new features to events. One of these is the ability to make an event recurring. When creating or editing an event, there is now a new text field labeled “Days Till event Recurs.” This text field accepts a number and, if set to a value greater than zero, will make the event “recur” the set number of days later upon its conclusion. To implement this, I refactored the code to use two services that each have their own looping timer. One timer is slower and loops every 6 hours, while one is faster and loops every minute. The slower timer is used to send SMS notifications and store any events concluding within a day. These stored events are then used by the faster timer to check if any events that are known to conclude soon have concluded in the past minute. Upon an event’s conclusion, it is either deleted or its date is incremented by its set “Days Till Event Recurs” value.

The second new feature added to events is the ability to sort events by priority. When creating or editing an event, there is a new NumberPicker labeled “Sorting Priority” that allows the user to pick a number from one to five. This number will then determine the placement of the event on the main event list screen, with higher priority events being listed before lower priority events. This was done by creating a custom Comparator class that compares events using their sorting priority, sorting the list of events using this Comparator, and reversing the sorted list so that the events appear in descending order of priority rather than ascending.

The last new feature added to events is a simple notification setting picker. By default, events will send an SMS text notification on the day they conclude. With this setting, users can now also set an event to send no notification upon its conclusion. This uses a picker as opposed to a simple toggle to account for the possibility of future notification settings.
## Did you meet the course outcomes you planned to meet with this enhancement in Module One? Do you have any updates to your outcome-coverage plans?
I planned to meet course outcomes one, two, and three with this enhancement. I feel that I have adequately met course outcome one, as the app already supported organizational decision-making to some degree prior to any enhancements. The improvements further this goal by giving even more opportunities for organization with sorting priorities and the automation possibilities using recurring events.

I also feel I met course outcome two, as the app is clean and communicates its function well. However, some of its implementation could still probably be clearer or otherwise allow for more customization. Namely, the notification feature is still rigid, and more could be done to ensure the app is adapted to more audiences. This could include adding an option for push notifications or giving more options pertaining to when the user should be notified of an upcoming event.

Lastly, I feel that I have met course outcome three as the new recurring event and sorting priority features both required an adherence to algorithmic principles and a consideration of trade-offs. Efforts were also made to reduce the number of intensive operations happening frequently by splitting up checks into a slower and faster timer.
## Reflect on the process of enhancing and modifying the artifact. What did you learn as you were creating it and improving it? What challenges did you face?
The process of enhancing and modifying the artifact was characterized by a series of small improvements and course-corrections over time. I was able to complete all the features I planned to, but the exact implementation of these features differs from my initial conception. 

For instance, I initially used a NumberPicker with custom values for the recurring event option. This NumberPicker featured values like “Recur Every Day,” “Recur Every Week,” and “Recur Every Year.” This is more convenient than the current implementation in several ways, but I was troubled by the number of edge cases that were not covered. For example, while adding options for recurring every one to six days and every week may work well enough for most situations, what if a user wants an event that recurs every week and a half? It became apparent that offering the ability to input any number of days increased functionality. Usability could perhaps be increased while maintaining functionality if this field were to be coupled with a NumberPicker that allows the user to specify between days, months, and years.

The sorting priority feature required less iteration, but it differs significantly from my initial conception. Originally, I imagined sorting events by categories or symbols, but it was unclear how this would manifest in the event list. Partially due to this lack of clarity, it made more sense to make the feature’s effect on sorting more explicit by trading out the sorting “categories” for a numerical priority. I think this final implementation is both easier to understand and more useful.

# Artifact Three: Animal Shelter Database Dashboard
