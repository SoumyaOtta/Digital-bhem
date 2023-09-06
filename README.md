<h1>Digita Bhem Task 1</h1>
I have used eventlistener attached to a form with id-"registration-form" .It listens the form's submission and performs various calculations and logging of form data.

The event listener is triggered when the "registration-form" is submitted.
`event.preventDefault();`this prevents the form from submitting its data to the server, effectively preventing a page refresh.
The script retrieves various form input values such as name, email, check-in date, check-out date, total days, total persons, room type, selected amenities, and advance amount.
It calculates the total cost of the room based on the selected room type and the number of days.
It also calculates the total cost of selected amenities based on their values.
It also calculates the total cost by adding the room cost and amenities cost.
And also calculates the balance by subtracting the advance amount from the total cost.
Finally, it updates several HTML elements with the calculated values and logs all the form data and calculations to the console.
