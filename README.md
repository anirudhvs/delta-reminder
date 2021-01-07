# Delta Reminder 

A simple Google Chrome extension that helps you create a quick note by selecting the texts which can be saved privately or shared with your team on the go.


## Features
-   Private Reminders  
    Private reminders are only sent to you and cannot be viewed by anyone else.
-   Public Reminders  
    Public reminders are shared with the entire club along with the person who shared the information for clarifications.
-   Articles can also be shared.    
-   Badge showing number of reminders
-   Separate page to view all reminders.

## Screenshots
   ![Imgur Image](https://i.imgur.com/Nlclkeu.jpg) </br></br>
   ![Imgur Image](https://i.imgur.com/79nRXLR.jpg) </br></br>
   ![Imgur Image](https://i.imgur.com/RFRj6GC.jpg) </br></br>
   ![Imgur Image](https://i.imgur.com/7nxjUa9.jpg) </br></br>
   ![Imgur Image](https://i.imgur.com/U2uLBT4.jpg) </br></br>
   ![Imgur Image](https://i.imgur.com/n4lDlQd.jpg) </br></br>
   
## Future Scopes
1. Adding authentication
2. Integrate it with Delta Reminder Bot in discord and Google Calendar API.
3. Adding categories/tags to the articles shared.
4. Sending messages directly to Delta groups with Twilio
   
## Development

To install manually for development

1. Clone this repository
2. In Chrome go to Window => Extensions or [chrome://extensions/](chrome://extensions/)
3. Click the ``Load unpacked extension...`` button
4. Select the directory you created in step 2
5. Open the terminal in the folder where you have cloned the project.
6. Run the following commands

```
   cd server
   npm install
   node app.js
```
Any time you make a change go back to the Chrome extensions manager page and refresh.
