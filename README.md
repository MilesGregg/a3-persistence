Assignment 3 - Persistence: Two-tier Web Application with Database, Express server, and CSS template
===

Miles Gregg: https://a3-miles-gregg.herokuapp.com/
Must login with a valid Github account.

## Reminders Web Application

The Reminders web application allows you to fill out a form of information for each reminder you want to keep track of. Once you fill out the form reminder you can press the create button to submit data to the server to keep track of all reminders. You can then delete or edit a specific reminder based off of the row in the table.

- Used Express for all functionality on the server-side of the website.
- Using Passport.js and GitHub OAuth to allow users to login onto the website. I used the username on GitHub to keep track of each users unique ID that way.
- Used MongoDB to store all users data in a clean and safe way. Stores reminders by a unique ID generated by MongoDB.
- Utilized Pico.css (https://picocss.com/) for css framework. Made small adjustments for styling like button colors to get 100% on lighthouse tests.
- Five Express middleware packages I used were:
    - **Passport.js:** was used for login with GitHub OAuth to access users specific Reminders.
    - **cookie-session:** was used to store GitHub login information on the browser.
    - **compression:** was used to compress HTTP responses and requests.
    - **checkAuth:** I made this to check to see if the user was authenticated or not. If the user wasn't authenticated then it would navigate to the login screen.
    - **serve-static:** also known as express.static was used to serve static files to the server.

- Used a wide varity of HTML input tags such as `<input>` and `<textarea>`
- HTML only displays authenticated user data. 

## Technical Achievements
- **Technical Achievement 1**: implemented Passport.js to use GitHub OAuth for login.
- **Technical Achievement 2**: hosted website on Heroku.
- **Technical Achievement 3**: 100% on all lighthouse tests.
