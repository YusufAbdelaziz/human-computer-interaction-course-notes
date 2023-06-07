# Lecture 2 - User Research Intro and MS Office 2007 design case.

- What were the two important aspects of user research ?
    - **Working** with users rather than guessing (**user-centric design**).
    - **Invisible** interfaces (**task-oriented design**).
- Why User Research is important ? Qualcomm device for truckers example.
    
    ![Untitled](Lecture%202%20-%20User%20Research%20Intro%20and%20MS%20Office%202007%2001b0d3def97b4a68b26a8c4b0c583a5c/Untitled.png)
    
    - Qualcomm created a device for truckers.
    - Initial versions had small buttons because the first design was done by guessing.
    - **User research** discovered surprising findings →
        - Truckers often have big hands.
        - Often wear gloves.
    - This study was made by “**participant observation**” which means that we’re observing how the trucker interacts with the device by just sitting next to the trucker during his working day. This is called a “**usability study**” which involves the observation of a user using the system and the user’s usage behavior is being recorded to come up with a better experience for the user.
    - From the study, a better design has emerged →
        - **Large touch screens** for big hands.
        - **Stylus Pens** for the gloves.
- Case Study - Microsoft Office UI Design.
    - Introduction and material used for the case study.
        - What we’re trying to know is how was the Microsoft Office design evolved.
        - How did Microsoft involve users in the redesign of the Office Interface starting 2003.
        - How did the design team transitioned from guessing-based design to user data based design ?
            
            ![Untitled](Lecture%202%20-%20User%20Research%20Intro%20and%20MS%20Office%202007%2001b0d3def97b4a68b26a8c4b0c583a5c/Untitled%201.png)
            
        - If you have time, watch **[The Story Of Ribbon](https://www.youtube.com/playlist?list=PLDMDz18kBJoxJ5VqK51FcrE8bCL2ScWfx)** by Jensen Harris who was a PM in Microsoft Office team. In this talk, you’d get to know how the Office team managed to transition from design by **guessing** to design by **user data**.
        - There’s also a [blogposts](https://learn.microsoft.com/ar-sa/archive/blogs/jensenh/table-of-contents) provided by Microsoft for Office 2007 design progress.
    - What are full-featured systems? What are the challenges of these type of systems? What is a **Bloatware**?
        - A Full-featured system (like MS Office or Adobe Photoshop) is a type of application which includes several features to fulfill the possible needs of its users.
        - The problems or challenges with this type of systems are:
            - Increased feeling that the application is **complicated**.
            - Increased **difficulty** to find or learn how to do things.
            - More **focus on tool** than on task.
        - A **Bloatware** is a term often used to describe a product that seem to have too **many features**, too many **megabytes**, too **slow**, too **difficult to use**, or simply too **much**.
    - State of MS Office between 97 and 2003.
        - WSJ published a story about MS Office being bloated with a very large list of commands (about 4500 commands).
        - There was a miles-long list of **feature requests** from customers.
            
            ![Untitled](Lecture%202%20-%20User%20Research%20Intro%20and%20MS%20Office%202007%2001b0d3def97b4a68b26a8c4b0c583a5c/Untitled%202.png)
            
        - Since 1997, people were feeling less in control of the program.
        - Menu and toolbar system was not scalable enough to fit the richness of the product.
        - Menus and toolbars are essentially full, people did not even notice new commands from version to version.
        - People were not finding or using new features.
        
    - Earlier attempts to reduce the perception of “bloat”.
        - Office 2000 introduces new UI mechanisms →
            - Adaptive (Personalized) Menus.
                - It was initially called “**adaptive menus**” but the naming was not obvious so it was changed to “**personalized menus**”.
                - The main idea behind it is that you click on a top-level menu which opens a short list of most likely used command by a user.
                - Clicking on the **chevron** (the downwards arrow icon) will expand the menu to show the full contents.
                - This feature becomes handy if the user finds what he/she wants in the short menu.
                - However, the short list may not include what the user wants (prediction was incorrect) which results in clicking on the chevron subconsciously without even checking the short list.
                - This is considered to be a bad UX because the user has to scan two lists (small and large lists) to find what functionality he/she needs.
                - Despite the failure of the personalized menus, it was a brilliant idea but implemented poorly due to the lack of sophisticated predictive algorithms back then.
                    
                    ![Untitled](Lecture%202%20-%20User%20Research%20Intro%20and%20MS%20Office%202007%2001b0d3def97b4a68b26a8c4b0c583a5c/Untitled%203.png)
                    
            - Rafted Toolbars.
                - The number of toolbars was big so the working area may become small.
                - Instead of allocating a line for the whole toolbar, an algorithm is used to predict the least likely used toolbar buttons by the user. This may lead to have multiple buttons from different toolbars in the same line.
                - The least likely used buttons are moved from the toolbar into an “**overflow**” area at the end.
                    
                    ![Untitled](Lecture%202%20-%20User%20Research%20Intro%20and%20MS%20Office%202007%2001b0d3def97b4a68b26a8c4b0c583a5c/Untitled%204.png)
                    
        - The main idea behind the new UI mechanisms is to rely on **customization** to hide unnecessary items so the user does not see lots of menu items or toolbar buttons.
        - Unfortunately, customization wasn’t a successful idea because of the algorithms used for customization was working improperly which leads to inaccurate menus.
        - This led to adding **complexity** and **inefficiency** to the interface, why?
            - Bad selection of short menu items appearing to the user requires him an additional scan of the full menu (scanning menus took twice as long).
        - Features like adaptive menus and rafted toolbars were turned off by default later in applications using them.
        - Jensen Harris said : “Auto-customization, unless it does a perfect job, is usually worse than no customization at all”.
    - Why do these attempts fail ?
        - Quoted from Jensen :
            - “At Microsoft, (say, pre-2003), design decisions were mostly supported by **guesswork**”.
            - “much of what we did was based on **feel**, **estimation**, and **guesswork**”
            - “Anything we would have done in the past would have been based more on guesswork and bias than on **reality**.”
        - MS Office team was launching new features to the app but there weren’t even noticed by the users. So the team introduce ******************Task Pane****************** which is a window on the side that includes the possible tasks a user may want to accomplish rather than searching all menus.
            
            ![Untitled](Lecture%202%20-%20User%20Research%20Intro%20and%20MS%20Office%202007%2001b0d3def97b4a68b26a8c4b0c583a5c/Untitled%205.png)
            
        - However, when people start working on Word, they just close the **Task Pane** as it was shrinking the working area of the user.
    - Office UI design decisions after 2003. What decision did MS Office managers make to change the basis on which UI was designed ?
        - The team managers of MS Office decided that the UI changes should be based on real data.
        - Therefore Microsoft Office **Custom Experience Improvement Program** (CEIP) was introduced. The main idea is to collect user’s usage data and send it to MS servers.
        - This will help in learning about:
            - Types of commands that are being frequently used.
            - Users that are using Office in Fullscreen.
            - etc.
        - Office 2003 users see a balloon popping up asking "Help Make Office Better.“
        - Clicking on the balloon enrolls the user in the CEIP and collects anonymous data about how the user uses the software and on what kind of hardware.
    - Data Collected for design team of Office 2007.
        - More than 1.3 billion sessions of usage data.
        - Sessions here indicate, for example, a 30-minutes session of tracking the user usage which may include clicking buttons or any kind of interaction with the Office.
        - Jensen stated that about 70% of Word and Outlook data were thrown away. This happened because storing a gigantic amount of data will require strong servers.
        - “For the first time, we have the data we need to make intelligent decisions” Jensen stated →
            - Which commands people often use and which they don't.
            - Which commands are used in sequence with which other commands.
            - Which commands are used 7x more with the keyboard than with the mouse.
            - How many documents they use at once.
            - How big people's screens are.
        - That’s why the **Paste** button was added due to the high frequency usage of paste command.
            
            ![Untitled](Lecture%202%20-%20User%20Research%20Intro%20and%20MS%20Office%202007%2001b0d3def97b4a68b26a8c4b0c583a5c/Untitled%206.png)
            
    - Lessons learned.
        - How design teams can make intelligent decisions if they consider a proper user research.
        - If you’re creating an app with large audience, make sure that you use a monitoring service to track the interaction of user with the app. For example, you can add a line of code when a button is clicked so that the monitoring service can store that interaction.
        - You can add separate table for tracking the interaction, but make sure you don’t send too much data to to the monitoring service as it’s not the app’s main functionality to only track the user interaction.
        - Using the data, you can use ML models to create an **accurate** personalized experience for each user.