📔 Daily Journal AI

A simple and interactive Daily Journal Web Application that helps users write, organize, search, and manage their daily journal entries with mood-based AI-style writing prompts.

🌟 Project Overview

Daily Journal AI is a frontend web application designed for daily reflection and personal journaling.

Users can:

- Create new journal entries
- Select their current mood
- Add a topic or theme
- Generate writing prompts based on mood and topic
- Search journal entries
- Filter entries by date
- Edit existing entries
- Delete entries
- Store journal data directly in the browser using Local Storage

✨ Features

📝 Journal Entries

- Create new daily journal entries
- Add title, date, mood, topic, and content
- Edit existing entries
- Delete entries

🤖 AI-Style Writing Prompts

The application provides writing prompts based on the selected mood.

Supported moods:

- 😊 Happy
- 😢 Sad
- 😌 Calm
- 🤩 Excited
- 😫 Stressed
- 😠 Angry
- 🙏 Grateful

🔍 Search

Search entries using:

- Title
- Topic
- Mood
- Journal content

📅 Date Filter

Users can select a particular date and view journal entries recorded on that date.

💾 Local Storage

Journal entries are stored in the browser using JavaScript "localStorage", so the data remains available when the page is reopened on the same browser.

📱 Responsive Design

The interface is designed to work on:

- Desktop
- Laptop
- Tablet
- Mobile devices

🛠️ Technologies Used

Technology| Purpose
HTML5| Web page structure
CSS3| Styling and responsive UI
JavaScript| Application logic and interactions
Local Storage| Storing journal entries
Netlify| Deployment

📂 Project Structure

public/
│
├── index.html
├── style.css
└── app.js

"index.html"

Contains the structure of the Daily Journal application, including:

- Navigation bar
- Journal entry cards
- Search section
- Date filter
- New entry form
- Edit entry form
- AI prompt section

"style.css"

Contains the complete visual design of the application, including:

- Layout
- Colors
- Buttons
- Cards
- Forms
- Modal window
- Responsive design

"app.js"

Contains the main application functionality:

- Creating entries
- Editing entries
- Deleting entries
- Searching
- Date filtering
- Local Storage
- Mood-based writing prompts
- Rendering journal cards

🚀 How to Run the Project

Step 1: Download or Clone the Project

Download the project files to your computer.

Step 2: Open the Project

Open the project folder in Visual Studio Code.

Step 3: Open "index.html"

You can open "index.html" directly in a browser.

For a better development experience, use the Live Server extension in VS Code.

Step 4: Start Using the Application

1. Click + Write Today
2. Select the date
3. Select your mood
4. Enter a topic
5. Click Generate AI Writing Prompt
6. Enter your journal title and content
7. Click Save Entry

🔄 Application Workflow

Open Website
     ↓
View Journal Entries
     ↓
Create New Entry
     ↓
Select Mood & Topic
     ↓
Generate Writing Prompt
     ↓
Write Journal Entry
     ↓
Save Entry
     ↓
Store Data in Local Storage
     ↓
Search / Filter / Edit / Delete

🧠 How the Writing Prompt System Works

The application contains a predefined prompt bank in "app.js".

Each mood has different prompts.

For example:

Mood: Happy
Topic: College

Prompt:
What made you feel genuinely happy today while thinking about College?

The selected mood and topic are combined to generate a suitable writing prompt.

💾 Data Storage

This project uses browser Local Storage.

Storage key:

daily_journal_ai_entries

Journal entries are saved as JSON data inside the browser.

No external database is required for the current version.

🔐 Privacy

Journal entries are stored locally in the user's browser.

The current version does not send journal content to an external server or database.

Users should understand that clearing browser storage can remove locally stored entries.

🎨 User Interface

The application provides a clean journal-style interface with:

- Navigation bar
- Journal cards
- Mood badges
- Search controls
- Date filtering
- Entry modal
- Writing prompt section
- Edit and delete controls
- Empty-state message

🌐 Deployment

The project is suitable for deployment using Netlify because it is a frontend web application.

The "public" folder contains the main website files.

🔮 Future Enhancements

Possible future improvements include:

- Real AI API integration
- User authentication
- Cloud database
- User profiles
- Journal statistics
- Mood charts
- Dark mode
- Export journal as PDF
- Download journal entries
- Image attachments
- Password-protected journals
- Automatic daily reminders

📌 Project Type

Frontend Web Application

Project Name

Daily Journal AI

Development Environment

Visual Studio Code

Technologies

HTML, CSS, JavaScript

Storage

Browser Local Storage

Deployment

Netlify

👩‍💻 Author

Developed as a web development project demonstrating frontend development, JavaScript functionality, browser storage, search/filter operations, and interactive UI design.
