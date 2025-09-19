# Hebrew Google Calendar Events

A simple web tool to manage and duplicate Hebrew calendar events in your Google Calendar.

## The Problem

Google Calendar does not natively support recurring events based on the Hebrew calendar. This makes it difficult to manage annual events like birthdays, anniversaries, and memorials that are observed on their Hebrew date. This tool solves that problem by allowing you to easily copy events from one year to the next according to their Hebrew date.

## How to Use

1.  **Open the Application**: Navigate to the [Hebrew Google Calendar Events page](https://eitan101.github.io/heb-google-cal/docs/).
2.  **Authorize**: Click the "Authorize Application" button and sign in with your Google account to grant the necessary permissions.
3.  **Select Calendar**: Choose the Google Calendar you wish to manage from the dropdown menu.
4.  **Choose Years**: Select the "source year" (the year you want to copy events from) and the "destination year" (the year you want to copy events to).
5.  **Duplicate**: Click the "Duplicate" button. The application will read all events from the source year and create them on their corresponding Hebrew dates in the destination year.
6.  **Delete (Optional)**: You can also delete all events in the destination year using the "Delete events in destination year" button. **Use this with caution, as this action cannot be undone.**

## Technology

This is a purely client-side application built with:
- HTML, CSS, and JavaScript
- **Google Calendar API** for calendar integration.
- **Hebcal.js** for Hebrew date calculations.
- **Bootstrap** for styling.
