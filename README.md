# Kelompok Cosmic
## Rivan Alamsyah / 2100016103
## Tri Handaru Arif / 2100016058
## Muslim Safiq / 2100016074

# Task Manager App

## Overview

The Task Manager App is a Flutter mobile application designed to help users manage their tasks efficiently.
The app utilizes the Bloc architecture for state management and incorporates error handling for a smooth user experience.

## Features

- **Add New Task:** Easily add new tasks with titles, descriptions, start and end dates.
- **Edit and Delete Tasks:** Each tasks created can be edited and deleted.
- **Sort and Search:** Sort tasks by date or completion status, and search for specific tasks using keywords.
- **Error Handling:** The app includes error handling mechanisms to gracefully handle and display errors to users.

TasksBloc: Manages the overall state of tasks in the application.
TasksEvent: Represents events triggering state changes.
TasksState: Represents different states of the tasks, such as loading, success, or failure.

### Error Handling
Error handling is implemented throughout the app to ensure a seamless user experience. 
The LoadTaskFailure, AddTaskFailure, and UpdateTaskFailure states provide details about errors encountered during data loading, task creation, and task updates.

### Unit Test
Unit test has been integrated to test all functionalities from initial state to creating new task, updating task and deleting task
