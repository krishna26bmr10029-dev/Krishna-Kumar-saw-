# DIGITAL ALARM CLOCK
## Project Statement

### 1. Project Title
**Digital Alarm Clock**

### 2. Project Overview
The Digital Alarm Clock is a Python-based console application designed to simulate the essential functions of a digital clock and alarm management system.

The program provides an interactive menu through which the user can set and display the current time, create and manage alarms, check alarms, configure clock format and alarm sound, set a snooze value, create quick alarms, search alarms by name, use a countdown timer and stopwatch, view alarm statistics, and delete alarms.

The project demonstrates the practical use of fundamental Python programming concepts such as variables, lists, functions, conditional statements, loops, user input, string manipulation, and basic data processing.

### 3. Problem Statement
A basic alarm-clock application needs to provide a simple way for users to manage time-related tasks such as setting alarms and checking scheduled alarms. The objective of this project is to develop a menu-driven Python application that models these functions in a clear and easy-to-use console interface.

### 4. Objectives
- To develop a menu-driven Digital Alarm Clock using Python.
- To allow users to set and display the current time.
- To create, edit, delete, enable, and disable alarms.
- To allow alarms to have user-defined names.
- To provide a quick-alarm facility based on the current time.
- To check whether an active alarm matches the current time.
- To provide 12-hour and 24-hour clock display formats.
- To allow selection of different alarm sounds.
- To provide a configurable snooze value.
- To implement a countdown timer and stopwatch.
- To provide alarm statistics.
- To demonstrate structured programming using Python functions and lists.

### 5. Major Features
1. **Set Current Time** - Sets the hour, minute, and second used by the application.
2. **Display Time** - Displays the stored time in either 12-hour or 24-hour format.
3. **Add Alarm** - Creates an alarm with a unique ID, time, name, and active status.
4. **View Alarms** - Displays all stored alarms and their ON/OFF status.
5. **Edit Alarm** - Updates the time and name of an existing alarm.
6. **Delete Alarm** - Removes a selected alarm.
7. **Enable/Disable Alarm** - Changes the active status of an alarm.
8. **Check Alarm** - Checks active alarms against the current stored hour and minute.
9. **Quick Alarm** - Creates an alarm after a specified number of minutes.
10. **Search Alarm** - Finds alarms using a partial or complete alarm name.
11. **Change Sound** - Allows Beep, Bell, or Buzz to be selected.
12. **Set Snooze** - Stores a user-defined positive snooze duration.
13. **Change Clock Format** - Switches between 12-hour and 24-hour display.
14. **Countdown Timer** - Performs a user-controlled second-by-second countdown.
15. **Stopwatch** - Counts elapsed seconds until the user stops it.
16. **Statistics** - Shows total, active, and disabled alarms along with sound and snooze settings.
17. **Delete All Alarms** - Clears the complete alarm list after confirmation.

### 6. Technologies Used
- **Programming Language:** Python
- **Application Type:** Console / Command-Line Application
- **External Libraries:** None
- **Data Storage:** In-memory Python list
- **Programming Approach:** Function-based procedural programming

### 7. Expected Outcome
The completed application provides an interactive simulation of a digital alarm clock. It allows users to manage multiple alarms and perform additional time-related operations through a simple numbered menu.

### 8. Scope and Limitations
The current implementation is a simulation rather than a real-time system clock. The current time is manually stored by the program and does not automatically advance in the background. Alarms are checked only when the user selects the alarm-checking option.

The program also does not save alarms to a file or database, so the alarm list is lost when the program terminates. The snooze value is stored as a setting, but the current implementation does not perform an automatic snooze operation.

### 9. Future Scope
The project can be extended by:
- Connecting the application to the computer's real system clock.
- Adding automatic background alarm checking.
- Implementing actual sound playback.
- Implementing functional snooze behaviour.
- Saving alarms permanently using JSON or a database.
- Adding a graphical user interface.
- Adding recurring alarms and dates.
- Adding a modern notification system.

