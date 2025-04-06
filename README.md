<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dental Clinic Check-Up</title>
    <link rel="stylesheet" href="1.css">
</head>
<body>
    <h1>Book Your Dental Check-Up</h1>
    <form id="appointmentForm" method="POST" action="submit_appointment.php">
        <label for="name">Name:</label>
        <input type="text" id="name" name="name" required>

        <label for="email">Email:</label>
        <input type="email" id="email" name="email" required>

        <label for="phone">Phone:</label>
        <input type="tel" id="phone" name="phone" required>

        <label for="date">Preferred Date:</label>
        <input type="date" id="date" name="date" required>

        <label for="time">Preferred Time:</label>
        <input type="time" id="time" name="time" required>

        <label for="notes">Additional Notes:</label>
        <textarea id="notes" name="notes"></textarea>

        <button type="submit">Book Appointment</button>
    </form>
</body>
</html>
