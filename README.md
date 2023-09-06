<h1>Digita Bhem Task 1</h1>
<p>I have used eventlistener attached to a form with id-"registration-form" .It listens the form's submission and performs various calculations and logging of form data.</p>

<h6>The event listener is triggered when the "registration-form" is submitted.</h6>
<h6>`event.preventDefault();`this prevents the form from submitting its data to the server, effectively preventing a page refresh.</h6>
<h6>The script retrieves various form input values such as name, email, check-in date, check-out date, total days, total persons, room type, selected amenities, and advance amount.</h6>
<h6>It calculates the total cost of the room based on the selected room type and the number of days.</h6>
<h6>It also calculates the total cost of selected amenities based on their values.</h6>
<h6>It also calculates the total cost by adding the room cost and amenities cost.</h6>
<h6>And also calculates the balance by subtracting the advance amount from the total cost.</h6>
Finally, it updates several HTML elements with the calculated values and logs all the form data and calculations to the console.
