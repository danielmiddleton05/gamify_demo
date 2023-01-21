# gamify_demo
1. What are the various features you would like your project to offer?
  I will make an app which allows the user to "gamify" mundane aspects of their lives. For example, the user may decide to start working out regularly, everytime they complete a workout, they gain 'expereince points', when they skip a workout, they will loose 'health points'. The rewards and punishments will be set by individual users. If time and ability permits, I would like to have this app where users can create small groups. For example, a teacher could set up the rewards/punishments (ideally fun/silly things) and then invite the students through their own devices. A student forgets to bring in their textbook, loose 5 HP; they have a great response to a question, they gain 20 XP; or they loose all their HP and 'die', they have to sing an embarassing/silly song to be revived.

2. What are the API endpoints that you would need to set up for each feature? List them along with the respective HTTP verb, endpoint URL, and any special details (query parameters, request bodies, headers).
I am sure there will be many, mant more to add as I get started on the project, but so far here are the following I have thought of:
  GET in order to find the user's information
  Various POST to do things such as add user info, set rewards/punishments, set goals, etc.
  PUT/PATCH could work to edit the user's HP, XP, and various user statistics
  DELETE may be used to delete user data

3.Provide a description of the database tables required for your application, including column names, data types, constraints, and foreign keys. Include your database name. You can optionally include an ER diagram.
  The main table will refer to the user's statistics with the following columns: user id, user name, user level, current XP, current HP, level abilities/rewards. Again, depending on scale and scope, I may need to add multiple tables with foriegn keys (such as a "game master" table and "participant" tables.
