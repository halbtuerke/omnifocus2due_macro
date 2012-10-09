# OmniFocus to Due App Keyboard Maestro Macro #

The Macro sends the selected [OmniFocus][1] task to [Due][2] app.

Uses the following rules to set the Due Reminder date and time:

* Will use the task’s start date if it is set to a future date
* Will use the task’s due date if it is set to a future date and there is no start date, or the start date is in the past
* Will ask the user for the reminder time if the task has no future start or due date

The macro also appends the task’s url to the reminder so you can quickly return to the task upon completing the Due app reminder.

## Dependencies ##

* My [OmniFocus Macro Functions][3]

[1]: http://www.omnigroup.com/products/omnifocus/
[2]: http://www.dueapp.com
[3]: https://github.com/ChewingPencils/keyboard-maestro-omnifocus-functions