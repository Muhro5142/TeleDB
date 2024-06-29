# Project Manager Bot

A Telegram bot to help you manage your projects, save information about them, and update or delete them as needed. The bot allows you to add new projects, view all projects, update project details, assign skills to projects, and delete projects.

## Features

- **Add New Project**: Add a new project by providing its name, link, and status.
- **View All Projects**: Display a list of all projects you have added.
- **Update Project**: Update details of an existing project, such as name, description, link, and status.
- **Assign Skills**: Assign relevant skills to a project.
- **Delete Project**: Delete an existing project from your list.

## Installation

1. Clone the repository:
   
   git clone https://github.com/yourusername/project-manager-bot.git
   cd project-manager-bot

2. Create a virtual environment and activate it: python3 -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`

3.Install the required packages:
**telebot**

4.Create a config.py file with your bot token.

5.Run the bot.

**Usage
Commands
/start: Start the bot and display the main menu.
/info: Show the available commands and their descriptions.
/new_project: Add a new project.
/projects: Display all projects.
/update_projects: Update details of an existing project.
/skills: Assign skills to a project.
/delete: Delete a project.
Inline Buttons
The bot uses inline buttons to facilitate interaction:

Новый проект✅: Add a new project.
Все проекты📑: View all projects.
Изменить проект🛠: Update a project.
Навыки🛳: Assign skills to a project.
Удалить проект❌: Delete a project.**

