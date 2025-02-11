# Reaction Race

This application will be very simple. A dot on the screen will flash a certain color after a random amount of time, and you must select that color as fast as possible.


> [!NOTE]
>  This is a template for your startup application. You must modify this `README.md` file for each phase of your development. You only need to fill in the section for each deliverable when that deliverable is submitted in Canvas. Without completing the section for a deliverable, the TA will not know what to look for when grading your submission. Feel free to add additional information to each deliverable description, but make sure you at least have the list of rubric items and a description of what you did for each item.

> [!NOTE]
>  If you are not familiar with Markdown then you should review the [documentation](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax) before continuing.

## 🚀 Specification Deliverable

> [!NOTE]
>  Fill in this sections as the submission artifact for this deliverable. You can refer to this [example](https://github.com/webprogramming260/startup-example/blob/main/README.md) for inspiration.

For this deliverable I did the following. I checked the box `[x]` and added a description for things I completed.

- [x] Proper use of Markdown
- [x] A concise and compelling elevator pitch
- [x] Description of key features
- [x] Description of how you will use each technology
- [x] One or more rough sketches of your application. Images must be embedded in this file using Markdown image references.

### Elevator pitch

Reaction race is a super simple, super awesome game to play with your friends. There's a single icon on the screen that will flash a random color at random intervals, and you have to select which color it flashed as fast as you can. It then computes your average reaction time and saves it in the score leaderboard for everyone to see. Have fun trying to beat all your friends!

### Design

![Design image](startup_design.png)

There are 4 key parts of this design. First, there is the large center dot that will display the color for you to select. Second, there are the smaller dots that you click when the center dot changes to that color. Third, there is the profile icon in the top left that lets you change your display name or account. Fourth, there is the leaderboard icon in the top right that allows you to view global rankings.

![flowchart](flow_diagram.png)

### Key features

- Login with email verification using third party service
- Client-side randomizer and timer for optimized gameplay
- Database with login credentials and high scores
- Global leaderboard visible to all users

### Technologies

I am going to use the required technologies in the following ways.

- **HTML** - 3 HTML pages: one for login, one for gameplay, and one for leaderboard
- **CSS** - Styling for the application that handles changing the color of the main dot, as well as scaling for different screen sizes
- **React** - Allows for updating only center dot during gameplay, as well as a single page with different HTML components
- **Service** - VerifyRight for verifying validity of email usernames
- **DB/Login** - Store usernames, high scores, and averages in database. Scores won't be saved unless logged in.
- **WebSocket** - When a player gets a new high score, this score is shared with all other users through the leaderboard

## 🚀 AWS deliverable

For this deliverable I did the following. I checked the box `[x]` and added a description for things I completed.

- [x] **Server deployed and accessible with custom domain name** - [My server link](https://reactionrace.click).

## 🚀 HTML deliverable

For this deliverable I did the following. I checked the box `[x]` and added a description for things I completed.

- [x] **HTML pages** - HTML page for login, gameplay, and leaderboard
- [x] **Proper HTML element usage** - Organized HTML layout following common practices
- [x] **Links** - Links between all 3 HTML pages found in <nav>
- [x] **Text** - All of the necessary text is there
- [x] **3rd party API placeholder** - Email verification on login page will go through the VerifyRight API
- [x] **Images** - Images for the profile and leaderboard are rendered
- [x] **Login placeholder** - Login page with form for filling in email
- [x] **DB data placeholder** - DB data will hold the global leaderboard scores
- [x] **WebSocket placeholder** - WebSocket will update the leaderboard scores in real time

## 🚀 CSS deliverable

For this deliverable I did the following. I checked the box `[x]` and added a description for things I completed.

- [x] **Header, footer, and main content body** - Styled all of these elements appropriately and made footer hide when screen is too small
- [x] **Navigation elements** - used flex to line up all navigation elements
- [x] **Responsive to window resizing** - footer, profile, and leaderboard elements all disappear when screen is portrait, circles shrink as well.
- [x] **Application elements** - Everything is colored the way I want and they all resize correctly
- [x] **Application text content** - Used different fonts and weights to highlight more important information
- [x] **Application images** - Images move correctly and hide when necessary

## 🚀 React part 1: Routing deliverable

For this deliverable I did the following. I checked the box `[x]` and added a description for things I completed.

- [ ] **Bundled using Vite** - I did not complete this part of the deliverable.
- [ ] **Components** - I did not complete this part of the deliverable.
- [ ] **Router** - Routing between login and voting components.

## 🚀 React part 2: Reactivity

For this deliverable I did the following. I checked the box `[x]` and added a description for things I completed.

- [ ] **All functionality implemented or mocked out** - I did not complete this part of the deliverable.
- [ ] **Hooks** - I did not complete this part of the deliverable.

## 🚀 Service deliverable

For this deliverable I did the following. I checked the box `[x]` and added a description for things I completed.

- [ ] **Node.js/Express HTTP service** - I did not complete this part of the deliverable.
- [ ] **Static middleware for frontend** - I did not complete this part of the deliverable.
- [ ] **Calls to third party endpoints** - I did not complete this part of the deliverable.
- [ ] **Backend service endpoints** - I did not complete this part of the deliverable.
- [ ] **Frontend calls service endpoints** - I did not complete this part of the deliverable.

## 🚀 DB/Login deliverable

For this deliverable I did the following. I checked the box `[x]` and added a description for things I completed.

- [ ] **User registration** - I did not complete this part of the deliverable.
- [ ] **User login and logout** - I did not complete this part of the deliverable.
- [ ] **Stores data in MongoDB** - I did not complete this part of the deliverable.
- [ ] **Stores credentials in MongoDB** - I did not complete this part of the deliverable.
- [ ] **Restricts functionality based on authentication** - I did not complete this part of the deliverable.

## 🚀 WebSocket deliverable

For this deliverable I did the following. I checked the box `[x]` and added a description for things I completed.

- [ ] **Backend listens for WebSocket connection** - I did not complete this part of the deliverable.
- [ ] **Frontend makes WebSocket connection** - I did not complete this part of the deliverable.
- [ ] **Data sent over WebSocket connection** - I did not complete this part of the deliverable.
- [ ] **WebSocket data displayed** - I did not complete this part of the deliverable.
- [ ] **Application is fully functional** - I did not complete this part of the deliverable.
