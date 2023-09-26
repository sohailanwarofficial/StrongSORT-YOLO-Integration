# StrongSORT-YOLO-Integration

# StrongSORT YOLO Integration

This repository contains code for integrating StrongSORT and YOLO to process video submissions and update a Google Sheet with the results.

## Overview

The code in this repository is designed to perform the following tasks:

1. Mount Google Drive to access necessary files.
2. Install and configure the required packages, including gspread and Ultralytics.
3. Authenticate with Google Sheets API and open a specific Google Sheet.
4. Search for a matching row with an empty "AA" column in the Google Sheet.
5. If a matching row is found, process a video from a provided URL using YOLO.
6. Store the YOLO results in a specific directory.
7. Retrieve the most recently added file in the YOLO results directory.
8. Generate a sharable link for the most recent file.
9. Send an email to the submitter with the sharable link.
10. Update the Google Sheet with the sharable link.

## Usage

To use this code, follow these steps:

1. Mount your Google Drive and ensure that the required files are in the correct directory.
2. Install the necessary Python packages.
3. Authenticate with Google Sheets API by running the provided code.
4. Run the main code to search for a matching row, process the video, and update the Google Sheet.

Make sure to customize the configuration and paths according to your specific setup.

## Dependencies

- Google Colab (for running the code in a Colab environment)
- gspread (for interacting with Google Sheets)
- Ultralytics (for YOLO processing)
- Python 3.x

## License

This project is licensed under the [MIT License](LICENSE).

Feel free to contribute or make improvements to the code as needed.
