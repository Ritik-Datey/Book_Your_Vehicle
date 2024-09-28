The "Book_Your_Vehicle" program is a Java-based console application that allows users to select and book a vehicle, either a car or a bus, for travel based on their choice. The program also handles payments and ensures that users provide correct input through custom exception handling.

<b>Key Features:</b>
<ol> 
  <li>Vehicle Selection: </li>
  <ul>
    <li>Users can select between two main vehicle types: Car or Bus.</li>
    <li>Each vehicle type has multiple options with different rates per kilometer:</li>
    <ul>
      <li>Cars: Innova, Ertiga, Swift Dzire, Tavera.</li>
      <li>Buses: Mahindra (18-Seater), Force (28-Seater and 32-Seater), Eicher (40-Seater), BharatBenz (52-Seater).</li>
    </ul>
  </ul>
  <br>
  <li>Payment Calculation: </li>
  <ul>
    <li>The program calculates the total cost based on the distance (km) entered by the user and the rate per km of the selected vehicle.</li>
    <li>It prompts the user to make the payment and handles scenarios where the payment is less, more, or equal to the required amount.</li>
  </ul>
  <br>
  <li>Exception Handling: </li>
  <ul>
    <li>Custom exceptions are used to handle specific errors:</li>
    <ul>
      <li>MoneyLessException: Thrown when the payment is less than the required amount.</li>
      <li>IllegalInputArgument: Thrown when an invalid vehicle or option selection is made.</li>
    </ul>
  </ul>
  <br>
  <li>User Interaction: </li>
  <ul>
    <li>The interactive program prompts users to re-enter valid input in case of errors, ensuring a smooth booking experience.</li>
  </ul>
</ol>
<br><br>
<b>Program Flow:</b>
<ol>
  <li>Welcome Screen: Displays a welcome message and prompts the user to select a vehicle type.</li>
  <li>Vehicle Selection: Based on the user's choice, presents available options for cars or buses.</li>
  <li>Distance Input: Takes the travel distance in kilometers.</li>
  <li>Payment Processing: Calculates the total cost and asks the user for payment. Provides feedback based on the payment amount (exact, excess, or insufficient).</li>
  <li>Booking Confirmation: Confirms the booking if the payment is successful and provides a thank-you message.</li>
</ol>



<br><br>
