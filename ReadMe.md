# OmniFocus to Due App Keyboard Maestro Macro #

The Macro sends the selected OmniFocus task to Due app.

Uses the following rules to set the Due Reminder date and time

* Will use the task’s start date if it is set to a future date
* Will use the task’s due date if it is set to a future date and there is no start date, or the start date is in the past.
* Will ask the user for the reminder time if the task has no future start or due date.

The macro also appends the task’s url to the reminder so you can quickly return to the task upon completing the Due app reminder