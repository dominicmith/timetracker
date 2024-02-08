# IEEE2

Dare Timer

This is a simple web application for a "Dare Timer" designed to collect participant information and record the time elapsed during their dare challenge. The application consists of an HTML form integrated with a stopwatch feature.

Features

Participant Information Collection:

Users can input their name and phone number through the form. Both fields are marked as required, ensuring essential information is provided.

Stopwatch:

The application includes a stopwatch feature allowing users to track the time elapsed during their dare challenge. The stopwatch starts automatically upon clicking the "Start" button and stops when the dare ends. Time is displayed in hours, minutes, and seconds format (HH:MM:SS).

Submission:

Upon completing the dare challenge, users can submit their information along with the recorded stopwatch time. The form data is submitted to a Google Apps Script endpoint specified in the form's action attribute.

Feedback Message:

After submission, a feedback message is displayed to users indicating successful submission. The message is styled for visibility and appears in green color to denote success.

Usage

Input Participant Information:

Fill in the participant's name and phone number in the respective input fields.

Start Stopwatch:

Click on the "Start" button to initiate the stopwatch and begin tracking the dare challenge time.

Submit Information:

Once the dare challenge is complete, click on the "Submit" button to send the participant's information and stopwatch time.

Development The application is built using HTML and vanilla JavaScript, making it lightweight and easy to customize. Here's a brief overview of the key components:

HTML Structure:

Defines the layout of the form and its elements. Includes placeholders for participant name, phone number, and stopwatch display.

JavaScript Functions:

Implements stopwatch functionality using setInterval() to update time display every second. Handles the start, stop, and update operations of the stopwatch. Updates the hidden input field with the stopwatch time for submission.

Integration

The form submission is integrated with a Google Apps Script endpoint, allowing seamless collection and processing of participant data. Ensure that the provided Google Apps Script URL in the form's action attribute is configured correctly to handle form submissions.

Contribution Contributions to enhance the application's functionality or improve its user experience are welcome. Feel free to submit pull requests or suggest improvements to make the Dare Timer more efficient and user-friendly.
