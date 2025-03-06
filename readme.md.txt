# Website Questionnaire Bot

A simple, interactive chatbot that guides users through filling out a website questionnaire. This is a standalone HTML/JavaScript implementation that can be easily deployed on GitHub Pages.

## Features

- Conversational interface that makes form-filling more engaging
- Progress tracking to show users how far they've come
- Multiple-choice options for easy selection
- Branching logic for a personalized experience
- Response saving in case of refreshes or interruptions
- Mobile-responsive design
- No server-side code needed - works entirely in the browser
- Easy to deploy on GitHub Pages

## Setup and Deployment Instructions

### Prerequisites
- A GitHub account
- GitHub Desktop installed

### Deployment Steps

1. **Clone this repository**
   - Open GitHub Desktop
   - Click on "File" > "Clone Repository"
   - Select this repository

2. **View the files locally**
   - Navigate to the repository folder on your computer
   - Open index.html in your browser to test it

3. **Deploy to GitHub Pages**
   - In GitHub Desktop, make sure all changes are committed
   - Click "Push origin" to push to GitHub
   - Go to your repository on GitHub.com
   - Click on "Settings"
   - Navigate to "Pages" section
   - Under "Source", select "main" branch
   - Click "Save"
   - Wait a few minutes for deployment to complete

4. **Access your bot**
   - Your bot will be available at `https://[your-username].github.io/website-questionnaire-bot/`
   - Share this link with anyone who needs to fill out your questionnaire

## Customization

You can easily customize the bot by editing the following in index.html:

1. **Questions and flow**
   - Find the `questions` array in the JavaScript section
   - Modify existing questions or add new ones
   - Change the `nextId` properties to adjust the flow

2. **Design and appearance**
   - Edit the CSS styles at the top of the file
   - Change colors by modifying the CSS variables in `:root`

3. **Bot behavior**
   - Adjust timing and animations in the JavaScript functions

## Data Collection

- All responses are saved in the user's browser using localStorage
- For a production environment, you would need to add code to send this data to your server
- Sample code for this is provided in comments

## License

This project is available for free use for personal and commercial projects.

## Need Help?

If you need assistance with customizing or deploying this bot, feel free to reach out!
