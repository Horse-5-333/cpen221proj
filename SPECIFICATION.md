The interface is simple and intuitive. The main screen is the calendar view:

![calendar view](mockups/main-view.png)

It shows all events from shared course calendars, including deadlines, exams and custom group study sessions added by students.
In the following overview, "item" refers to any such event.

The present date is displayed at the top of the page, and the present day is highlighted in the calendar.

The calendar displays 5 weeks: the present week, one past week and three coming weeks. Any day that is not part of the present month is tinted (Nov in the image above).

Clicking on one of the days in the calendar brings up the day view:

![Oct 18 view](mockups/day-view.png)

For example, this is the view brought up by clicking Oct 18. This view displays all the assignments, exams and custom events on that day. For each assignment, the deadline is shown along with an "Open assignment" button. Pressing this button sends the user to the page linked by the contributor who originally added the event to the shared calendar.

There is also a button to mark this assignment as completed, which is made to help users keep track of their assignments.

Custom event items are presented differently:

![Oct 17 view](mockups/custom-event-view.png)

Custom events are presented with their name in quotation marks, both in the calendar view and in day view. In the day view, the details about the event are provided: the start time and location as specified by the organizer, as well as a button to flag whether you would like to join the event or not. When a student presses this button, the label (here "4 people coming") changes accordingly. If you change your mind, you can press the button again to remove the flag.

In the calendar view, the top bar has two interactive buttons: the "Add" on the right and the "Preferences" button on the left.

The user can press the "Add" button to add an item to the shared calendar:

![Add view](mockups/add-view.png)

This view presents the following fields:
- Name - the display name of the item to add
- Type: Deadline/Exam/Custom Event
- Course - which course the item is related to
- Link (hidden for any items that aren't type Deadline) - the link to the assignment page
- Date - which day to place the item on
- Time - what is the deadline / what time does the exam/custom event start

Pressing the add button on the bottom right of the panel returns the user back to the calendar view and adds the item to the shared calendar, so that all the users can see and access it. Pressing the cancel button on the bottom right simply returns the user to the calendar view, and no items are added to the calendar.

Pressing the menu button on the top left opens the preferences view:

![Preferences view](mockups/menu-view.png)

This view allows the user to configure the following:
- Show completed - allows the user to choose whether they would like to see completed assignments on their calendar view. If this option is checked, all assignments are displayed in calendar view. If this option is unchecked, assignments marked as completed aren't shown in the calendar view, but are still displayed if the user opens the view of the corresponding day.
- Show custom - allows the user to choose whether they would like to see custom events added by other users. If this option is checked, all custom events are visible in both calendar and day views. If this option is unchecked, the calendar and day views only display the user's own custom events. Events added by any other user are hidden.
- Courses - allows the user to select which courses they are enrolled in. Pressing the "Select..." button opens a dropdown menu and allows the user to select their courses:

![Course select dropdown](mockups/menu-select-view.png)

The calendar and day views only display courses selected in this menu.

Pressing the cancel button at the bottom of the preferences menu cancels applying any changes, and the options remain as they were before opening this view.

Pressing the save button applies the changes and updates the calendar view accordingly.
