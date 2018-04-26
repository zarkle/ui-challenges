# CF 401 UI Challenge #1 - Elevator Panel

For this CSS code challenge, you will develop code that renders an elevator panel that matches the [provided mockup](https://github.com/codefellows/seattle-python-401d8/blob/master/28-model-relationships/assets/elevator.png).

You will then be adding JS code to make the elevator panel function according to the functional requirements below. You can control which way the elevator moves by selecting the ?floor? buttons on the panel. As soon as a button is selected, the elevator will begin moving toward that floor.

UI Requirements:
- A display panel that indicates the number of the current floor
- Green and red lights indicating whether the elevator is going up (green) or down (red)
- Four floor buttons
- Four floors behind the elevator panel, represented as images you select from any free source on the internet

Functional Requirements:
- A floor can be selected from the elevator panel.
- When a floor is selected, its button is highlighted.
- Clicking on a floor button in the panel will cause the floors in the background to scroll up and down.
- Multiple floors can be selected and will be executed in the order that they were selected.
- The chosen button should remain highlighted until the floor is reached.
- The current floor is shown on the display panel. (This is the large number on the panel display.)
- The elevator's current direction (up/down) is indicated by highlighting the corresponding green and red indicators in the display panel.
- A visual cue is provided when you have arrived at the selected floor. (Un-highlight the button, deactivate the direction indicators, and update the displayed floor.)
- Selecting a button anchor does not navigate or change the URL.
