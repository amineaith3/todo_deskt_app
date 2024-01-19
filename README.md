# Todo App

A simple to-do application built with Python and Tkinter, using SQLite for database storage.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)

## Overview

The Todo App is a desktop application that allows users to manage their tasks. It provides a user-friendly interface for adding, updating, and deleting tasks, as well as features such as task filtering, calendar view, and daily task display.

## Features

- Task creation with various attributes (ID, Name, Description, Start Date, End Date, Frequency, Type, Status).
- Update and delete tasks.
- Filter tasks by date, type, or other criteria.
- Calendar view to visualize mandatory tasks on a monthly basis.
- Daily task display in a scrollable space within the main menu.

## Requirements

- Python 3.x
- Tkinter
- Tkcalendar
- SQLAlchemy (optional, for an alternative database interaction)

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/yourusername/todo-app.git
    cd todo-app
    ```

2. Install dependencies:

    ```bash
    pip install -r requirements.txt
    ```

3. Run the application:

    ```bash
    python main.py
    ```

## Usage

- **Update Tasks:** Click the "Update Tasks" button to access a menu for managing all tasks.
- **Filter by:** Click the "Filter by" button to filter tasks based on date or other criteria.
- **Calendar:** Click the "Calendar" button to view mandatory tasks on a monthly calendar.
- **Daily Tasks Display:** Daily tasks are displayed in a limited space on the main menu with a scrollbar for navigation.

