My Concept is to create an interactive storytelling web application. The story that I will be portraying will be based around the cold war during the 1945 to 1991 period. Alongside this there will be elements of highly detailed sections for the user to use for research. The key features of this application will be:

A scrolling timeline using the timeline.js api

Within this timeline there will be discussion tabs for users to add their own comments / family experiences 

An interactive before and after map containing critical information about the cold war

Profiles of the main personnel within the cold war 

Discussion sections for users to use 

Additional resources, Used to fetch articles for the user to gain further information

Target Audience

My target audience is largely people having their first look at the cold war in detail. The expectations of this audience will be to have an enjoyable way of experiencing the data compared to a more conventional sheet full of mass data. My secondary audience is students/ researchers who are looking for a unique way to view the information. This unique method of storytelling engages the user more as it's interactive and a fun way to get the needed information they require.

Technology Stack: 

Node,js will be used to allow for full stack development and support npm

Express will be used as the framework due to its flexibility 

Web sockets will be used for users to utilise real time messaging in the forum section as well as within the timeline

MongoDB will be used to store imputed data

Bootstrap will be used for css

React will be used for fast

Data:

One source of data being stored internally will be the user login. This will be stored within the mongo DB server, allowing for the user to register a unique account with safe security

Another source of data that will be stored internally is the users posts on to the two sections of the application(the timeline and the debate section).  This data will also be stored within mongo db database

Another large sauce of data I'll be getting externally will be through the wikipedia api. This data will consist of the main historical figures within the cold war. The wikipedia api provides a great source of data for a vast amount of historical figures and is perfect for the intel needed for the page on personel.

The timeline.js api will be used to create the main skeleton of the timeline where features can be added to such as the comment feature. This requires a spreadsheet that i will need to make and implement afterwards

Another api needed for the data will be the leaflet api. This will allow me to add a scalable map easily alongside being able to add specific markers over locations.

There wil be a section for atricles where the apis ' new yorl times article search api' and 'national archieves api' will be used to display relevant articles.
