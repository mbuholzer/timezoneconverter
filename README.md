# Time Zone Converter

A simple, elegant web-based time zone converter that helps coordinate meetings across different time zones. This tool also generates calendar files (.ics) for easy import into calendar applications.

https://mbuholzer.github.io/timezoneconverter/

## Creator
**Michael Buholzer** ([@mbuholzer](https://github.com/mbuholzer))

## Description
This application converts times between Swiss Time (CET/CEST), Eastern Time (ET), and Central Time (CT) zones. It's particularly useful for teams working across these regions to schedule meetings and coordinate activities.

## Features
- Instant time zone conversion between:
  - Swiss Time (CET/CEST) - Fribourg, Bern, Zürich
  - Eastern Time (ET) - New York, Boston, Miami
  - Central Time (CT) - "Melanie Time", Dallas, Milwaukee, Chicago
- Automatic detection of user's local time zone
- Correct handling of Daylight Saving Time differences
- Meeting scheduler with:
  - Custom date selection
  - Meeting duration options (15, 30, 45 minutes or 1 hour)
  - Calendar file (.ics) generation for import into Outlook, Google Calendar, Apple Calendar, etc.
  - Multi-time-zone information included in generated calendar events

## Usage
1. Select your source time zone and time
2. View the equivalent times in all supported time zones
3. (Optional) Enter meeting details, select date and duration
4. Click "Create Calendar Event" to download a calendar file (.ics)
5. Import the .ics file into your preferred calendar application

## Technical Details
The converter uses JavaScript to:
- Calculate time differences between zones
- Handle Daylight Saving Time transitions
- Generate standards-compliant iCalendar (.ics) files
- Auto-detect user's time zone

## Installation
Simply clone this repository and open the index.html file in a web browser:

```bash
git clone https://github.com/mbuholzer/timezoneconverter.git
cd timezoneconverter
# Open index.html in your browser
```

## License
MIT License

## Acknowledgements
- Special thanks to "Melanie" for the the Central Time zone 😊
