# Calendar
Minimal, Open Source, Portable Calendar with Events, Notes, & Optional Notifications or Email Alerts

[Download Portable App](https://github.com/5aaa002d-8e7a-42e7-9514-c6019ef325a7)  |  [Updated (Dark Theme)](https://github.com/a2e15092-d4db-4e7a-a479-06716cb22863)

You should unzip it somewhere simple like C:\\

All of the files in the folder are needed for the .EXE to run.

![Calendar](https://github.com/escardel/Calendar/assets/39771493/067c5380-ccff-46b0-9d37-6ff8d9d2d570)
![Calendar Dark](https://github.com/escardel/Calendar/assets/39771493/f8f30fd5-a807-4360-aace-55a2d28e1d47)

Made with Visual Basic, this is a barebones Calendar app that is totally minimal and fully functional for the average person. 

### Features:

* Lightweight tray application with minimalist system icon
* Based on the familiar Windows 7 Calendar
* Simple text area to add events, notes, lists, URL links, etc.
* Underline, italic, or strikeout text
* Auto-complete common event phrases
* Auto-format time ranges
* Optional automatic system notifications 10 mins before events
* Optional morning email alerts for days with scheduled events/ notes
* Portable app, just copy/move the main folder and all data is backed-up

## How to use

1. Click on a date to add a note to the date.  
   * Adding a note/event will bold the date on the Calendar. Delete the text to unbold the date.
   * Built in auto-complete and underline for common events
     * mtg -> Meeting
     * bday -> Birthday
     * apt -> Appointment
   * Shorthand time ranges by removing spaces and colons.  Time will auto-format , examples:
     * 9am-330pm -> 9:00 AM - 3:30 PM
     * 325pm-5pm -> 3:25 PM - 5:00 PM
   * When a time range is auto-formatted, a simple notification is scheduled for ~10 minutes before the date and time occur.
     * This is unrelated to the Email Alert function
2. Add a Microsoft/Outlook/Hotmail account (used for To & From with SMTP) to enable email Alerts.
   * If there is an note present for the current date, the note will be emailed to you at 8am.
   * Email password is stored locally as plaintext. Update the source code or use at your own risk.
3. Use Task Scheduler in Windows to launch the program at startup if desired. 

Use Visual Studio to open the project and tweak the program to your preferences.
The origninal V1 (light themed) does not have notifications.
