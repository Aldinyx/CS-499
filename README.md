# Hey, it's great to meet you!
My name is Robert Rossman, and welcome to my portfolio! This portfolio is my capstone for my Bachelor's of Science in Computer Science and it was created in line with requirements set out in Southern New Hampshire University's CS-499 Computer Science Capstone course. 

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
# Artifact Three: Animal Shelter Database Dashboard
