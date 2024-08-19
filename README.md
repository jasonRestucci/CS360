# CS360
Mobile Architecture and Programming


<ins> Briefly summarize the requirements and goals of the app you developed. What user needs was this app designed to address? </ins>  <br><br><be>

This app was designed to be an inventory management app for warehouses, convenience stores, or everyday use. Requirements and needs were met, including the ability to log in to the app with a username and password or create one if the user did not already have one. These log-ins are stored in a database. After logging in the user is met with a list of items and their quantity. The user can add new items, and edit, or delete existing items as well. These items are also stored in a database so they are maintained after the app is closed.


<ins> What screens and features were necessary to support user needs and produce a user-centered UI for the app? How did your UI designs keep users in mind? Why were your designs successful? </ins> <br><br><be>

The screens required were the log-in, item menu, create new item, and edit/delete item screens. Each UI element was created with ease of use and efficiency in mind. Android's multiple design and planning resources were a great help as well. I also kept the same color arrangement for the UI throughout the app to maintain a streamlined and consistent experience.


<ins> How did you approach the process of coding your app? What techniques or strategies did you use? How could those techniques or strategies be applied in the future? </ins> <br><br><be>

After the design stage was completed I split the project into smaller tasks and spread them throughout my schedule. These tasks are much more surmountable on their own and keep progress consistent. Constant unit testing, and integration testing as I started to piece the different parts of the app together ensured bugs and other issues never snowballed. I will admit I underestimated how long certain tasks would take. I will have better estimations in the future, however, I believe to a certain extent this is part of the process, and pivoting and working through these kinds of things is part of what makes a good developer.   


<ins> How did you test to ensure your code was functional? Why is this process important, and what did it reveal? </ins> <br><br><be>

I primarily use unit and integration testing. Both are equally important and you cannot have one without the other. You must ensure what you are creating is doing exactly what you think is does and you must also ensure it works with the other parts of your code exactly how you think it does. For example, I have a function that populates the item list with the item objects in memory whenever you open the item menu screen. This worked as intended before the database was implemented and all items were lost after you navigated away to a different screen. After I implemented the database, those items were not lost like they used to be, so that function would duplicate the list whenever the user opened the item menu screen. Unit testing showed that it worked as intended. Integration testing showed an interaction in the code that I did not foresee. That function only gets called once now.


<ins> Consider the full app design and development process from initial planning to finalization. Where did you have to innovate to overcome a challenge?
 </ins> <br><br><be>

I learned so much from this project and about app development, design, and Android Studio itself. There were a few times I had to figure a way around the problem. One of with was the user table in the database. I made the item table and connected it to the app first. After it was implemented I went back to create another table for the user data, but the table would never actually get created. I fixed this by creating a different database for the user table. Another was handling logins and registers on the same screen. I wanted to handle them both in the same activity so I would toggle the visibility for the login UI off and the visibility for the register UI on. Looking back, however, I could have just used the same UI elements but changed the text on the buttons and text views, live and learn.

<ins> In what specific component of your mobile app were you particularly successful in demonstrating your knowledge, skills, and experience?
 </ins> <br><br><be>

Before this project had very little experience with Android Studio, and with developing for Android devices. I think this app and its code demonstrate my skills in working with the unfamiliar and learning and developing well on the fly. 
