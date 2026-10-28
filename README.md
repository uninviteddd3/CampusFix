# CampusFix — Campus Maintenance Reporting

**LION Code Challenge 2026 | Penn State Abington**

## Overview

CampusFix is a campus maintenance reporting web app prototype designed to help students, faculty, and staff report facility issues and track their progress until they are resolved.

The project addresses common campus problems, such as broken lights, leaking sinks, and damaged furniture. It also helps reduce duplicate reports by suggesting similar existing issues before a new report is submitted.

## Features

- **Issue reporting:** Submit a title, description, category, and campus location.
- **Photo attachments:** Attach an image to a maintenance report.
- **Search and filtering:** Find reports by keywords, category, or status.
- **Status tracking:** Track issues through Reported, In Progress, and Resolved.
- **Duplicate detection:** Identify potentially similar reports before submitting a new issue.
- **Upvoting:** Support an existing report instead of creating a duplicate.
- **Dashboard statistics:** View total reports and counts for each status.
- **Local data storage:** Save reports in the browser using local storage.

## Technologies Used

- HTML5
- CSS3
- JavaScript
- Browser Local Storage

The application runs in a web browser without requiring a separate server or database.

## How to Run

1. Download or clone this repository.
2. Open the project folder.
3. Open `index.html` in a web browser, such as Google Chrome.
4. Use the dashboard to create, search, filter, and update maintenance reports.

No additional dependencies or installations are required.

## Testing

The prototype was tested for the following functions:

- Creating maintenance reports.
- Attaching images to reports.
- Searching and filtering reports.
- Detecting potentially similar reports.
- Upvoting existing reports.
- Updating issue statuses.
- Saving and restoring reports after refreshing the browser.

## Limitations

CampusFix is a prototype that stores data locally in the browser. Reports do not automatically synchronize across different users or devices. Duplicate detection is based on basic text similarity and may miss some duplicates or identify unrelated reports as similar.

The prototype uses fictional sample reports and is not connected to real Penn State systems.

## Responsible Design

The application is intended to demonstrate a campus maintenance reporting workflow. Testing should use fictional information and sample images, without collecting personal information or photographs of real people.

## Future Work

Potential improvements include shared cloud storage, staff accounts, notifications, a campus map, and more advanced duplicate detection.

## Project Information

- **Project:** CampusFix
- **Event:** LION Code Challenge 2026
- **Affiliation:** Penn State Abington
- **Developer:** Individual student project
