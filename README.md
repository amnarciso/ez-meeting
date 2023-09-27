# ez-Meeting

## Overview

This repository contains a simple HTML file designed to be loaded on a tablet and displayed on the door of a meeting room. The HTML file provides real-time information about the room's availability, and it also displays the upcoming reservations for the room. This can help individuals quickly determine if the room is free for use or if it is currently occupied.

## Usage

To use this project, follow these steps:

1. Load the HTML file in a web browser on a tablet that you intend to place on the door of the meeting room.

2. Pass the following parameters in the URL:

   - `room`: Name of the meeting room.
   - `calendar`: ID of the Google Calendar associated with the meeting room.
   - `key` (Optional): If the room's calendar is not public, provide the `google_access_key`. If the calendar is public, you can omit this parameter.

3. The HTML file will display the current status of the meeting room, indicating whether it is free or occupied. It will also show the details of the next few reservations scheduled for the room.

## Requirements

- Tablet with a web browser.
- Internet connection for real-time calendar updates.
- Google Calendar associated with the meeting room.

## Configuration

Before using the HTML file, you need to configure your Google Calendar:

1. Make sure the Google Calendar associated with the meeting room is correctly set up with all the relevant reservations.

2. If the calendar is not public and requires authentication, generate a Google API access key and provide it as the `key` parameter in the URL when loading the HTML file.

## Notes

- Ensure that the tablet remains connected to the internet for real-time updates if the calendar is not public.

- This project is designed to be simple and lightweight, providing essential information about the meeting room's status. You can customize the HTML file's appearance or add additional features to meet your specific needs.

## License

This project is open-source and available under the [MIT License](LICENSE).

## Contributors

- amnarciso

Feel free to contribute to this project or report issues if you encounter any problems. We welcome your feedback and suggestions for improvement.