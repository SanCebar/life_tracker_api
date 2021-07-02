# Week 3 Assignment: Life Tracker

Submitted by: **Robert Velasco**

Deployed Application: [Lifetracker Deployed Site](ADD_LINK_HERE)
Frontend Repo: [Lifetracker UI](https://github.com/SanCebar/life_tracker_ui)
Old Repo with commit history: [Lifetracker DEMO](https://github.com/SanCebar/Life_Tracker_DEMO)

## Application Features

### Core Features

- [x] **The Nav Bar:** Implement customized views for users who are logged in vs not logged in.
- [x] If the user is logged in, it should display a **Sign Out** button. 
- [x] If no user is logged in, it should display **Login** and **Register** buttons
- [x] Display a logo on the far left side, and contain links to the individual detailed activity page. 
- [x] **The Landing Page:** Display a large hero image and a brief blurb on what this application is about
- [x] **Login Page:** A form that allows users to login with email and password.
- [x] **Registration Page:** A form that allows the user to sign up with their email, password, username, first name, and last name.
- [x] When a user first authenticates, they should be redirected to an authenticated view (i.e the detailed activity page). When they sign out, all frontend data should be reset.
- [x] Users have access to an overview Activity page that show one summary statistic about each of the 3 types of activity tracked.
- [x] The API should have a `security` middleware that only allows authenticated users to access resources and only allows users to access resources about themselves. 
- [x] Users should have the ability to track at least **1** types of activities (i.e Nutrition, Exercise, Sleep, etc.). Each activity should be tracked on separate pages.
- [ ] Deployed website with Heroku & Surge. 

**Detailed Activity Page:**
- [x] The detailed activity page should display a feed of all previous tracked activities.
- [x] The detailed activity should contain a form to contain relevant information. (i.e if tracking nutrition this form allows the user to capture calories, timestamp, image, category, etc.) 
- [x] The activity tracked should be given a unique id for easy lookup.
  * [https://github.com/SanCebar/life_tracker_api/blob/main/life-tracker-schema.sql] 

### Stretch Features

Implement any of the following features to improve the application:
- [ ] Each model (`nutrition`, `exercise`, and `sleep`) should also implement a `fetchById` method that queries the database for a record by its id and only serves it to users who own that resource. Create a new dynamic route on the frontend that displays detail about a single record. For instance, `nutrition/detail/:id` should show a page with all the information about a single nutrition item.
- [ ] Provide a dropdown that allows users to filter activity based on a certain attribute of any activity item.
- [ ] Calculate aggregate statistics based on time periods - such as daily, weekly, monthly aggregates.
- [ ] Create a page that shows all other users that use the life tracker application and allow users to follow each other.

### Walkthrough Video

https://www.loom.com/share/a5cb3aba461f4c42a0ae09cb2605d54c

### Reflection

* Did the topics discussed in your labs prepare you to complete the assignment? Be specific, which features in your weekly assignment did you feel unprepared to complete?

Yes. I  think the lab from Day 3 of Week 3 really helped me set up my backend. I also appreciated the introduction of custom hooks and context becuase it really helped me organize my code and develop much faster. I felt uneasy about implementing the form for the detailed activity page, especially about how to make calls to the backend for that feauture. 

* If you had more time, what would you have done differently? Would you have added additional features? Changed the way your project responded to a particular event, etc.
  
Given more time, I would've like to create more custom hooks and perhaps add to the context to improve the readablity of my code. I think some of my code is to single purpose and could be generalized to be more reusable. For example, the Modal component is specially configured for the Exercise Activity.

* Reflect on your project demo, what went well? Were there things that maybe didn't go as planned? Did you notice something that your peer did that you would like to try next time?

I'm happy with my project demo. I think I had a good pace and showed all of the features I implemented. I think it would have been nice to talk about/show how I refactored some of my code after using custom hooks.

### Open-source libraries used

- Add any links to open-source libraries used in your project.

### Shout out

Give a shout out to somebody from your cohort that especially helped you during your project. This can be a fellow peer, instructor, TA, mentor, etc.

I'd like to shoutout my capstone pod for being incredibly fun and supportive.
